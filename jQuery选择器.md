```js
//id为的div1元素
$('#div1').css('background', 'red')

//选择所有div元素；

$('div').css('background', 'red')

//选择所有 class属性为box的元素
$('.box').css('background', 'red')

//选择所有div和span元素
$('div,span').css('background', 'red')

//选择所有class属性为box的div元素；
$('div.box').css('background', 'red')

//选择UL下所有的span;
$('ul span').css('background', 'black')

//选择ul下所有子元素span;
$('ul>span').css('background', 'black')

//选中class为 box的下一个li
$('.box+li').css('background', 'black')

//选中ul下的class为box的元素后面的所有兄弟元素；
$('ul .box~*').css('background', 'black')

//读取第一个div的title属性
console.log($('div:first').attr('title'))

//给所有div设置naem属性(value：'guigu');
$('div').attr('name', 'guigu')
//移除所有div的title属性；
$('div').removeAttr('title')

//给所有div设置class='shanggui';
$('div').attr('class', 'shanggui')

//给所有div添加class='abc';
$('div').addClass('abc')

//移除所有div的guiguclass的class；
$('div').removeClass('guiguclass')

//得到最后一个li的标签文本；
console.log($('li:last').html())

//设置第一个li的标签体为"<h1>mmmmmmm</h1>";
$('li:first').html('<h1>mmmmmmm</h1>')

//得到输入框中的value值；
console.log($(':text').val())

//将输入框的值设置为atguigu;
$(':text').val('atguigu')

//点击全选按钮实现全选
var $checks = $(':checkbox')

$('button:first').click(function () {
  $checks.prop('checked', true)
})
//点击全不选按钮实现全不选
$('button:last').click(function () {
  $checks.prop('checked', false)
})
```
