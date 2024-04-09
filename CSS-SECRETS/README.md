# CSS 揭秘

## 背景和边框
- [透明边框](./background-border/translucent-borders.html)：默认情况下，背景会延伸到边框所在的区域下面，可以通过 **background-clip** 属性来调整默认行为。
- [多重边框](./background-border/multiple-borders.html)：使用 **box-shadow** 来模拟外框，模拟的边框出现在在外圈，并不会响应鼠标事件，可以给 **box-shadow** 属性加上 **inset** 关键字，来使投影绘制在元素的内圈。
- [灵活的背景定位](./background-border/extended-bg-position.html)：**background-position** 允许指定背景图片距离任意角的偏移量，只要在偏移量前面指定关键词。
- [灵活的背景定位](./background-border/background-origin.html)：默认情况下，**background-position** 是以 **padding-box** 为准的，可以使用 **background-origin** 来改变该基准。
- [灵活的背景定位](./background-border/background-position-calc.html)：使用calc()函数计算偏移值进行背景定位。
- [边框内圆角](./background-border/inner-rounding.html)：利用描边 **outline**不跟着圆角走的事实，配合 **box-shadow** 实现边框内圆角。
- [条纹背景-水平条纹](./background-border/horizontal-stripes.html)：使用线性渐变 **linear-gradient** 将两个色标重合可以创建实色条纹。如果某个色标的位置值比整个列表中在它之前的色标值都要小，则该色标的位置值会被设置成它前面所有色标位置的最大值。这意味着，如果把第二个色标的位置设置为0，那它的位置就总是被浏览器调整为前一个色标的位置值。