---
layout: post
title:  "Markdown语法"
date:   2018-01-23
excerpt: "使用markdowm来写你的blog,你就会需要了解到更多......"
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

## HTML元素

以下是您需要在blog中进行设计的所有内容。检查源代码以查看段落中的许多嵌入式元素。

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### 主体

 使用`**加粗**`**加粗**.

![图片](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

我是天空里的一片云 
偶尔投影在你的波心 
你不必讶异 
更无须欢喜 
在转瞬间消灭了踪影 

你我相逢在黑夜的海上 
你有你的，我有我的，方向 
你记得也好 
最好你忘掉 
在这交会时互放的光亮


### 引用文字

> 最是那一低头的温柔 像一朵水莲花不胜凉风的娇羞             ——徐志摩 《沙扬娜拉》

## 列表类型

### 有序列表

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
  2. Item two

### 无序列表

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## 代码片段

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

使用 `.btn` class让更多的链接脱颖而出.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

你可以用 `<kbd>` 用来标识键盘按键.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

例如：使用<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> 进行移动. **嘻嘻😳!!**

## 通知

**Watch out!** 您还可以添加一个段落，以添加通知。 `{: .notice}`
{: .notice}
