## Html事件

`1、Window="针对 window 对象触发的事件 应用到 <body> 标签"`

- `1. onafterprint="文档打印之后运行的脚本"`
 
  `2. onbeforeprint="文档打印之前运行的脚本"`
 
  `3. onbeforeunload="文档卸载之前运行的脚本"`
 
  `4. onerror="在错误发生时运行的脚本"`
 
  `5. onhaschange="当文档已改变时运行的脚本"`
 
  `6. onload="页面结束加载之后触发"`
 
  `7. onmessage="在消息被触发时运行的脚本"`
 
  `8. onoffline="当文档离线时运行的脚本"`
 
  `9. ononline="当文档上线时运行的脚本"`
 
  `10. onpagehide="当窗口隐藏时运行的脚本"`
 
  `11. onpageshow="当窗口成为可见时运行的脚本"`
 
  `12. onpopstate="当窗口历史记录改变时运行的脚本"`
 
  `13. onredo="当文档执行撤销 redo 时运行的脚本"`
 
  `14. onresize="当浏览器窗口被调整大小时触发"`
  
  `15. onstorage="在 Web Storage 区域更新后运行的脚本"`
  
  `16. onundo="在文档执行 undo 时运行的脚本"`
  
  `17. onunload="一旦页面已下载时触发 或者浏览器窗口已被关闭"` 
  
`2、Form="由 HTML 表单内的动作触发的事件 应用到几乎所有 HTML 元素，但最常用在 form 元素中"`

- `1. onblur="元素失去焦点时运行的脚本"`
 
  `2. onchange="在元素值被改变时运行的脚本"`
 
  `3. oncontextmenu="当上下文菜单被触发时运行的脚本"`
 
  `4. onfocus="当元素获得焦点时运行的脚本"`
 
  `5. onformchange="在表单改变时运行的脚本"`
 
  `6. onforminput="当表单获得用户输入时运行的脚本"`
 
  `7. oninput="当元素获得用户输入时运行的脚本"`
 
  `8. oninvalid="当元素无效时运行的脚本"`
 
  `9. onreset="当表单中的重置按钮被点击时触发 HTML5 中不支持"`
 
  `10. onselect="在元素中文本被选中后触发"`
 
  `11. onsubmit="在提交表单时触发"`

`3、Keyboard `

- `1. onkeydown="在用户按下按键时触发"`

  `2. onkeypress="在用户敲击按钮时触发"`

  `3. onkeyup="当用户释放按键时触发"`      

`4、Mouse="由鼠标或类似用户动作触发的事件"` 

- `1. onclick="元素上发生鼠标点击时触发"`

  `2. ondblclick="元素上发生鼠标双击时触发"`

  `3. ondrag="元素被拖动时运行的脚本"`

  `4. ondragend="在拖动操作末端运行的脚本"`

  `5. ondragenter="当元素元素已被拖动到有效拖放区域时运行的脚本"`

  `6. ondragleave="当元素离开有效拖放目标时运行的脚本"`

  `7. ondragover="当元素在有效拖放目标上正在被拖动时运行的脚本"`

  `8. ondragstart="在拖动操作开端运行的脚本"`

  `9. ondrop="当被拖元素正在被拖放时运行的脚本"`

  `10. onmousedown="当元素上按下鼠标按钮时触发"`

  `11. onmousemove="当鼠标指针移动到元素上时触发"`

  `12. onmouseout="当鼠标指针移出元素时触发"`

  `13. onmouseover="当鼠标指针移动到元素上时触发"`

  `14. onmouseup="当在元素上释放鼠标按钮时触发"`

  `15. onmousewheel="当鼠标滚轮正在被滚动时运行的脚本"`

  `16. onscroll="当元素滚动条被滚动时运行的脚本"` 

  
`5、Media="由媒介 比如视频、图像和音频 触发的事件 适用于所有 HTML 元素，但常见于媒介元素中，比如 <audio>、<embed>、<img>、<object> 以及 <video></video>"`

- `1. onabort="在退出时运行的脚本"`

  `2. oncanplay="当文件就绪可以开始播放时运行的脚本 缓冲已足够开始时"`

  `3. oncanplaythrough="当媒介能够无需因缓冲而停止即可播放至结尾时运行的脚本"  `

  `4. ondurationchange="当媒介长度改变时运行的脚本"`

  `5. onemptied="当发生故障并且文件突然不可用时运行的脚本 比如连接意外断开时"`

  `6. onended="当媒介已到达结尾时运行的脚本 可发送类似“感谢观看”之类的消息"`

  `7. onerror="当在文件加载期间发生错误时运行的脚本"`

  `8. onloadeddata="当媒介数据已加载时运行的脚本"`

  `9. onloadedmetadata="当元数据 比如分辨率和时长 被加载时运行的脚本"`

  `10. onloadstart="在文件开始加载且未实际加载任何数据前运行的脚本"`

  `11. onpause="当媒介被用户或程序暂停时运行的脚本"`

  `12. onplay="当媒介已就绪可以开始播放时运行的脚本"`

  `13. onplaying="当媒介已开始播放时运行的脚本"`

  `14. onprogress="当浏览器正在获取媒介数据时运行的脚本"`

  `15. onratechange="每当回放速率改变时运行的脚本 比如当用户切换到慢动作或快进模式"`

  `16. onreadystatechange="每当就绪状态改变时运行的脚本 就绪状态监测媒介数据的状态"`

  `17. onseeked="当 seeking 属性设置为 false 指示定位已结束 时运行的脚本"`

  `18. onseeking="当 seeking 属性设置为 true 指示定位是活动的 时运行的脚本"`

  `19. onstalled="在浏览器不论何种原因未能取回媒介数据时运行的脚本"`

  `20. onsuspend="在媒介数据完全加载之前不论何种原因终止取回媒介数据时运行的脚本"`

  `21. ontimeupdate="当播放位置改变时 比如当用户快进到媒介中一个不同的位置时 运行的脚本"`

  `22. onvolumechange="每当音量改变时 包括将音量设置为静音 时运行的脚本"`

  `23.	onwaiting="当媒介已停止播放但打算继续播放时 比如当媒介暂停已缓冲更多数据 运行脚本"`