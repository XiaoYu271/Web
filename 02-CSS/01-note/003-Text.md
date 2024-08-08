## 003-Text

`1、color="设置文本的颜色"`

`2、text-align="规定文本的水平对齐方式"`

- `1. left="把文本排列到左边 默认值：由浏览器决定"`

  `2. right="把文本排列到右边"`

  `3. center="把文本排列到中间"`

  `4. justify="实现两端对齐文本效果"`

`3、text-decoration="规定添加到文本的装饰效果"`
  
- `1. none="定义标准的文本 默认"`
  
  `2. overline="定义上划线"`
  
  `3. line-through="定义中划线"`
  
  `4. underline="下划线"`

`4、text-indent="规定文本块首行的缩进 例：2em"`

`5、letter-spacing="设置字符间距"`

`6、word-spacing="设置单词间距"`

`7、white-space="规定如何处理元素中的空白"`

- `1. normal="空白会被浏览器忽略 默认"`

  `2. pre="空白会被浏览器保留 方式类似HTML的Pre标签"`

  `3. nowrap="文本不会换行 文本会在在同一行上继续 到遇到br标签为止"`

  `4. pre-wrap="保留空白符序列 但是正常地进行换行"`

  `5. pre-line="合并空白符序列，但是保留换行符"`

`8、text-wrap="规定文本的换行规则"`

- `1. normal="只在允许的换行点进行换行"`

  `2. none="不换行 元素无法容纳的文本会溢出"`

  `3. unrestricted="在任意两个字符间换行"`

  `4. suppress="压缩元素中的换行 浏览器只在行中没有其他有效换行点时进行换行"`

`9、text-transform="控制文本的大小写"`

- `1. none="定义带有小写字母和大写字母的标准的文本 默认"`

  `2. capitalize="文本中的每个单词以大写字母开头"`

  `3. uppercase="定义仅有大写字母"`

  `4. lowercase="定义仅有小写字母"`

`10、direction="规定文本的方向/书写方向"`

- `1. Itr="默认 文本方向从左到右"`

  `2. rtl="文本方向从右到左"`

`11、text-shadow="向文本加阴影 水平位移/垂直位移/模糊程度/阴影颜色"`

- `1. h-shadow="水平阴影 允许负值 必需"`

  `2. v-shadow="垂直阴影 允许负值 必需"`

  `3. blur="模糊 可选"`

  `4. color="颜色 可选"`

  `凹凸文字效果的方式比较简单，给左上角放黑色的阴影，右下角放白色的阴影，就达到了凹下去的效果`

`12、hanging-punctuation="规定标点字符是否位于线框之外"`

- `1. none="不在文本整行的开头还是结尾的行框之外放置标签符号"`

  `2. first="标点附着在首行开始边缘之外"`

  `3. last="标点附着在首行结尾边缘之外"`

`13、punctuation-trim="规定是否对标点字符进行修剪"`

- `1. none="不修剪开启或闭合标点符号"`

  `2. start="修剪每行结尾的开启标点符号"`

  `3. end="修剪每行结尾的闭合标点符号"`

`14、text-align-last="设置如何对齐最后一行或紧挨着强制换行符之前的行"`

`15、text-emphasis="向元素的文本应用重点标记以及重点标记的前景色"`

- `1. text-emphasis-style="向元素的文本应用重点标记"`

  `2. text-emphasis-color="定义重点标记的前景色"`

`16、text-justify="规定当text-align设置为"justify"时所使用的对齐方法"`
- `1. auto="浏览器决定齐行算法"`

  `2. none="禁用齐行"`

  `3. inter-word="增加/减少单词间的间隔"`

  `4. inter-ideograph="用表意文本来排齐内容"`

  `5. inter-cluster="只对不包含内部单词间隔的内容 比如亚洲语系进行排齐"`

  `6. distribute="类似报纸版面 除了在东亚语系中最后一行是不齐行的"`

  `7. kashida="通过拉伸字符来排齐内容"`

`17、text-outline="规定文本的轮廓"`

- `1. thickness="必需 轮廓的粗细"`

  `2. blur="可选 轮廓的模糊半径"`

  `3. color="必需 轮廓的颜色"`

`18、text-overflow="规定当文本溢出包含元素时发生的事情"`

- `1. clip="修剪文本"`

  `2. ellipsis="显示省略符号来代表被修剪的文本"`

  `3. string="使用给定的字符串来代表被修剪的文本"`

  ```css
  overflow: hidden;
  
  white-speace: nowrap;
  text-overflow: ellipsis;
  ```
  
`19、word-break="规定非中日韩文本的换行规则"`

- `1. normal="使用浏览器默认的换行规则"`

  `2. break-all="允许在单词内换行"`

  `3. keep-all="只能在半角空格或连字符处换行"`

`20、word-wrap="允许对长的不可分割的单词进行分割并换行到下一行"`

- `1. normal="只在允许的断字点换行 浏览器保持默认处理"`

  `2. break-word="在长单词或URL地址内部进行换行"`
