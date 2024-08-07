## Html音频视频

`<audio>="定义嵌入的声音内容"`
--
`1、src="规定音频文件的 URL"`

`2、autoplay="准备就绪后立即开始播放"`

`3、controls="显示音频控件 例如播放/暂停按钮等`

`4、loop="音频将在每次结束后重新开始"`

`5、muted="音频输出应静音"`

`6、preload="规定是否以及如何在页面加载时加载音频"`

- `1. auto="页面加载时加载整个音频文件"`

  `2. metadata="页面加载时只加载元数据"`

  `3. none="不应该在页面加载时加载音频文件"`

`<source>="定义媒体元素音频视频图像的多个媒体资源"`
--

```html
<audio controls>
  <source src="1.ogg" type="audio/ogg">
  <source src="1.mp3" type="audio/mpeg">
</audio>
```

```html
<video width="640" height="400" controls>
  <source src="1.mp4" type="video/mp4">
  <source src="1.ogg" type="video/ogg">
</video>
```

```html
<picture>
  <source media="(min-width:650px)" srcset="1.jpg">
  <source media="(min-width:465px)" srcset="2.jpg">
  <img src="3.jpg" alt="Flowers" style="width:auto;">
</picture>
```

`<video>="定义嵌入的视频内容"`
--
`1、src="规定音频文件的 URL"`

`2、width="设置视频播放器的宽度"`

`3、height="设置视频播放器的高度"`

`4、autoplay="准备就绪后立即开始播放"`

`5、controls="显示音频控件 例如播放/暂停按钮等"`

`6、loop="音频将在每次结束后重新开始"`

`7、muted="音频输出应静音"`

`8、poster="URL下载视频期间或在用户点击播放按钮之前显示的图像`

`9、preload="规定是否以及如何在页面加载时加载音频"`

- `1. auto="页面加载时加载整个音频文件"`

  `2. metadata="页面加载时只加载元数据"`

  `3. none="不应该在页面加载时加载音频文件"`


