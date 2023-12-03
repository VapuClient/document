# client

`client.xxx`

提供与客户端功能相关的操作方法。

## 方法

### 获取版本信息

#### getVersion()
获取客户端的版本信息。

- 返回值: 一个包含版本信息的字符串。

### 创建计时器

#### newTimer()
创建一个新的计时器对象。

- 返回值: 包含新计时器对象的 [Timer](../type/timer.md)。

### 创建旋转

#### newRotation()
创建一个新的旋转对象。

- 返回值: 包含新旋转对象的 [Rotation](../type/rotation.md)。

### 创建空数组

#### newArray()
创建一个新的空数组。

- 返回值: 包含新数组的 `ArrayList`。

### 获取模块列表

#### getModulesByCategory(category: [Category](../type/category.md), scriptOnly: boolean)
根据指定的类别获取模块列表。

- 参数:
  - `category` - 类别对象。
  - `scriptOnly` - 是否仅获取脚本模块。

- 返回值: 一个包含模块对象的 `ArrayList`。

### 获取所有模块

#### getModules()
获取所有模块的列表。

- 返回值: 一个包含模块对象的 `ArrayList`。

### 获取当前时间

#### currentTimeMillis()
获取当前时间的毫秒数。

- 返回值: 当前时间的毫秒数。

### 获取屏幕分辨率

#### getScaledResolution()
获取当前屏幕的分辨率。

- 返回值: 包含分辨率信息的 [ScaledResolution](../type/ScaledResolution.md) 对象。

### 发送聊天消息

#### sendMessage(text: String)
向聊天窗口发送一条消息。

- 参数:
  - `text` - 要发送的消息内容。

### 获取FPS

#### getFPS()
获取当前的帧每秒（FPS）。

- 返回值: 当前的FPS数。

### 检查是否为null屏幕

#### isNullScreen()
检查当前屏幕是否为null。

- 返回值: 如果当前屏幕为null，则返回 `true`，否则返回 `false`。

### 检查是否为null的物体鼠标悬停

#### isNullObjectMouseOver()
检查鼠标悬停的物体是否为null。

- 返回值: 如果鼠标悬停的物体为null，则返回 `true`，否则返回 `false`。

### 创建GUI屏幕

#### createGuiScreen()
创建一个新的GUI屏幕。

- 返回值: 包含新GUI屏幕的 [GuiScreen](../type/GuiScreen.md) 对象。

### 显示GUI屏幕

#### displayGuiScreen(guiScreen: [GuiScreen](../type/GuiScreen.md))
在游戏中显示指定的GUI屏幕。

- 参数:
  - `guiScreen` - 要显示的GUI屏幕对象。

### 设置按键状态

#### setKeyBindState(key: int, status: boolean)
设置指定按键的状态。

- 参数:
  - `key` - 要设置状态的按键的键值。
  - `status` - 按键的状态，`true` 表示按下，`false` 表示释放。

### 获取模块类别列表

#### getCategories()
获取所有模块类别的列表。

- 返回值: 包含模块类别对象的 `ArrayList`。

### 获取实体的旋转

#### getRotations(ent: [Entity](../type/entity.md))
获取指定实体的旋转信息。

- 参数:
  - `ent` - 要获取旋转信息的实体对象。

- 返回值: 包含实体旋转信息的浮点数组。

### 检查鼠标左键是否按下

#### leftMouseButtonDown()
检查鼠标左键是否按下。

- 返回值: 如果左键按下，则返回 `true`，否则返回 `false`。

### 检查鼠标右键是否按下

#### rightMouseButtonDown()
检查鼠标右键是否按下。

- 返回值: 如果右键按下，则返回 `true`，否则返回 `false`。

### 检查按键是否按下

#### isKeyDown(key: int)
检查指定按键是否按下。

- 参数:
  - `key` - 要检查的按键的键值。

- 返回值: 如果按键按下，则返回 `true`，否则返回 `false`。

#### getTarget()
返回LegitAura目标

- 返回值: 返回Entity，如果没有目标则返回null

### 获取指定模块

#### getModule(moduleName: String)
获取指定名称的模块。

- 参数:
  - `moduleName` - 要获取的模块的名称。

- 返回值: 包含指定模块的 `Module` 对象。
