# 认识前端：html

知识点：

- 前端是什么？







## 前端是什么

前端指浏览器端。

前端开发工程师，职责：

- 构建页面结构
- 美化页面
- 页面交互

前端的知识体系

- HTML: 描述页面中的内容
- CSS：美化页面
- JavaScript：动效、交互
  - VUE
  - React
  - AngularJS
  - Node.js
  - 太多太多

## 认识HTML





## 创建一个项目

- 创建了一个文件夹
- 创建了首页
- 创建了服务页

## 网页文档的基本结构

网页文档指 文件扩展名 .html 的文件

```html
<!DOCTYPE html>  <!--DOCUMENT:文档 TYPE：类型  HTML就是答案  除了html语言浏览器还可以渲染XML-->
<html>
	<head>
		
		<title></title>
	</head>
	<body>
    <p>
      我是一个段落安
    </p>
	</body>
</html>
```



## HTML

含义：

H: hyper 超范围

T: TEXT  文本

M: 标记 markup

L： language 语言

用途：用于描述页面中的内容。

文字

图片

视频

音频

flash

等

学习HTML，其实就是背单词，记住每一个标签的用途。

H1  定义一级标题

H2 定义二级标题



## 四大结构标签

结构标签一共只有4个，

结构标签是一个网页都必须有的结构。



## Html语法

- 标签构成：
- 分类：
  - 对标签：标签都是成对出现的，有开始标签就必须有结束标签
  - 单标签：单标签也必须关闭

```html
对标签：
<html><body></body></html>
<p>  </p>
单标签
<br/>

合理嵌套：
<html><body></body></html>
不合理嵌套：
<html><body></html></body>
```

- 含义：所有的标签都具有特定的含义
- 属性：所有的标签都具有N种属性
- 大小写：
- 嵌套：

## 认识标签

### 文档基本结构标签

\<html>定义web文档

\<head>定义文档头部区域。头部区域中的常常放置3种信息：

- 提供给浏览器使用的信息
- 提供给搜索引擎使用的信息
- 提供给开发人员使用的信息

注意：头部区域中的内容是不显示在页面中的。

\<title>定义网页文档标题 必须出现在head标签内

\<body>定义文档主体区域

- 页面中看到的内容全部要放在body标签内部

### 文档内容标签

内容标签用于描述内容。

```html
<img /> 定义图片
<ul></ul> 用于定义无序列表。无序就是不强调顺序。 unorder list 
<li></li> 用于定义列表项。
<input /> 用于定义一个输入框。
<p></p> 用于定义一个段落。 paragraph
<span></span> span：范围、跨度 这里 引申为定义一段小文本。
<a href="index.html">首页</a> : 连接到首页
<a href="#">购买须知</a> ： # 空链接（代表指向当前文档，不指向其他页面。等确定其他页面地址之后再修改。）
<h1></h1> 用于定义一级标题
<h6></h6> 用于定义六级标题
<p></p> 定义段落
<div></div> 用于创建结构块。块就是一个范围、就是一个组。
<hr />  用来定义分割线（水平线） horizontal水平的

```

## div标签

特殊的标签：

- 没有明确的语义

div的理解：

- div用来构建结构块
- 搭建页面布局结构
- div相当于xd中的编组
- Division  分隔物

## 标签的属性

标签可以看出是一个对象：

- p标签=p对象
- h1标签 = h1对象

对象是属性的集合。

每一个标签都具有N种属性。

标签属性的分类：

- 全局属性：所有的标签都具有的属性
  - id: identify 确认身份的 可识别 唯一 
  - class: 类、一组 用来为标签设置分组。
  - title
  - style

```html
<div id='yetou'> hello world </div>
<div id='yetou2' class='aaa'> hello world </div>
<div id='yetou3'> hello world </div>
<div id='yetou4' class='aaa'> hello world </div>
<div id='yetou5'> hello world </div>
<div id='yetou6' class='aaa'> hello world </div>
```



- 局部属性：局部就是特殊的意思。某个标签的独有属性。比如：
  - a标签：href-定义超链接的指向地址。



















