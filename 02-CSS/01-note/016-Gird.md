## 016-Gird

`1、grid="块级网格"`

`2、inline-grid="行内块级网格"`

`3、grid-template-rows`

- `1. 固定值`

  `2. 百分比`

  `3. Repeat(Row，Size)`

  `4. Repeate(Auto-fill，Size)`

  `5. n fr="占满或平分天下"`

  `6. minmax(Size，Size)`

  `7. auto`

`4、grid-template-columns`

- `1. 固定值`

  `2. 百分比`

  `3. Repeat(Columns，Size)`

  `4. Repeate(Auto-fill，Size)`

  `5. n fr="占满或平分天下"`

  `6. minmax(Size，Size)`

  `7. auto`

`5、gap="行列间距"`

`6、row-gap="行间距"`

`7、column-gap="列间距"`

`8、grid-template-areas="划分区域 名称"`

`9、grid-area="区域名称"`

```css
grid-template-areas:'a a c'
                    'd e f'
                    'g h i'
;
```

```css
grid-area:a;
```

`10、grid-auto-flow="主轴方向"`

- `1. row="行"`

  `2. columns="列"`

`11、place-content="justify-content align-content"`

`12、justify-content="控制子元素在主轴上的排列方式"`

- `1. flex-start="从主轴的起点对齐 默认值"`

  `2. flex-end="从主轴的终点对齐"`

  `3. center="居中对齐"`

  `4. space-around="在父盒子里平分"`

  `5. space-between="两端对齐 平分"`


`13、align-content="设置子元素在侧轴上的对齐方式"`

- `1. flex-start="从侧轴开始的方向对齐"`

  `2. flex-end="从侧轴结束的方向对齐"`

  `3. baseline="基线"`

  `4. center="中间对齐"`

  `5. stretch="拉伸"`

`14、Place-items="justify-items align-items"`

`15、justify-items="控制子元素在网格内的排列方式"`

- `1. flex-start="从网格内主轴的起点对齐 默认值"`

  `2. flex-end="从网格内主轴的终点对齐"`

  `3. center="网格内居中对齐"`

  `4. space-around="在网格内父盒子里平分"`

  `5. space-between="网格内两端对齐 平分"`

`16、align-items="设置子元素在侧轴上的对齐方式"`

  `1. flex-start="从网格内侧轴开始的方向对齐"`

  `2. flex-end="从网格内侧轴结束的方向对齐"`

  `3. baseline="网格内基线"`

  `4. center="网格内中间对齐"`

  `5. stretch="网格内拉伸"`

`17、gird-row="网格线合并"`

`18、gird-row-start="网格线合并"`

`19、gird-row-end="网格线合并"`

`20、gird-columns="网格线合并"`

`21、gird-columns-start="网格线合并"`

`22、gird-columns-end="网格线合并"`

```css
gird-row: 2/4;
gird-columns: 1/3;
```

```css
gird-row-start: 2;
gird-row-end: 4;
gird-columns-start: 1;
gird-columns-end: 3;
```