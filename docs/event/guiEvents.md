# Gui Event

## `drawScreen(int mouseX, int mouseY)`

当屏幕需要渲染时，此方法被调用。它接受鼠标的X和Y坐标作为参数，以便根据鼠标位置进行渲染。如果已注册 "drawScreen" 事件处理函数，则调用它。

## `mouseMovedOrUp(int mouseX, int mouseY, int button)`

这个方法用于处理鼠标移动或释放鼠标按键事件。它接受鼠标的X和Y坐标以及按钮编号作为参数。如果已注册 "mouseReleased" 事件处理函数，则调用它。

## `keyTyped(char typedChar, int keyCode)`

当键盘输入事件发生时，此方法被调用。它接受输入的字符和键码作为参数。如果已注册 "keyTyped" 事件处理函数，则调用它。

## `mouseClicked(int mouseX, int mouseY, int mouseButton)`

当用户点击鼠标时，此方法被调用。它接受鼠标的X和Y坐标以及鼠标按钮编号作为参数。如果已注册 "mouseClicked" 事件处理函数，则调用它。

## `initGui()`

此方法在初始化用户界面时被调用。如果已注册 "initGui" 事件处理函数，则调用它。

## `onGuiClosed()`

当用户界面关闭时，此方法被调用。如果已注册 "onGuiClosed" 事件处理函数，则调用它。