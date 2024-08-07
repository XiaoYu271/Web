## Html框架

`<iframe>="定义行内框架即内联框架"`
--
`1、src="规定要嵌入到框架中的页面的地址"`

`2、width="宽度 默认 300 "`

`3、height="高度 默认 150 "`

`4、name="规定框架名称"`

`5、frameborder="框架边框 无: 0 有: 1"`

```html
    <iframe src="" frameborder="1" width="100%" height="500x"></iframe>
```

```html
    <!-- 框架中打开超链接 -->
    <iframe src="" name="iframe" width="600" height="400"></iframe>
    <a href="" target="iframe">link</a>
```
`6、referrerpolicy="规定在获取框架时要发送的引用信息"`

- `1. no-referrer="不会随请求一起发送引用者信息"`

  `2. no-referrer-when-downgrade="默认 如果没有 HTTPS 引用标头将不会发送到源"`

  `3. origin="仅向请求客户端发送协议 主机和端口信息"`

  `4. origin-when-cross-origin="对于跨域请求：仅发送协议、主机和端口信息 对于同源请求：还需包括路径信息"`

  `5. same-origin="对于同源请求，发送引用者信息 对于跨域请求，不发送引用者信息"`

  `6. strict-origin="仅在安全级别相同例如 HTTPS 到 HTTPS 时才发送引用者信息不要发送到不太安全的目的地例如 HTTPS 到 HTTP"`

  `7. strict-origin-when-cross-origin="在进行同源请求时，发送完整路径信息 当安全级别保持不变时（例如 HTTPS 到 HTTPS），仅发送源站点信息不向较不安全的目标站点发送任何头信息（例如 HTTPS 到 HTTP）"`

  `8. unsafe-url="发送来源、路径和查询字符串信息（但不包括片段、密码或用户名）此值被视为不安全的"`

`7、sandbox="启用一系列对框架中内容的额外限制"`

- `1. ""="应用所有限制"`

  `2. allow-forms="允许表单提交"`

  `3. allow-modals="允许打开模态窗口"`

  `4. allow-orientation-lock="允许锁定屏幕方向"`
  
  `5. allow-pointer-lock="允许使用 Pointer Lock API"`

  `6. allow-popups="允许弹出窗口"`

  `7. allow-popups-to-escape-sandbox="允许弹出窗口打开新窗口 而不继承沙盒化"`

  `8. allow-presentation="允许开始演示会话"`

  `9. allow-same-origin="允许框架内容被视为与包含文档有相同的来源"`

  `10. allow-scripts="允许运行脚本"`

  `11. allow-top-navigation="允许框架内容导航其顶级浏览上下文"`

  `12. allow-top-navigation-by-user-activation="允许框架内容导航其顶级浏览上下文，但仅在用户发起的情况下"`

`8、srcdoc="规定要在框架中显示的页面的 HTML 内容 覆盖src"`
--

`9、Allowfullscreen="如果框架可以通过调用 `
--

`10、requestFullscreen() 方法激活全屏模式 则设置为 true "`
--

`10、Allowpaymentrequest="如果允许跨源框架调用Payment Request API 则设置为 true "`

## css

```css
iframe:focus {
    outline: none;
}

iframe[seamless] {
    display: block;
}
```