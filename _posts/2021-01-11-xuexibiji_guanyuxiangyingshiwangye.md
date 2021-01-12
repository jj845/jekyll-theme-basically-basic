---
title: 网新人怎么可以不会响应式网页呢~
excerpt_separator: "<!--more-->"
categories:
 _ 学习笔记
---

用两个W和一个H说说响应式网页吧~

<!--more-->
### What(概念)
简单来说是让你的网页跟你的设备进行相应的调整和匹配，这也就是所谓的响应式布局。

### Why(原因)
随着国内移动互联网的快速发展，移动端用户已超过8亿用户,
响应式网站建设是进行全网营销推广的必然选择和最好选择。
也就是说我们对网页的要求在不断增加，寻找更好的体验感。

### How(怎么做)
#### 首先，要在网页设计头部添加一行viewport元标签，这是最重要的一步
源代码
```
<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,minimum-scale=1.0,user-scalable=no">
```
1.那这行代码有什么好处呢？
2.它可以让你的网页适用于手机端

#### 其次，便是不能把宽度设成绝对，不然无法变化
源代码
```
width:auto; / width:XX%;
```

#### 第三，便是字体的大小，意思就是不要用绝对"px",而要用相对"rem"
源代码
```
html{font-size:62.5%;}
body {font:normal 100% Arial,sans-serif;font-size:14px; font-size:1.4rem; }
```
但为什么是62.5%呢？
其实道理很简单，我们的浏览器默认字体大小是16px，而1rem=10px,10/16=62.5%，这样子可以让计算更加方便

#### 第四，流动布局
从字面上来讲，就是你网页上的每个区块应该是灵活，而不是死板地固定在那里
源代码
```
.left{ width:30%; float:left} 
.right{ width:70%; float:right;}
```
用left和right后，若是页面的宽度太小，放不下两个元素，后面的元素会自动滚动到前面元素的下方，不会在水平方向overflow（溢出），避免了水平滚动条的出现，给客户更好的视觉感受以及方便

#### 第五，图片的缩放
在一个网页当中，不可缺少的便是图片，让图片随着屏幕大小变化而变化，也是十分重要的。
源代码
```
img, object {max-width: 100%;}
```
运用max-width后，可以让图片自动缩放

#### 最后一点，也是特别重要的一点，用CSS来实现响应式网页
##### 最简单的一种便是直接加入
源代码
```
@media screen and (max-width:980px ) {
body{
background-color: red;
}
}
```
怎么解释呢
就是如果媒体类型屏幕的可视窗口宽度小于 480 px ，背景颜色变为红色。

##### 另外一种，也是我们最常用的一种，便是link
源代码
```
<link rel="stylesheet" type="text/css" media="screen and (max-device-width: 600px)" href="style/css/css600.css" />
```
怎么解释呢
就是当你的屏幕小于600px，就加载css600.css这个文件；若大于600px，就加载css980.css文件

#### @media与@media screen有什么不一样呢？
@media与@media screen两者在手机设备上没有区别，但@media screen的css在打印设备里是无效的，而@media在打印设备里是有效的，如果css需要用在打印设备里，那么就用@media 。

### 这些便是响应式网页设计的一些知识啦~







