## 006-Background

`1、background-color="设置元素的背景颜色"`

- `1. transparent="背景颜色为透明 默认"`

`2、 background-image="设置元素的背景图像"`

- `1. URL`

  `2. background-image: linear-gradient(方向, 起始颜色, 终止颜色)="线性渐变"`

  `3. background-image: radial-gradient(辐射的半径大小, 中心的位置, 起始颜色, 终止颜色)="径向渐变"`

`3、background-repeat="设置是否及如何重复背景图像"`

- `1. repeat="背景图像将在垂直方向和水平方向重复 默认"`

  `2. repeat-x="背景图像将在水平方向重复"`

  `3. repeat-y="背景图像将在垂直方向重复"`

  `4. no-repeat="背景图像将仅显示一次"`

`4、background-position="设置背景图像的开始位置"`

`5、background-attachment="背景图像是否固定或随页面的其余部分滚动"`

- `1. scroll="默认值 背景图像会随着页面其余部分的滚动而移动"`
  `2. fixed="当页面的其余部分滚动时，背景图像不会移动"`

`6、background-origin="规定背景图片的定位区域"`

- `1. border-box="边框开始显示背景图"`

  `2. padding-box="内边距开始显示背景图"`

  `3. content-box="内容区域开始显示背景图"`

`7、background-clip="规定背景的绘制区域"`

- `1. border-box="超出边框的部分将裁剪掉"`

  `2. padding-box="超出内边距的部分将裁剪掉"`

  `3. content-box="超出内容区域的部分将裁剪掉"`

`8、background-size="规定背景图片的尺寸"`

- `1. 第一个值设置宽度，第二个值设置高度"`

  `2. cover="保证长宽比不变 始终填充满容器 超出部分会被隐藏"`

  `3. contain="保证长宽比不变将图片完整地显示在容器中可能会导致容器的部分区域为空白"`

`9、background="在一个声明中设置所有的背景属性"`

