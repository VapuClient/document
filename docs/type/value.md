# Value

`Value` 类用于包装各种类型的值对象。

## 方法

### `getValue()`

获取包装的值对象的值。

- 返回值：
  - 包装的值对象的值。

### `getName()`

获取值对象的名称。

- 返回值：
  - 值对象的名称。

### `setValueString(String string)`

根据输入的字符串设置值对象的值。

- 参数：
  - `string`（String）：要设置的字符串值。

### `isCombo()`

检查值对象是否是 ComboValue 类型。

- 返回值：
  - 如果值对象是 ComboValue 类型，返回 `true`；否则返回 `false`。

### `isBool()`

检查值对象是否是 BooleanValue 类型。

- 返回值：
  - 如果值对象是 BooleanValue 类型，返回 `true`；否则返回 `false`。

### `isNumber()`

检查值对象是否是 NumberValue 类型。

- 返回值：
  - 如果值对象是 NumberValue 类型，返回 `true`；否则返回 `false`。

### `isColor()`

检查值对象是否是 ColorValue 类型。

- 返回值：
  - 如果值对象是 ColorValue 类型，返回 `true`；否则返回 `false`。

### `isText()`

检查值对象是否是 TextValue 类型。

- 返回值：
  - 如果值对象是 TextValue 类型，返回 `true`；否则返回 `false`。

### `getModes()`

获取 ComboValue 值对象的可选模式。

- 返回值：
  - ComboValue 值对象的可选模式数组。

### `isMode(String mode)`

检查 ComboValue 值对象是否处于特定模式。

- 参数：
  - `mode`（String）：要检查的模式名称。
- 返回值：
  - 如果值对象是 ComboValue 且处于指定模式，返回 `true`；否则返回 `false`。

### `getString()`

获取值对象的值作为字符串。

- 返回值：
  - 值对象的值作为字符串。

### `getAsInt()`

获取值对象的值作为整数。

- 返回值：
  - 值对象的值作为整数。

### `setValueInt(int i)`

根据整数值设置 NumberValue 值对象的值。

- 参数：
  - `i`（int）：要设置的整数值。

### `setValueDouble(double i)`

根据双精度浮点数值设置 NumberValue 值对象的值。

- 参数：
  - `i`（double）：要设置的双精度浮点数值。

### `setValueHue(float i)`

设置 ColorValue 值对象的色调。

- 参数：
  - `i`（float）：要设置的色调值。

### `setValueBrightness(float i)`

设置 ColorValue 值对象的亮度。

- 参数：
  - `i`（float）：要设置的亮度值。

### `setValueSaturation(float i)`

设置 ColorValue 值对象的饱和度。

- 参数：
  - `i`（float）：要设置的饱和度值。

### `getHue()`

获取 ColorValue 值对象的色调。

- 返回值：
  - ColorValue 值对象的色调值。

### `getBrightness()`

获取 ColorValue 值对象的亮度。

- 返回值：
  - ColorValue 值对象的亮度值。

### `getSaturation()`

获取 ColorValue 值对象的饱和度。

- 返回值：
  - ColorValue 值对象的饱和度值。

### `getMax()`

获取 NumberValue 值对象的最大值。

- 返回值：
  - NumberValue 值对象的最大值。

### `getMin()`

获取 NumberValue 值对象的最小值。

- 返回值：
  - NumberValue 值对象的最小值。

### `getIncrement()`

获取 NumberValue 值对象的增量值。

- 返回值：
  - NumberValue 值对象的增量值。

### `getRGB()`

获取 ColorValue 值对象的RGB值。

- 返回值：
  - ColorValue 值对象的RGB值。

### `setValueRGB(int rgb)`

根据RGB值设置 ColorValue 值对象的值。

- 参数：
  - `rgb`（int）：要设置的RGB值。

### `getBool()`

获取 BooleanValue 值对象的布尔值。

- 返回值：
  - BooleanValue 值对象的布尔值。

### `setValueBool(boolean i)`

根据布尔值设置 BooleanValue 值对象的值。

- 参数：
  - `i`（boolean）：要设置的布尔值。

### `getAsDouble()`

获取值对象的值作为双精度浮点数。

- 返回值：
  - 值对象的值作为双精度浮点数。

### `getAsFloat()`

获取值对象的值作为浮点数。

- 返回值：
  - 值对象的值作为浮点数。
