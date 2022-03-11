---
title: Markdown之使用技巧
date: 2022-02-28 15:23:55
tags: [Markdown,使用技巧]
categories: [Markdown]
---


>本篇主要介绍Markdown的几种简单书写方法，后续会不断新增和整理变化  


<hr style="background-color:#8FBC8F;height:4px;border:none;">

##### 标题：
一级与六级标题的表达主要是在文字前加井号控制，中间级由添加“#”多少决定。

 <!-- more -->

``` bash
# Markdown
###### Markdown
```
***

<p style="font-family: 'Lato','PingFang SC','Microsoft YaHei', sans-serif;
    font-weight: bold;
    line-height: 1.5;
    margin: 20px 0 15px;font-size: 1.5em;padding-top: 10px;    margin-block-start: 0.83em;
    margin-block-end: 0.83em;display: block;"> Markdown </p>
<p style="font-family: 'Lato','PingFang SC','Microsoft YaHei', sans-serif;
    font-weight: bold;
    line-height: 1.5;
    margin: 20px 0 15px;font-size: 1em;padding-top: 10px;       display: block;
    margin-block-start: 1.67em;
    margin-block-end: 1.67em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;"> Markdown </p>

***

<hr style="background-color:#8FBC8F;height:4px;border:none;">

##### 字体处理：

``` bash
**Markdown**   加粗
*Markdown*     斜体
***Markdown*** 加粗斜体
```
***
**Markdown**
*Markdown*
***Markdown***
***

<hr style="background-color:#8FBC8F;height:4px;border:none;">


##### 排序：
```bash
有序排序
1.Markdown
2.Markdown
3.Markdown
```
***
1. Markdown
2. Markdown
3. Markdown

***

```bash
无序排序
- Markdown
+ Markdown
* Markdown
```
***
- Markdown
+ Markdown
* Markdown

***

<hr style="background-color:#8FBC8F;height:4px;border:none;">

##### 代码块：
注意大括号与百分号之间不能有空格，否则不显示.
```
{% codeblock [title] [lang:language] [url] [link text] %} {% endcodeblock %}
```

```bash
{% codeblock 测试代码 lang:python https://www.python.org/ Python %}
print(“hello world!”) 
{% endcodeblock %}
```
***

{% codeblock 测试代码 lang:python https://www.python.org/ Python %}
print(“hello world!”) 
{% endcodeblock %}

***
<hr style="background-color:#8FBC8F;height:4px;border:none;">

##### 笔记块：

```
{% note class_name %} {% endnote %}
```

```bash
{% note default %}
Markdown 
{% endnote %}

{% note primary %}
Markdown 
{% endnote %}

{% note success %}
Markdown 
{% endnote %}

{% note info %}
Markdown 
{% endnote %}

{% note warning %}
Markdown 
{% endnote %}

{% note danger %}
Markdown 
{% endnote %}
```
***

{% note default %}
Markdown 
{% endnote %}

{% note primary %}
Markdown 
{% endnote %}

{% note success %}
Markdown 
{% endnote %}

{% note info %}
Markdown 
{% endnote %}

{% note warning %}
Markdown 
{% endnote %}

{% note danger %}
Markdown 
{% endnote %}

***
<hr style="background-color:#8FBC8F;height:4px;border:none;">
