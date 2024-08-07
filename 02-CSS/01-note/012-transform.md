## 012-transform

`2D  3D 转换 (位移、旋转、变形、缩放)`
--

`1、transform="向元素应用2D或3D转换"`

- `1. none="定义不进行转换"`

  `2. matrix(n,n,n,n,n,n)="定义2D转换使用六个值的矩阵"`

  `3. matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n)="定义3D转换使用16个值的4x4矩阵"`

  `4. translate(x,y)="定义2D转换"`

  `5. translate3d(x,y,z)="定义3D转换"`

  `6. translateX(x)="定义转换只是用X轴的值"`

  `7. translateY(y)="定义转换只是用Y轴的值"`

  `8. translateZ(z)="定义3D转换只是用Z轴"`

  `9. scale(x,y)="定义2D缩放转换"`

  `10. scale3d(x,y,z)="定义3D缩放转换"`

  `11. scaleX(x)="通过设置X轴的值来定义缩放转换"`

  `12. scaleY(y)="通过设置Y轴的值来定义缩放转换"`

  `13. scaleZ(z)="通过设置Z轴的值来定义3D缩放转换"`

  `14. rotate(angle)="定义2D旋转在参数中规定角度"`

  `15. rotate3d(x,y,z,angle)="定义3D转换"`

  `16. rotateX(angle)="定义沿着X轴的3D旋转"`

  `17. rotateY(angle)="定义沿着Y轴的3D旋转"`

  `18. rotateZ(angle)="定义沿着Z轴的3D旋转"`

  `19. skew(x-angle,y-angle)="定义沿着X和Y轴的2D倾斜转换"`

  `20. skewX(angle)="定义沿着X轴的2D倾斜转换"`

  `21. skewY(angle)="定义沿着Y轴的2D倾斜转换"`

  `22. perspective(n)="为3D转换元素定义透视视图"`


`2、transform-origin="允许你改变被转换元素的位置"`

- `1. x-axis="定义视图被置于X轴的何处"`

  `2. y-axis="定义视图被置于Y轴的何处"`

  `3. z-axis="定义视图被置于Z轴的何处"`

`3、transform-style="规定被嵌套元素如何在3D空间中显示"`

- `1. flat="子元素将不保留其3D位置"`

`  2. preserve-3d="子元素将保留其3D位置"`

`4、perspective="规定3D元素的透视效果"`

`5、perspective-origin="规定3D元素的底部位置"`

`6、backface-visibility="定义元素在不面对屏幕时是否可见"`

- `1. visible="背面是可见的"`

  `2. hidden="背面是不可见的"` 
