# player

`player.xxx`

`player` 用于处理与 Minecraft 玩家角色相关的各种操作和信息。

## 方法

### respawn()
- 重生

### swingItem()
- 摆动玩家手持物品。

### setPitch(float pitch)
- 设置玩家的俯仰角度（垂直视角）为指定值。
- 参数：
  - `pitch`：要设置的俯仰角度。

### setYaw(float yaw)
- 设置玩家的偏航角度（水平视角）为指定值。
- 参数：
  - `yaw`：要设置的偏航角度。

### setMotionX(double x)
- 设置玩家在X轴方向上的运动。
- 参数：
  - `x`：X轴方向上的运动。

### setMotionY(double y)
- 设置玩家在Y轴方向上的运动。
- 参数：
  - `y`：Y轴方向上的运动。

### setMotionZ(double z)
- 设置玩家在Z轴方向上的运动。
- 参数：
  - `z`：Z轴方向上的运动。

### setPosition(double x, double y, double z)
- 使用指定坐标设置玩家的位置。
- 参数：
  - `x`：X坐标。
  - `y`：Y坐标。
  - `z`：Z坐标。

### jump()
- 使玩家跳跃。

### setSneaking(boolean state)
- 设置玩家潜行状态。
- 参数：
  - `state`：`true` 启用潜行，`false` 禁用潜行。

### setSprinting(boolean state)
- 设置玩家奔跑状态。
- 参数：
  - `state`：`true` 启用奔跑，`false` 禁用奔跑。

### leftClick()
- 模拟鼠标左键单击。

### hasSword()
- 检查玩家是否在背包中拥有剑。
- 返回值：
  - 如果玩家有剑则返回 `true`，否则返回 `false`.

### rightClick()
- 模拟鼠标右键单击。

### setHeldItemSlot(int slot)
- 设置玩家手持物品的槽位。
- 参数：
  - `slot`：要设置的槽位。

### sendMessage(String msg)
- 以玩家身份发送聊天消息。
- 参数：
  - `msg`：要发送的消息。

### strafe(double speed)
- 控制玩家的横向移动。
- 参数：
  - `speed`：横向移动速度。

### collidedHorizontally()
- 检查玩家是否水平碰撞到物体。
- 返回值：
  - 如果玩家水平碰撞则返回 `true`，否则返回 `false`.

### collidedVertically()
- 检查玩家是否垂直碰撞到物体。
- 返回值：
  - 如果玩家垂直碰撞则返回 `true`，否则返回 `false`.

### collided()
- 检查玩家是否与物体碰撞。
- 返回值：
  - 如果玩家碰撞则返回 `true`，否则返回 `false`.

### moving()
- 检查玩家是否在移动。
- 返回值：
  - 如果玩家在移动则返回 `true`，否则返回 `false`.

### sneaking()
- 检查玩家是否在潜行状态。
- 返回值：
  - 如果玩家在潜行则返回 `true`，否则返回 `false`.

### sprinting()
- 检查玩家是否在奔跑状态。
- 返回值：
  - 如果玩家在奔跑则返回 `true`，否则返回 `false`.

### eating()
- 检查玩家是否在进食状态。
- 返回值：
  - 如果玩家在进食则返回 `true`，否则返回 `false`.

### onGround()
- 检查玩家是否站在地面上。
- 返回值：
  - 如果玩家在地面上则返回 `true`，否则返回 `false`.

### airBorne()
- 检查玩家是否在空中。
- 返回值：
  - 如果玩家在空中则返回 `true`，否则返回 `false`.

### onLadder()
- 检查玩家是否在梯子上。
- 返回值：
  - 如果玩家在梯子上则返回 `true`，否则返回 `false`.

### inWater()
- 检查玩家是否在水中。
- 返回值：
  - 如果玩家在水中则返回 `true`，否则返回 `false`.

### inLava()
- 检查玩家是否在岩浆中。
- 返回值：
  - 如果玩家在岩浆中则返回 `true`，否则返回 `false`.

### usingItem()
- 检查玩家是否正在使用物品。
- 返回值：
  - 如果玩家正在使用物品则返回 `true`，否则返回 `false`.

### burning()
- 检查玩家是否燃烧状态。
- 返回值：
  - 如果玩家正在燃烧则返回 `true`，否则返回 `false`.

