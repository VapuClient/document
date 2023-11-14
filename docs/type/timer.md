# Timer

这个类用于计时和时间间隔相关的操作。

## 属性

### `lastMS`
- 类型：long
- 描述：最后一次记录的时间戳。

## 方法

### `hasTimeElapsed(long time)`
- 描述：检查是否已经经过了指定的时间间隔。
- 参数：
  - `time`（long）：要检查的时间间隔（以毫秒为单位）。
- 返回值：
  - 如果已经经过了指定时间间隔，返回 `true`；否则返回 `false`。

### `hasTimeElapsed(long time, boolean reset)`
- 描述：检查是否已经经过了指定的时间间隔，并在满足条件时重置计时。
- 参数：
  - `time`（long）：要检查的时间间隔（以毫秒为单位）。
  - `reset`（boolean）：是否在满足条件时重置计时。
- 返回值：
  - 如果已经经过了指定时间间隔，且满足条件时重置了计时，返回 `true`；否则返回 `false`。

### `getElapsedTime()`
- 描述：获取自上次计时以来经过的时间。
- 返回值：
  - 经过的时间（以毫秒为单位）。

### `reset()`
- 描述：重置计时，将 `lastMS` 设置为当前时间。

### `reset(long time)`
- 描述：将计时重置为指定时间。
- 参数：
  - `time`（long）：要设置的时间。

### `setLastMS(long lastMS)`
- 描述：设置 `lastMS` 的值为指定时间。
- 参数：
  - `lastMS`（long）：要设置的时间。
