## notification

`notification.xxx`

`notification` 提供了与通知消息相关的功能，包括发送不同类型的通知消息。以下是该类中的方法和属性的文档：

### 属性

#### INFO
- 类型: `NotificationType`
- 描述: 表示通知消息类型为信息（INFO）的属性。

#### WARNING
- 类型: `NotificationType`
- 描述: 表示通知消息类型为警告（WARNING）的属性。

#### ALERT
- 类型: `NotificationType`
- 描述: 表示通知消息类型为警报（ALERT）的属性。

### 方法

#### post(notificationType: NotificationType, title: String, info: String)
发布通知消息。

- 参数:
  - `notificationType` (类型: `NotificationType`) - 通知消息类型，可以使用 `INFO`、`WARNING` 或 `ALERT` 属性。
  - `title` (类型: `String`) - 通知消息的标题。
  - `info` (类型: `String`) - 通知消息的详细信息。

#### post(notificationType: NotificationType, title: String, info: String, time: long)
发布具有自定义显示时间的通知消息。

- 参数:
  - `notificationType` (类型: `NotificationType`) - 通知消息类型，可以使用 `INFO`、`WARNING` 或 `ALERT` 属性。
  - `title` (类型: `String`) - 通知消息的标题。
  - `info` (类型: `String`) - 通知消息的详细信息。
  - `time` (类型: `long`) - 通知消息的自定义显示时间（以毫秒为单位）。