### dead()
- 检查玩家是否死亡。
- 返回值：
  - 如果玩家已死亡则返回 `true`，否则返回 `false`.

### isPotionActive(int potionId)
- 检查玩家是否激活特定药水效果。
- 参数：
  - `potionId`：要检查的药水效果的ID。
- 返回值：
  - 如果玩家激活了指定的药水效果则返回 `true`，否则返回 `false`.

### name()
- 获取玩家的名称。
- 返回值：
  - 玩家的名称。

### hurtTime()
- 获取玩家受伤时的时间。
- 返回值：
  - 受伤时间。

### heldItemSlot()
- 获取玩家当前手持物品的槽位。
- 返回值：
  - 当前手持物品的槽位.

### ticksExisted()
- 获取玩家已存在的刻数。
- 返回值：
  - 已存在的刻数.

### fallDistance()
- 获取玩家的下落距离.
- 返回值:
  - 下落距离.

### health()
- 获取玩家的生命值.
- 返回值:
  - 生命值.

### maxHealth()
- 获取玩家的最大生命值.
- 返回值:
  - 最大生命值.

### armorValue()
- 获取玩家的总护甲值.
- 返回值:
  - 总护甲值.

### hunger()
- 获取玩家的饥饿值.
- 返回值:
  - 饥饿值.

### absorption()
- 获取玩家的吸收量.
- 返回值:
  - 吸收量.

### pitch()
- 获取玩家的俯仰角度.
- 返回值:
  - 俯仰角度.

### yaw()
- 获取玩家的偏航角度.
- 返回值:
  - 偏航角度.

### x()
- 获取玩家的X坐标.
- 返回值:
  - X坐标.

### y()
- 获取玩家的Y坐标.
- 返回值:
  - Y坐标.

### z()
- 获取玩家的Z坐标.
- 返回值:
  - Z坐标.

### prevX()
- 获取玩家的上一个X坐标.
- 返回值:
  - 上一个X坐标.

### prevY()
- 获取玩家的上一个Y坐标.
- 返回值:
  - 上一个Y坐标.

### prevZ()
- 获取玩家的上一个Z坐标.
- 返回值:
  - 上一个Z坐标.

### motionX()
- 获取玩家在X轴方向上的运动速度.
- 返回值:
  - X轴方向上的运动速度.

### motionY()
- 获取玩家在Y轴方向上的运动速度.
- 返回值:
  - Y轴方向上的运动速度.

### motionZ()
- 获取玩家在Z轴方向上的运动速度.
- 返回值:
  - Z轴方向上的运动速度.

### timerSpeed()
- 获取计时器速度.
- 返回值:
  - 计时器速度.

### getBaseMoveSpeed()
- 获取玩家的基础移动速度.
- 返回值:
  - 基础移动速度.

### getInventorySlot(int slot)
- 获取玩家背包中指定槽位的物品.
- 参数:
  - `slot`: 要获取的槽位.
- 返回值:
  - 物品的包装对象.

### getServerIP()
- 获取当前服务器的IP地址.
- 返回值:
  - 当前服务器的IP地址.

### sendUseItem([ItemStack](../type/itemstack.md) itemStack)
- 发送使用物品的请求.
- 参数:
  - `itemStack`: 要使用的物品的包装对象.

### stopUseItem()
- 停止使用物品.

### getDistance([Entity](../type/entity.md) entity)
- 获取与指定实体之间的距离.
- 参数:
  - `entity`: 目标实体的包装对象.
- 返回值:
  - 与目标实体的距离.

### ()
- 获取玩家的包装对象.
- 返回值:
  - 玩家的包装对象.

### sendPacket(int integer, Object... args)
- 发送网络数据包.
- 参数:
  - `integer`: 数据包类型。
  - `args`: 数据包参数。



#### 注意

`sendPacket` 方法的参数取决于不同的情况，根据传入的 `integer` 参数，可能会有不同的参数。以下是 `sendPacket` 方法的各个情况和可能的参数列表：

1. `integer` 为 `0x0A` 时，对应 `C0APacketAnimation` 数据包，无需额外参数。

2. `integer` 为 `0x0B` 时，对应 `C0BPacketEntityAction` 数据包，需要以下参数：
   - `args[0]`：整数，代表 `C0BPacketEntityAction$Action` 的 ID。

