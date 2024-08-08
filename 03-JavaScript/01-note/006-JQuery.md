## 006-JQuery

`选择器`
--

```js
console.log($)
console.log(jQuery)

<ul>
    <li>1</li>
    <li class="a">2</li>
    <li>3</li>
    <li class="b">4</li>
    <li>5</li>
    <li class="a">6</li>
    <li>7</li>
    <li id="box">8</li>
    <li>9</li>
    <li>10</li>
</ul>

console.log($('#box'))
console.log($('.a'))
console.log($('li'))
console.log($('li:nth-child(odd)'))
console.log($('li:nth-child(even)'))

<ul>
    <li>1</li>
    <li>2</li>
    <li>3</li>
    <li>4</li>
    <li>5
        <i>子两级</i>
    </li>
    <i>子一级</i>
    <span>我是 ul 内的一个 span 标签</span>
    <li>6</li>
    <li>7
        <p>
            <i>子三级</i>
        </p>
    </li>
    <li>8</li>
    <li>9</li>
    <li>10</li>
</ul>

console.log($('li').first())
console.log($('li').last())
console.log($('li').eq(3))
console.log($('span').next())
console.log($('span').nextAll())
console.log($('span').prev())
console.log($('span').prevAll())
console.log($('span').parent())
console.log($('span').parents())
console.log($('span').siblings())
console.log($('ul').find('i'))
```

`操作文本内容 innerHTML innerText value`
--

```js
<div>
    hello
    <p>你好 世界</p>
    world
</div>
<input type="text" value="hello world">

console.log($('div').html())
$('div').html('<h2>我是后来设置的内容</h2>')
console.log($('div').text())
$('div').text('<h2>我是后来设置的内容</h2>')
console.log($('input').val())
```

`操作元素类名`
--

```js
<div class="a b c d"></div>
<button>切换</button>

$('div').addClass('e')
$('div').removeClass('b')
var btn = document.querySelector('button')
btn.onclick = function () {
    $('div').toggleClass('box')
}
```

`操作元素样式`
--

```js
<div style="width: 100px;"></div>

console.log($('div').css('width'))
$('div').css('width', '300px')
$('div').css({
    width: 260,
    height: 320,
    opacity: 0.68,
    'background-color': 'purple'
})
```


`操作元素属性`
--

```js
<div id="box" hello="world"> 我是一个 div 标签 </div>

console.log($('div').attr('hello'))
$('div').attr('a', 100)
$('div').removeAttr('hello')

$('div').prop('id', 'container')
console.log($('div').prop('id'))
$('div').removeProp('id')
```

`获取元素尺寸`
--

```js
console.log($('div').width())
console.log($('div').height())
console.log($('div').innerWidth())
console.log($('div').innerHeight())
console.log($('div').outerWidth())
console.log($('div').outerHeight())
console.log($('div').outerWidth(true))
console.log($('div').outerHeight(true))
```

`操作元素偏移量`
--

```js
console.log('div : ', $('div').offset())
console.log($('span').position())
```

`事件绑定`
--

```js
$('div').on('click', function () { console.log('我是 div 的点击事件') })
$('div').on('click', 'p', function () { console.log('我是事件委托形式的事件') })
$('div').on({
    click: function () { console.log('点击事件') },
    mouseover: function () { console.log('鼠标移入事件') },
    mouseout: function () { console.log('鼠标移出事件') }
})

$('div').one('click', function () { console.log('基础绑定事件') })
$('div').one('click', 'p', function () { console.log('事件委托绑定事件') })
$('div').one({
    click: function () { console.log('点击事件') },
    mouseover: function () { console.log('鼠标移入事件') },
    mouseout: function () { console.log('鼠标移出事件') }
})

$('div').hover(
    function () { console.log('函数1') },
    function () { console.log('函数2') }
)

$('div').click(function () { console.log('点击事件') })
$('div').mouseover(function () { console.log('...') })
$('div').mouseout()(function () { console.log('...') })
$('div').change(function () { console.log('...') })
```

`事件的解绑和触发`
--

```js
function handlerA() { console.log('我是 handlerA 事件处理函数') }
function handlerB() { console.log('我是 handlerB 事件处理函数') }
$('div')
    .click(handlerA)
    .click(handlerB)
$('div').off('click')
$('div').off('click', handlerB)

$('div').trigger('click')

setInterval(function () {
    $('div').trigger('click')
}, 1000)
```

`基本动画`
--

```js
$('button:nth-child(1)').click(function () {
    $('div').show(1000, 'linear', function () { console.log('show 结束了') })
})
$('button:nth-child(2)').click(function () {
    $('div').hide(1000, 'linear', function () { console.log('hide 结束了') })
})
$('button:nth-child(3)').click(function () {
    $('div').toggle(1000, 'linear', function () { console.log('toggle 结束了') })
})

$('button:nth-child(1)').click(function () {
    $('div').slideDown(1000, 'linear', function () { console.log('show 结束了') })
})
$('button:nth-child(2)').click(function () {
    $('div').slideUp(1000, 'linear', function () { console.log('hide 结束了') })
})
$('button:nth-child(3)').click(function () {
    $('div').slideToggle(1000, 'linear', function () { console.log('toggle 结束了') })
})

$('button:nth-child(1)').click(function () {
    $('div').fadeIn(1000, 'linear', function () { console.log('show 结束了') })
})
$('button:nth-child(2)').click(function () {
    $('div').fadeOut(1000, 'linear', function () { console.log('hide 结束了') })
})
$('button:nth-child(3)').click(function () {
    $('div').fadeToggle(1000, 'linear', function () { console.log('toggle 结束了') })
})
$('button:nth-child(4)').click(function () {
    $('div').fadeTo(1000, 0.68, 'linear', function () { console.log('运动到了指定的透明度') })
})
```

`动画`
--

```js
$('button').click(function () {
    $('div').animate({
        width: 500,
        height: 600,
    }, 1000, 'linear', function () { console.log('运动结束了') })
})
```

`结束动画`
--

```js
$("button:nth-child(1)").click(function () {
    $('div').stop().toggle(2000)
})
$("button:nth-child(1)").click(function () {
    $('div').finish().toggle(2000)
})
```

`ajax请求`
--

```js
$.ajax({
    url: 'http://localhost:8888/',
    method: 'POST',
    async: false,
    data: { name: '...', age: '...' },
    success: function (res) {
        console.log(res)
    },
    error: function (res) { }
})
```
