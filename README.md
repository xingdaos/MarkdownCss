# Markdown CSS

## 目的

收集常用，好用的Markdown的CSS文件

## 文件简介

1. MyGitHub2.css

该文件来自liteide中预定义的CSS：GitHub2.css，我在其基础上添加了2-6级标题的序号，当使用`##`时，会自动在前面生成`1. `，下面是一个演示例子：

	# 文档名称，做了居中处理
	## 一级标题
	### 二级标题

生成后的效果：

			文档名称，做了居中处理
	1 一级标题
	1.1 二级标题


使用这个CSS，可以用来写word中带序号的标题文档了

## 原理

其实就是用到了CSS里面元素的before属性，可以在内容前面添加自定义的内容，另外还用到了conter计数器