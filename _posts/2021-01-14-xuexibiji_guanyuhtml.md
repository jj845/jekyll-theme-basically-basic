---
title: 啥？文科生竟然也会敲代码了！
excerpt_separator: "<!--more-->"
categories:
 _ 学习笔记
---

#### 让我们来学学html的知识吧~
<!--more-->

### 先从what说起吧
HTML 是用来描述网页的一种语言，而且还是一种标记语言 (markup language)，什么意思呢，换句话说，是一种一套标记标签 (markup tag)。
### 再说工具吧
- Sublime Text 3
- Adobe Dreamweaver
- WebStorm
一般我自己常用dw,因为它会自动帮你把html基本结构敲出来
### 因而接下来讲讲how把
#### 从基本结构说起吧
```
DTD(Document Type Definition)  -------------- 文档定义类型
<html>  -------------- 文本描述网页
    <head>  -------------- 文档头部标记：含脚本，样式表等等。
        <meta />   -------------- 定义文档字符集、使用语言、作者等基本信息
        <title>标题</title>  -------------- 定义文档的标题
    </head>
    <body>   -------------- 网页主体,是可见的页面内容
        <h1>Hello world</h1> -----------标题
    </body>
</html>
```
- <html> 与 </html> :定义描述网页
- <body> 与 </body> ：定义可见的页面内容
- <head>与</head>：头部元素
- <head> ：定义关于文档的信息。
- <title> ：定义文档标题。
- <base>：定义页面上所有链接的默认地址或默认目标。
- <link> ：定义文档与外部资源之间的关系。
- <meta>： 定义关于 HTML 文档的元数据。
- <script>： 定义客户端脚本。
- <style>： 定义文档的样式信息。

#### 接下来再说说一些基本元素吧~
##### 字体
语法
```
<b>字体加粗</b>
<i>斜体字体</i>
<u>下划线</u>
<s>删除线</s>
```
看看效果吧~
- <b>字体加粗</b>
- <i>斜体字体</i>
- <u>下划线</u>
- <s>删除线</s>

##### 标题
语法
```
<h1 align="center">1号标题</h1>
<h2>2号标题</h2>
<h3>3号标题</h3>
<h4>4号标题</h4>
<h5>5号标题</h5>
<h6>6号标题</h6>
```
看看效果吧~
<h1 align="center">1号标题</h1>
<h2>2号标题</h2>
<h3>3号标题</h3>
<h4>4号标题</h4>
<h5>5号标题</h5>
<h6>6号标题</h6>

##### 段落
语法
```
<p></p>
```
瞅瞅效果吧~
<p>第一段</p>
<p align="left">第二段</p>
<p align="center">第三段</p>
<p align="right">第四段</p>

##### 换行和水平线
语法
```
蔡徐坤呀<br />   蔡徐坤呀
<hr />蔡徐坤
```
瞅瞅效果吧~

蔡徐坤呀<br />   蔡徐坤呀
<hr />蔡徐坤

##### 列表: ol ul li
语法
```
有序列表:<ol></ol> 
   & 
无序列表:<ul></ul>
```
瞅瞅效果吧~
<ol type="i" start="3">
  <li>网新1</li>
  <li>网新2</li>
  <li>网新3</li>
</ol>

<ul type="circle">
  <li>网新1</li>
  <li>网新2</li>
  <li>网新3</li>
</ul>

###  块: div span
- 块级元素：以新行来显示。
- 内联元素：不会以新行来显示。

#### 区别
- <div> 元素是块级元素，常用于组合其他 HTML 元素的容器，进行文档布局。
- <span> 元素是内联元素，常用作文本的容器。

### 别粗心哦~ 看看有没有多一个小空空哦
例子
```
正确例子：<div>...</div>;
错误例子：<div>...< /div>;
```
### 等等，别急。还有彩蛋哦！
```
标签           	描述
<article>  定义页面独立的内容区域。
<aside>	   定义页面的侧边栏内容。
<bdi>	  允许您设置一段文本，使其脱离其父元素的文本方向设置。
<command>	定义命令按钮，比如单选按钮、复选框或按钮
<details>	用于描述文档或文档某个部分的细节
<dialog>	定义对话框，比如提示框
<summary>	标签包含 details 元素的标题
<figure>	规定独立的流内容（图像、图表、照片、代码等等）。
<figcaption>	定义 <figure> 元素的标题
<footer>	定义 section 或 document 的页脚。
<header>	定义了文档的头部区域
<mark>	定义带有记号的文本。
<meter>	定义度量衡。仅用于已知最大和最小值的度量。
<nav>	定义导航链接的部分。
<progress>	定义任何类型的任务的进度。
<ruby>	定义 ruby 注释（中文注音或字符）。
<rt>	定义字符（中文注音或字符）的解释或发音。
<rp>	在 ruby 注释中使用，定义不支持 ruby 元素的浏览器所显示的内容。
<section>	定义文档中的节（section、区段）。
<time>	定义日期或时间。
<wbr>	规定在文本中的何处适合添加换行符
<canvas>	标签定义图形，比如图表和其他图像。该标签基于 JavaScript 的绘图 API
<audio>	定义音频内容
<video>	定义视频（video 或者 movie）
<source>	定义多媒体资源 <video> 和 <audio>
<embed>	定义嵌入的内容，比如插件。
<track>	为诸如 <video> 和 <audio> 元素之类的媒介规定外部文本轨道.
<datalist>	定义选项列表。请与 input 元素配合使用该元素，来定义 input 可能的值。
<keygen>	规定用于表单的密钥对生成器字段。
<output>	定义不同类型的输出，比如脚本的输出。
```
**<!doctype> 声明必须位于 HTML5 文档中的第一行,使用非常简单:**
#### 下面是一个简单的HTML5文档：
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>文档标题</title>
</head>
 
<body>
文档内容......
</body>
 
</html>
```

**好了，以上便是html的一些小知识啦**

