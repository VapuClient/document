## rotation

### 属性

#### `getYaw(): float`
获取当前偏航角。

- 返回值: 当前偏航角 (类型: `float`)。

#### `getPitch(): float`
获取当前俯仰角。

- 返回值: 当前俯仰角 (类型: `float`)。

### 方法

#### `setYaw(yaw: float): rotation`
设置偏航角。

- 参数:
  - `yaw` (类型: `float`) - 要设置的偏航角。

- 返回值: 更新后的 `rotation` 对象。

#### `setPitch(pitch: float): rotation`
设置俯仰角。

- 参数:
  - `pitch` (类型: `float`) - 要设置的俯仰角。

- 返回值: 更新后的 `rotation` 对象。

#### `setYawPitch(yaw: float, pitch: float): rotation`
同时设置偏航角和俯仰角。

- 参数:
  - `yaw` (类型: `float`) - 要设置的偏航角。
  - `pitch` (类型: `float`) - 要设置的俯仰角。

- 返回值: 更新后的 `rotation` 对象。

#### `rotationWithSpeed(targetYaw: float, targetPitch: float, speed: double): rotation`
根据速度以平滑的方式旋转到指定的偏航角和俯仰角。

- 参数:
  - `targetYaw` (类型: `float`) - 目标偏航角。
  - `targetPitch` (类型: `float`) - 目标俯仰角。
  - `speed` (类型: `double`) - 旋转速度。

- 返回值: 更新后的 `rotation` 对象。

#### `rotationWithSpeedOnlyYaw(targetYaw: float, speed: double): rotation`
根据速度以平滑的方式旋转到指定的偏航角，不修改俯仰角。

- 参数:
  - `targetYaw` (类型: `float`) - 目标偏航角。
  - `speed` (类型: `double`) - 旋转速度。

- 返回值: 更新后的 `rotation` 对象。

#### `rotationWithSpeedOnlyPitch(targetPitch: float, speed: double): rotation`
根据速度以平滑的方式旋转到指定的俯仰角，不修改偏航角。

- 参数:
  - `targetPitch` (类型: `float`) - 目标俯仰角。
  - `speed` (类型: `double`) - 旋转速度。

- 返回值: 更新后的 `rotation` 对象。

#### `setEntityRotation(entity: Entity): void`
将当前偏航角和俯仰角应用到指定实体对象上，更新实体的旋转角度。

- 参数:
  - `entity` (类型: `Entity`) - 要应用旋转角度的实体对象。

#### `setPlayerRotation(e: MotionEventWrapper): void`
将当前偏航角和俯仰角应用到玩家角色的事件对象上，更新玩家角色的旋转角度。

- 参数:
  - `e` (类型: `MotionEventWrapper`) - 事件对象。

#### `toString(): String`
返回表示 `rotation` 对象的字符串，包括当前的偏航角和俯仰角。

- 返回值: 表示对象的字符串 (类型: `String`)。

#### `getAngleDifference(a: float, b: float): float`
计算两个角度之间的差值，确保结果在 -180 到 180 度之间。

- 参数:
  - `a` (类型: `float`) - 第一个角度。
  - `b` (类型: `float`) - 第二个角度。

- 返回值: 角度差值 (类型: `float`)。
