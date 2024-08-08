## 005-Ajax

`Ajax 语法`
--
```js
var xhr = new XMLHttpRequest()
xhr.open('请求方式:按照接口文档来进行书写','请求地址: 按照接口文档来进行书写','是否异步: 默认是 true 表示异步请求 选填为 false 表示同步请求')
xhr.onload = function () {
    var res = JSON.parse(xhr.responseText)
    console.log(res)
}
xhr.send()
```

`GET 和 POST 请求`
--

`GET`

```js
var xhr = new XMLHttpRequest()
xhr.open('GET', 'Website?name=...&age=...', true)
xhr.onload = function () {
    console.log(JSON.parse(xhr.responseText))
}
xhr.send()
```

`POST`

```js
var xhr = new XMLHttpRequest()
xhr.open('POST', 'Website', true)
xhr.onload = function () {
    console.log(JSON.parse(xhr.responseText))
}
xhr.setRequestHeader('content-type', '传递参数的格式:application/x-www-form-urlencoded')
xhr.send('name=...&age=...')
```

