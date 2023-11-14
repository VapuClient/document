# world

`world.xxx`

`world` 提供了与游戏世界（World）相关的操作方法。

## 方法

### setTimer(float speed)
- 设置游戏计时器的速度。
- 参数：
  - `speed`：计时器速度。

### isSinglePlayer()
- 检查是否为单人游戏。
- 返回值：
  - 如果是单人游戏，返回 `true`；否则返回 `false`。

### getTimer()
- 获取游戏计时器的速度。
- 返回值：
  - 游戏计时器的速度。

### removeEntity(Entity entity)
- 从游戏世界中移除指定的实体。
- 参数：
  - `entity`：要移除的实体的包装对象。

### getLivingEntities()
- 获取所有存活的实体。
- 返回值：
  - 包含所有存活实体的 `Entity` 对象列表。
