## Html表单和输入标签

`<form>="表单标签"`
--
`1、action="规定提交表单时将表单数据发送到哪里 必须"`

`2、name="规定表单的名称"`

`<input>="输入控件标签"`
--
`1、type="元素类型"`

- `1. txet="输入框"`

  `2. password="密码框"`

  `3. radio="单选框"`

  `4. checkbox="复选框"`

  `5. file="文件选择浏览按钮"`

  `6. image="图像提交按钮"`

`2、name="名称"`

`3、value="默认内容"`

`4、width="宽度"`

`5、height="高度"`

`6、autofocus="自动获得焦点"`

`7、readonly="只读"`

`8、disabled="禁用"`

`9、required="必填或必选"`

`10、checked="预选 适用 单选框 复选框"`

`11、placeholder="规定描述元素预期值的简短提示"`

`12、size="宽度 以字符数为单位"`

`13、pattern="规定检查元素值的正则表达式"`

`14、accept="文件类型过滤器"`

- `1. ext="文件扩展名 如：、gif、、jpg"`

  `2. audio/*="声音文件"`

  `3. video/*="视频文件"`

  `4. image/*="图像文件"`

`15、max min="规定最大值 最小值"`

- `1. number="数值"`

  `2. date="日期"`

`16、maxlength minlength="规定最大和最小字符数 默认 最大值为524288 无最小"`

`17、list="id 引用预定义选项的<datalist>元素"`

```html
<input list="111" name="">
<datalist id="111">
    <option value="IE">
    <option value="Edge">
    <option value="Chrome">
</datalist>
```

`18、src="规定用作提交按钮的图像的 URL"`

`19、alt="图像的替代文本"`

`<textarea>="多行文本输入控件标签"`
--
`1、name="规定文本区域的名称"`

`2、cols="文本区域的可见宽度"`

`3、rows="文本区域中可见的行数"`

`4、autofocus="自动获得焦点"`

`5、readonly="只读"`

`6、disable="禁用"`

`7、required="必填"`

`8、placeholder="规定描述元素预期值的简短提示"`

`9、maxlength="规定文本区域允许的最大字符数"`

`10、wrap="规定在表单中提交时文本区域中的文本如何换行"`

- `1. soft="默认 在表单中提交时文本区域中的文本不换行"`

  `2. hard="在表单中提交时文本区域中的文本会被换行 必须规定cols属性"`

`<button>="按钮标签"`
--
`1、name="规定按钮的名称"`

`2、type="规定按钮的类型"`

- `1. button="可点击按钮"`

  `2. submit="提交按钮"`

  `3. reset="重置按钮"`

`3、value="规定按钮的初始值"`

`4、autofocus="自动获得焦点"`

`5、disable="禁用"`

`<select>="下拉列表标签"`
--
`1、name="定义下拉列表的名称"`

`2、form="定义下拉列表所属的表单"`

`3、 autofocus="规定下拉列表应在页面加载时自动获得焦点"`

`4、disabled="禁用"`

`5、required="必填"`

`6、multiple="规定可以一次选择多个选项"`

`7、size="定义下拉列表中可见选项的数量"`

`<optgroup>="下拉列表相关选项分组"`
--
`1、disabled="规定应禁用选项组"`

`2、label="规定选项组的标签"`

`<option>="下拉列表中选项的标签"`
--
`1、disabled="规定选项应该被禁用"`

`2、label="为选项规定较短的标签"`

`3、selected="规定在页面加载时应预先选择一个选项"`

`4、value="规定要发送到服务器的值"`

`<label>="定义 input 元素 的标注"`
--
`1、for="规定 label 绑定到哪个表单元素"`

`2、form="规定 label 字段所属的表单"`

`<fieldset>="对表单中的相关元素进行分组" `
--
`1、name="规定字段集的名称"`

`2、 disabled="规定应禁用一组相关的表单元素"`

`<legend>="定义 fieldset 元素的标题"`
--

`<datalist>="规定输入控件的预定义选项列表"`
--

`<output>="定义计算的结果"`
--

## css

```css
form {
    display: block;
    margin-top: 0em;
}

label {
    cursor: default;
}

fieldset {
    display: block;
    margin-left: 2px;
    margin-right: 2px;
    padding-top: 0、35em;
    padding-bottom: 0、625em;
    padding-left: 0、75em;
    padding-right: 0、75em;
    border: 2px groove (internal value);
}

legend {
    display: block;
    padding-left: 2px;
    padding-right: 2px;
    border: none;
}

datalist {
    display: none;
}

output {
    display: inline;
}
```