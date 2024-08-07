## Html图像

`<img>="定义图像"`
--
`1、src="路径"`

`2、width="宽度"`

`3、height="高度"`

`4、alt="替代文本"`

`5、longdesc="指向图像详细描述的URL"`

`6、loading ="指定浏览器是否应立即加载图像"`
- `1. eager="默认 立即加载图像"`

  `2. lazy="延迟加载图像，直到满足某些条件"`

`7、sizes="规定不同页面布局的图像尺寸"`

`8、ismap="将图像定义为服务器端图像映射"`

`9、usemap="#mapname 将图像定义为客户器端图像映射"`

`<map>="定义图像映射"`
--
`1、name="必需 规定图像地图的名称"`

`<area>="定义图像地图内部的区域"`
--
`1、alt="规定区域的替代文本 如果存在 href 属性则为必需"`

`2、shape="规定区域的形状"`

- `1. default="规定整个区域"`

  `2. rect="定义矩形区域""`

  `3. circle="定义圆形区域"`

  `4. poly="定义多边形区域"`

`3、coords="规定区域的坐标"`

- `1. 矩形左上角和右下角的坐标 `

  `2. 圆心的坐标和半径`

  `3. 多边形边的坐标 如果第一个和最后一个坐标对不相同，浏览器将添加最后一个坐标对来闭合多边形`

`4、Href="URL 映射地址"`

```html
<map>
<img src="" alt="" usemap="#mapname " width="650" height="451">
<map name="mapname">
  <area shape="rect" coords="10,208,155,338" alt="" href="">
  <area shape="circle" coords="570,291,75" alt="" href="">
</map>
```

`5、download="规定当用户单击超链接时将下载目标"`

- `1. filename="可选 规定下载文件的新文件名"`

`6、target="规定在何处打开目标 URL"`

- `1. _blank="在新窗口或选项卡中打开链接文档"`

  `2. _self="在与点击相同的框架中打开链接的文档 默认"`

  `3. _parent="在父框架中打开链接文档"`

  `4. _top="在窗口的整个主体中打开链接的文档"`
  
  `5. framename="在指定的 iframe 中打开链接文档"`

`<canvas>="用于通过脚本通常是 JavaScript动态绘制图形"`
--
`1、height="规定画布的高度 默认值为 150"`

`2、width="规定画布的宽度 默认值为 300"`

`<figure>="规定自包含的内容"`
--

`<figcaption>="标题"`
--

`<picture>="定义多个图像资源的容器"`
--

`<svg>="定义 SVG 图形的容器"`
--

## css
```css
img {
    display: inline-block;
}

map {
    display: inline;
}

area {
    display: none;
}

canvas {
    height: 150px;
    width: 300px;
}

figcaption {
    display: block;
}

figure {
    display: block;
    margin-top: 1em;
    margin-bottom: 1em;
    margin-left: 40px;
    margin-right: 40px;
}
```
