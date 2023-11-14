# GuiScreen

示例自定义Gui Screen代码

```javascript

var script = newModule({
	name: "GUI",
	category: "Visual",
	description: "A Simple gui"
})

var instance = client.createGuiScreen();


script.onEnable(function() {
	script.wrapper().setState(false);
	client.displayGuiScreen(instance);
})

script.drawScreen(function(mouseX, mouseY, partialTicks) {
    // render gui
})
```

事件请查看[Gui Events](../event/guiEvents.md)