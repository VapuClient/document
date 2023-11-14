# vapu.js

## 安装脚本

Script系统允许你自己添加需要的功能，使用指令（聊天栏输入）.script opendir

创建新的文件，以js为后缀，并写入js代码代码，重新启动客户端即可加载

脚本文件夹：C:\Users\%username%\vapu-scripts

**问题：和水影脚本互通吗？**

**答案是为什么不试试呢？(^^;**


## 示例脚本

```javascript
var timer = newModule({
	name: "Timer",
	category: "Blatant",
	description: "Change game speed"
})

var speed = timer.sliderOption("Speed",1.1,0.1,5.0,0.1);

timer.onDisable(function () {
	world.setTimer(1.0);
})

timer.onMotion(function (event) {
	world.setTimer(speed.getAsFloat());
})
```

```javascript
var regen = newModule({
	name: "Regen",
	category: "Blatant",
	description: "Faster regen"
})

regen.onTick(function(){
	if (player.health() < 20 && player.onGround()) {
		var sb = 0;
		while (sb < 120) {
			player.sendPacket(0x03, true);
			sb++;
		}
	}
})
```

## 基本方法

### `boolOption(String name, boolean initialValue)`
- 描述：创建一个布尔类型的选项。
- 参数：
  - `name`（String）：选项的名称。
  - `initialValue`（boolean）：初始值。
- 返回值：
  - 布尔类型的选项（[Value](type/value.md) 对象）。

### `textOption(String name, String initialValue)`
- 描述：创建一个文本类型的选项。
- 参数：
  - `name`（String）：选项的名称。
  - `initialValue`（String）：初始值。
- 返回值：
  - 文本类型的选项（[Value](type/value.md) 对象）。

### `modeOption(String name, String startMode, String... modes)`
- 描述：创建一个多选项类型的选项。
- 参数：
  - `name`（String）：选项的名称。
  - `startMode`（String）：初始模式。
  - `modes`（String 可变参数）：可选模式。
- 返回值：
  - 多选项类型的选项（[Value](type/value.md) 对象）。

### `sliderOption(String name, double defaultValue, double minValue, double maxValue, double increment)`
- 描述：创建一个滑动条类型的选项。
- 参数：
  - `name`（String）：选项的名称。
  - `defaultValue`（double）：默认值。
  - `minValue`（double）：最小值。
  - `maxValue`（double）：最大值。
  - `increment`（double）：增量。
- 返回值：
  - 滑动条类型的选项（[Value](type/value.md) 对象）。

### `colorOption(String name, int rgb, boolean canAlpha)`
- 描述：创建一个颜色类型的选项。
- 参数：
  - `name`（String）：选项的名称。
  - `rgb`（int）：RGB颜色值。
  - `canAlpha`（boolean）：是否允许调整透明度。
- 返回值：
  - 颜色类型的选项（[Value](type/value.md) 对象）。

### `wrapper()`
- 描述：返回一个包装了脚本模块的 `Module` 对象。
- 返回值：
  - 包装了脚本模块的 [Module](type/module.md) 对象。
