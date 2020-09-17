# 认识CSS

知识点

- css简介
- css语法



## CSS简介

CSS ，直译：层叠样式表

Cascading style sheet

CSS: 使用一行一行的样式代码去控制html页面中的标签的外观。

```css
div{
  width:1000px;
  height:100px;
  background-color:red;
}
p{
  width:500px;
  height:500px;
  background-color:gold;
}
```

## CSS语法

语法格式：

选择器{ 属性:属性值; }

什么是选择器？

选择器就是你要定义样式的对象。

想为哪个标签定义样式，必须通过选择器声明。

**三大基本选择器**

- 标签选择器：
- id选择器
- class选择器

## 复杂的CSS语法

需要学习大量的属性和属性值。



## 注释的写法

html注释的写法

```html
<!-- 代码 -->
```



## 盒模型

盒模型规定，任何一个HTML标签都可以看出一个矩形框。

矩形框是有宽度的

- width属性：用于控制元素框的宽度
- height属性：用于控制元素框的高度

矩形框是有内边距的

- padding: 30px 60px 90px 120px;
- padding: 30px 60px 90px ;  上30  左右60  下90
- padding: 30px 60px;  上下30  左右60
- Padding:30px ;  上下左右30

矩形框是有边框的

Border: 1px solid black;

矩形框是有外边距的

- Margin: 30px 60px 90px 120px;
- Margin: 30px 60px 90px ;  上30  左右60  下90
- Margin: 30px 60px;  上下30  左右60
- Margin:30px ;  上下左右30

## 学习几个常用的css属性

尺寸属性：设置元素的尺寸



颜色属性：设置元素的前景色或背景色。



边距属性：设置标签的内边距或外边距。



字体属性

