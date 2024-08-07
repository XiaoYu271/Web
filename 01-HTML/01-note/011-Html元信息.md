## Html元信息

`<head>="包含文档的元数据/信息"`
--

`<meta>="定义关于 HTML 文档的元数据"`
--
`1、charset="规定 HTML 文档的字符编码"`

`2、name="元数据的类型 规定元数据的名称"`

- `1. application-name="规定页面代表的 Web 应用程序的名称"`

  `2. uthor="规定文档作者的姓名"`

  `3. description="规定页面的描述 搜索引擎可以选择此描述来显示搜索结果"`

  `4. keywords="规定与页面相关的关键字列表，以逗号分隔 告知搜索引擎关于页面的内容"`

  `5. viewport="控制视口 网页的用户可见区域"`

  `6. generator="规定用于生成文档的软件包之一 不用于手写页面"`

`3、content="元数据值"`

```html
    <meta name="description" content="页面描述">
    <meta name="keywords" content="搜索词">
    <meta name="author" content="XiaoYu">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

`<base>="规定文档中所有相对 URL 的基准 URL 和/或目标"`
--

`1、href="规定页面中所有相对 URL 的基本 URL"`

- `1. URL="充当基准 URL 的绝对 URL"`

`2、target="规定页面中所有超链接和表单的默认目标"`

- `1. _blank="在新窗口或标签页中打开链接"`

  `2. _self="默认 在单击时的在同一框架中打开链接"`

  `3. _parent="在父框架中打开链接"`

  `4. _top="在整个窗口中打开链接"`

## css

```css
head {
    display: none;
}
```
