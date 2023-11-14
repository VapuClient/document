## entity

### 方法

#### getName(): String
获取实体的名称。

- 返回值: 实体的名称 (类型: `String`)。

#### getHealth(): float
获取实体的当前生命值。

- 返回值: 实体的当前生命值 (类型: `float`)。

#### getMaxHealth(): float
获取实体的最大生命值。

- 返回值: 实体的最大生命值 (类型: `float`)。

#### getPosX(): double
获取实体的 X 坐标位置。

- 返回值: 实体的 X 坐标位置 (类型: `double`)。

#### getPosY(): double
获取实体的 Y 坐标位置。

- 返回值: 实体的 Y 坐标位置 (类型: `double`)。

#### getPosZ(): double
获取实体的 Z 坐标位置。

- 返回值: 实体的 Z 坐标位置 (类型: `double`)。

#### getMotionX(): double
获取实体的 X 轴速度。

- 返回值: 实体的 X 轴速度 (类型: `double`)。

#### getMotionY(): double
获取实体的 Y 轴速度。

- 返回值: 实体的 Y 轴速度 (类型: `double`)。

#### getMotionZ(): double
获取实体的 Z 轴速度。

- 返回值: 实体的 Z 轴速度 (类型: `double`)。

#### isOnGround(): boolean
检查实体是否在地面上。

- 返回值: 如果实体在地面上，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isCollidedHorizontally(): boolean
检查实体是否水平碰撞。

- 返回值: 如果实体水平碰撞，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isCollidedVertically(): boolean
检查实体是否垂直碰撞。

- 返回值: 如果实体垂直碰撞，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isOnLadder(): boolean
检查实体是否在梯子上。

- 返回值: 如果实体在梯子上，则为 `true`；否则为 `false` (类型: `boolean`)。

#### getTotalArmorValue(): int
获取实体的总护甲值。

- 返回值: 实体的总护甲值 (类型: `int`)。

#### getHeldItem(): ItemStack
获取实体手持的物品栏中的物品。

- 返回值: `ItemStack` 对象，表示实体手持的物品。

#### getHurtTime(): int
获取实体的受伤时间。

- 返回值: 实体的受伤时间 (类型: `int`)。

#### getYaw(): float
获取实体的水平旋转角度（偏航角）。

- 返回值: 实体的水平旋转角度 (类型: `float`)。

#### getPitch(): float
获取实体的俯仰角。

- 返回值: 实体的俯仰角 (类型: `float`)。

#### isPlayer(): boolean
检查实体是否为玩家。

- 返回值: 如果实体是玩家，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isMob(): boolean
检查实体是否为生物怪物。

- 返回值: 如果实体是生物怪物，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isAnimal(): boolean
检查实体是否为动物。

- 返回值: 如果实体是动物，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isAlive(): boolean
检查实体是否仍然存活。

- 返回值: 如果实体仍然存活，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isInvisible(): boolean
检查实体是否不可见。

- 返回值: 如果实体不可见，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isBot(): boolean
检查实体是否为机器人。

- 返回值: 如果实体是机器人，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isTeam(): boolean
检查实体是否与同一队伍。

- 返回值: 如果实体与同一队伍，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isSelf(): boolean
检查实体是否为自己。

- 返回值: 如果实体是自己，则为 `true`；否则为 `false` (类型: `boolean`)。

#### isNull(): boolean
检查实体是否为空（不存在）。

- 返回值: 如果实体为空，则为 `true`；否则为 `false` (类型: `boolean`)。

#### clearValue()
清除实体的值，将其设置为 `null`。
