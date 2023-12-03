# Module Events

## enable

module.onEnable();

## disable

module.onDisable();

## render

module.onRender2D(float renderPartialTicks);

在进行2D渲染时调用此方法。 `renderPartialTicks` 参数表示渲染的时间部分，通常用于平滑动画和渲染效果。

### onKey

module.onKey(int keyCode);

当用户按下键盘上的键时，此方法会被调用。`keyCode` 参数表示按下的键的键码。

### onRender3D

module.onRender3D(float renderPartialTicks);

在进行3D渲染时调用此方法。 `renderPartialTicks` 参数表示渲染的时间部分，通常用于平滑动画和渲染效果。

### onMotion

module.onMotion(MotionUpdateEvent event);

当运动事件发生时，此方法会被调用。 `event` 参数是 `MotionUpdateEvent` 类型的事件对象，包含有关运动的信息。

### onTick

module.onTick();

在每个刻事件（tick）时，此方法会被调用。通常用于处理周期性任务或事件。

### onPacketSend

module.onPacketSend(PacketEvent event);

当数据包发送事件发生时，此方法会被调用。 `event` 参数是 `PacketEvent` 类型的事件对象，包含有关数据包发送的信息。

### onPacketReceive

module.onPacketReceive(PacketEvent event);

当数据包接收事件发生时，此方法会被调用。 `event` 参数是 `PacketEvent` 类型的事件对象，包含有关数据包接收的信息。

### onStrafe

module.onStrafe(StrafeEvent event);

当运动事件发生时，此方法会被调用。 `event` 参数是 `StrafeEvent` 类型的事件对象，包含有关运动方向的信息。
