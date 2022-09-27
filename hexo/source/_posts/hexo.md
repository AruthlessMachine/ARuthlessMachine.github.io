---
title: hexo
tags: hexo
categories: hexo
comments: true
date: 2022-09-27 18:55:47
updated: 2022-09-27 18:55:47
permalink:
---

# Hello Wrold Hexo 

##  [hexo 官方文档](https://hexo.io/docs/)


## 常用命令

```
$ hexo init [folder]

$ hexo new [layout] <title>

$ hexo generate

$ hexo publish [layout] <filename>

$ hexo server

$ hexo deploy

```

## 嵌入重要引述
{% pullquote  %}
内容
{% endpullquote %}

## 嵌入代码块
```
{% codeblock [title] [lang:language] [url] [link text] [additional options] %}
代码片段
{% endcodeblock %}

```

{% codeblock demo lang:javascript line_number:true line_threshold:3  %}

    function add (){

        return 1 + 1

    }

{% endcodeblock %}


## 嵌入Asset

<!-- <img src="2.png" width="100" height="200"/> -->
{% asset_path 2.png %} 
{% asset_link 2.png 2.png %}
{% asset_img 2.png 400 %}

## 嵌入视频

{% youtube WurwIqiqiXg  %}

<video  src="1.mp4" controls/>

## 嵌入iframe

{% iframe https://www.calculator.net/bmr-calculator.html?ctype=metric&cage=25&csex=m&cheightfeet=5&cheightinch=10&cpound=160&cheightmeter=180&ckg=85&cmop=0&coutunit=c&cformula=m&cfatpct=20&x=50&y=7 100% 400 %}

