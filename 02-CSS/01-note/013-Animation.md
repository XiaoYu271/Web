## 013-Animation

`定义动画`
--
`1、@keyframes="规定动画"`
`语法：@keyframes animationname {keyframes-selector {css-styles;}}`

  `1. animationname="必需 定义动画的名称"`

  `2. keyframes-selector="必需 动画时长的百分比 合法的值 0-100% 注: from 与0% 相同 to 与100% 相同"`

  `3. css-styles="必需 一个或多个合法的CSS 样式属性"`

`调用动画`
--
`1、animation="动画名称 持续时间 执行次数 是否反向 运动曲线 延迟执行"`

`语法：animation: name duration iteration-count direction timing-function delay`

`2、animation-name="规定 @keyframes 动画的名称"`

- `1. keyframename="规定需要绑定到选择器的keyframe的名称"`

  `2. none="规定无动画效果 可用于覆盖来自级联的动画"`

`3、animation-duration="规定动画完成一个周期所花费的秒或毫秒"`
- `1. time="规定完成动画所花费的时间"`

`4、animation-iteration-count="规定动画被播放的次数"`

- `1. n="定义动画播放次数的数值"`

  `2. infinite="规定动画应该无限次播放"`

`5、animation-direction="规定动画是否在下一周期逆向地播放"`

- `1. normal="默认值 动画应该正常播放"`

  `2.alternate="动画应该轮流反向播放"`

`6、animation-timing-function="规定动画的速度曲线"`

- `1. linear="描述动画从头到尾的速度是相同的"`

  `2. ease="默认 动画以低速开始 然后加快 在结束前变慢"`

  `3. ease-in="动画以低速开始"`

  `4. ease-out="动画以低速结束"`

  `5. ease-in-out="动画以低速开始和结束"`

  `6. cubic-bezier(n,n,n,n)="在 cubic-bezier 函数中自己的值 可能的值是从 0 到 1的数值"`

`7、animation-delay="规定动画何时开始"`
- `1. time="可选 定义动画开始前等待的时间 以秒或毫秒计"`

`8、animation-fill-mode="规定对象动画时间之外的状态"`

- `1. none="不改变默认行为"`

  `2. forwards="当动画完成后，保持最后一个属性值 在最后一个关键帧中定义"`

  `3. backwards="在animation-delay所指定的一段时间内，在动画显示之前，应用开始属性值在第一个关键帧中定义"`

  `4. both="向前和向后填充模式都被应用"`

`9、animation-play-state="规定动画是否正在运行或暂停"`

- `1. paused="规定动画已暂停"`

  `2. running="规定动画正在播放"`

