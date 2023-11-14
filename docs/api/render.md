# render

`render.xxx`

`render` 包含了用于渲染的各种方法。以下是该类的方法及其说明：

## drawBoundingBox(Entity target, int color, int alpha)
- 绘制实体边界框。
- 参数：
  - `target`：目标实体的包装对象。
  - `color`：边界框颜色。
  - `alpha`：边界框透明度。

## reAlpha(Color color, int alpha)
- 更改颜色的透明度。
- 参数：
  - `color`：原始颜色。
  - `alpha`：新的透明度。
- 返回值：
  - 修改后的颜色。

## interpolateColors(Color color1, Color color2, float percent)
- 在两种颜色之间进行插值。
- 参数：
  - `color1`：第一种颜色。
  - `color2`：第二种颜色。
  - `percent`：插值比例（0.0 到 1.0）。
- 返回值：
  - 插值后的颜色。

## drawRect(float x, float y, float width, float height, Color color)
- 绘制矩形。
- 参数：
  - `x`：矩形左上角的X坐标。
  - `y`：矩形左上角的Y坐标。
  - `width`：矩形的宽度。
  - `height`：矩形的高度。
  - `color`：矩形的颜色。

## drawCircle(double x, double y, float radius, int color)
- 绘制圆形。
- 参数：
  - `x`：圆心的X坐标。
  - `y`：圆心的Y坐标。
  - `radius`：圆的半径。
  - `color`：圆的颜色。

## renderItem(int itemSlot, int x, int y)
- 渲染物品图标。
- 参数：
  - `itemSlot`：物品所在槽位的索引。
  - `x`：渲染位置的X坐标。
  - `y`：渲染位置的Y坐标。

## getRGB(int r, int g, int b)
- 获取RGB颜色。
- 参数：
  - `r`：红色分量。
  - `g`：绿色分量。
  - `b`：蓝色分量。
- 返回值：
  - 对应的RGB颜色。

## getRGBA(int r, int g, int b, int a)
- 获取RGBA颜色。
- 参数：
  - `r`：红色分量。
  - `g`：绿色分量。
  - `b`：蓝色分量。
  - `a`：透明度。
- 返回值：
  - 对应的RGBA颜色。

## drawRect0(float x, float y, float x1, float y1, Color color)
- 绘制矩形。
- 参数：
  - `x`：矩形左上角的X坐标。
  - `y`：矩形左上角的Y坐标。
  - `x1`：矩形右下角的X坐标。
  - `y1`：矩形右下角的Y坐标。
  - `color`：矩形的颜色。

## resetColor()
- 重置颜色。

## HSBtoRGB(float hue, float saturation, float brightness)
- 将HSB颜色转换为RGB颜色。
- 参数：
  - `hue`：色调。
  - `saturation`：饱和度。
  - `brightness`：亮度。
- 返回值：
  - 对应的RGB颜色。

## startGlScissor(int x, int y, int width, int height)
- 启用OpenGL裁剪。
- 参数：
  - `x`：裁剪区域的左上角X坐标。
  - `y`：裁剪区域的左上角Y坐标。
  - `width`：裁剪区域的宽度。
  - `height`：裁剪区域的高度。

## stopGlScissor()
- 停用OpenGL裁剪。

## drawImage(String image, int x, int y, int width, int height)
- 绘制图像。
- 参数：
  - `image`：图像文件的路径。
  - `x`：图像左上角的X坐标。
  - `y`：图像左上角的Y坐标。
  - `width`：图像的宽度。
  - `height`：图像的高度。

## getAnimationState(double animation, double finalState, double speed)
- 获取动画状态。
- 参数：
  - `animation`：当前动画状态。
  - `finalState`：最终动画状态。
  - `speed`：动画速度。
- 返回值：
  - 更新后的动画状态。

## getAnimationStateEasing(double animation, double finalState, double speed)
- 获取使用缓动函数的动画状态。
- 参数：
  - `animation`：当前动画状态。
  - `finalState`：最终动画状态。
  - `speed`：动画速度。
- 返回值：
  - 更新后的动画状态。

## easing(double now, double target, double speed)
- 使用缓动函数进行插值计算。
- 参数：
  - `now`：当前值。
  - `target`：目标值。
  - `speed`：插值速度。
- 返回值：
  - 插值后的值。

## defineMask()
- 定义遮罩。

## finishDefineMask()
- 完成遮罩定义。

## drawOnMask()
- 绘制在遮罩上。

## resetMask()
- 重置遮罩。

## getPartialTicks()
- 获取渲染部分的时间。

## drawEntity3D(int posX, int posY, int scale, float mouseX, float mouseY, EntityLivingBase ent)
- 在3D空间中绘制实体。
- 参数：
  - `posX`：X坐标。
  - `posY`：Y坐标。
  - `scale`：缩放比例。
  - `mouseX`：鼠标X坐标。
  - `mouseY`：鼠标Y坐标。
  - `ent`：实体对象。

## drawEntity2D(int x, int y, int width, int height, EntityLivingBase player)
- 在2D空间中绘制实体。
- 参数：
  - `x`：X坐标。
  - `y`：Y坐标。
  - `width`：宽度。
  - `height`：高度。
  - `player`：实体对象。

## getScaledWidth()
- 获取缩放后的宽度。

## getScaledHeight()
- 获取缩放后的高度。