3. `integer` 为 `0x0C` 时，对应 `C0CPacketInput` 数据包，需要以下参数：
   - `args[0]`：浮点数，X轴旋转。
   - `args[1]`：浮点数，Y轴旋转。
   - `args[2]`：布尔值，是否执行跳跃操作。
   - `args[3]`：布尔值，是否执行旁观操作。

4. `integer` 为 `0x0D` 时，对应 `C0DPacketCloseWindow` 数据包，需要以下参数：
   - `args[0]`：整数，窗口 ID。

5. `integer` 为 `0x0F` 时，对应 `C0FPacketConfirmTransaction` 数据包，需要以下参数：
   - `args[0]`：整数，窗口 ID。
   - `args[1]`：短整数，动作 ID。
   - `args[2]`：布尔值，是否确认事务。

6. `integer` 为 `0x00` 时，对应 `C00PacketKeepAlive` 数据包，需要以下参数：
   - `args[0]`：整数，用于保持连接的随机 ID。

7. `integer` 为 `0x02` 时，对应 `C02PacketUseEntity` 数据包，需要以下参数：
   - `args[0]`：`Entity` 包装的目标实体。
   - `args[1]`：整数，对应 `C02PacketUseEntity$Action` 的 ID。

8. `integer` 为 `0x03` 时，对应 `C03PacketPlayer` 数据包，需要以下参数：
   - `args[0]`：布尔值，是否在地上。

9. `integer` 为 `0x04` 时，对应 `C03PacketPlayer$C04PacketPlayerPosition` 数据包，需要以下参数：
   - `args[0]`：浮点数，X坐标。
   - `args[1]`：浮点数，Y坐标。
   - `args[2]`：浮点数，Z坐标。
   - `args[3]`：布尔值，是否在地上。

10. `integer` 为 `0x05` 时，对应 `C03PacketPlayer$C05PacketPlayerLook` 数据包，需要以下参数：
    - `args[0]`：浮点数，俯仰角度。
    - `args[1]`：浮点数，偏航角度。
    - `args[2]`：布尔值，是否在地上。

11. `integer` 为 `0x06` 时，对应 `C03PacketPlayer$C06PacketPlayerPosLook` 数据包，需要以下参数：
    - `args[0]`：浮点数，X坐标。
    - `args[1]`：浮点数，Y坐标。
    - `args[2]`：浮点数，Z坐标。
    - `args[3]`：浮点数，俯仰角度。
    - `args[4]`：浮点数，偏航角度。
    - `args[5]`：布尔值，是否在地上。

12. `integer` 为 `0x07` 时，对应 `C07PacketPlayerDigging` 数据包，需要以下参数：
    - `args[0]`：整数，对应 `C07PacketPlayerDigging$Action` 的 ID。
    - `args[1]`：浮点数，X坐标。
    - `args[2]`：浮点数，Y坐标。
    - `args[3]`：浮点数，Z坐标。
    - `args[4]`：整数，方向的索引。

13. `integer` 为 `0x08` 时，对应 `C08PacketPlayerBlockPlacement` 数据包，需要以下参数：
    - `args[0]`：浮点数，X坐标。
    - `args[1]`：浮点数，Y坐标。
    - `args[2]`：浮点数，Z坐标。
    - `args[3]`：整数，方块槽位 ID。
    - `args[4]`：[ItemStack](../type/itemstack.md)。
    - `args[5]`：浮点数，X坐标。
    - `args[6]`：浮点数，Y坐标。
    - `args[7]`：浮点数，Z坐标。

14. `integer` 为 `0x09` 时，对应 `C09PacketHeldItemChange` 数据包，需要以下参数：
    - `args[0]`：整数，槽位 ID。

15. `integer` 为 `0x16` 时，对应 `C16PacketClientStatus` 数据包，需要以下参数：
    - `args[0]`：整数，对应 `C16PacketClientStatus$EnumState` 的 ID。

16. `integer` 为 `0x18` 时，对应 `C18PacketSpectate` 数据包，需要以下参数：
    - `args[0]`：UUID，目标实体的 UUID。

请根据具体情况选择正确的 `integer` 值和相应的参数。