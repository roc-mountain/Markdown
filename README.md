# 编写整洁优雅的Markdown
Markdown编写文档：[https://roc-mountain.github.io/Markdown/](https://roc-mountain.github.io/Markdown/ "Markdown编写文档")  
源码地址：[https://github.com/roc-mountain/Markdown](https://github.com/roc-mountain/Markdown "源码地址")  
在线体验：[https://roc-mountain.github.io/Markdown/editor.html](https://roc-mountain.github.io/Markdown/editor.html "在线体验")

## 1.目录

1. [目录](#1目录)
2. [前言](#2前言)
3. [什么是Markdown](#3什么是Markdown)
4. [Markdown编写工具](#4Markdown编写工具)
5. [Markdown语法](#5Markdown语法)
    * [5.1标题](#51-标题)
    * [5.2段落和换行](#52-段落和换行)
    * [5.3列表](#53-列表)
    * [5.4引用（注释）](#quote)
    * [5.5代码区块](#code)
    * [5.6分割线](#cutline)
    * [5.7强调](#mephasize)
    * [5.8链接](#link)
    * [5.9图片](#image)
    * [5.10符号](#symbol)
6. [注意事项](#6注意事项)
7. [参考](#7参考)

----

## 2.前言

项目中经常有一个被人们忽略的文件:`README.md`，通常情况都是简单的两句，并没有深入的了解一下这个文件的编写规则，今天仔细的探究了一下，把学习结果记录下来，与大家共勉。

## 3.什么是Markdown

Markdown的目标是成为一种适用于网络的书写语言，实现「易读易写」。可读性，无论如何，都是最重要的。   

一份使用 Markdown 格式撰写的文件应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。    

Markdown 的语法受到一些既有 text-to-HTML 格式（包括 Setext、atx、Textile、reStructuredText、Grutatext 和 EtText）以及纯文本电子邮件的格式的影响，全由一些符号所组成，这些符号经过精挑细选，其作用一目了然。   

Markdown 的写法兼容HTML。需要注意HTML标签的类型：在 HTML 区块（块元素）标签间的 Markdown 格式语法将不会被处理（如：div,table,p）。HTML 的区段（行内元素）标签(如：span,a,img)可以在 Markdown 的段落、列表或是标题里随意使用。如果比较喜欢 HTML 的 `<a>` 或 `<img>` 标签，可以直接使用这些标签，而不用 Markdown 提供的链接或是图像标签语法。  

通常情况下，用 Markdown 语法编写的文件的后缀名为`.md`。

## 4.Markdown编写工具

一般代码编辑器都是可以满足编写 Markdown 语法文件的，并且有预览的功能，
本人尝试的有：[sublime](https://www.sublimetext.com) 和 [VScode](https://code.visualstudio.com/)。    
如果想要专业的Markdown编写工具，Mac系统推荐：[Mou](http://25.io/mou/)。Windows系统推荐：[MarkdownPad](http://www.markdownpad.com/)。  
在线编辑体验：<a href="https://roc-mountain.github.io/Markdown/editor.html" target="_blank">Markdown在线编辑体验</a>

## 5.Markdown语法

### 5.1-标题
  Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。

* 第一种类 Setext 形式是用底线的形式，利用 = （最高级标题）和 - （第二级标题），任何数量的 = 和 - 都可以有效果。例：

  ![标题图1](./images/title-1.png)

* 第二种类 Atx 形式则是在行首插入 1 到 6 个 # ，对应到标题 1 到 6 级，最高6级。例：

  ![标题图2](./images/title-2.png)

  你可以选择性地在类 atx 样式的标题行尾加上 #，
  而行尾的 # 数量不用和开头一样（行首的井字符数量决定标题的级数）。例：

  ![标题图3](./images/title-3.png)

### 5.2-段落和换行

一个 Markdown 段落是由一个或多个连续的文本行组成，它的前后要有一个以上的空行（空行的定义是显示上看起来像是空的，便会被视为空行。比方说，若某一行只包含空格和制表符，则该行也会被视为空行）。Markdown 允许段落内的强迫换行（插入换行符），在换行处（插入处）先按入两个以上的空格然后按回车即可实现换行。（注：有些Markdown编辑器已经避免这个问题，需要换行的时候只需按入空格即可）

普通段落不该用空格或制表符来缩进。（空格缩进4个以上或一个制表符，会把缩进内容变为代码区块内容。详见：[5.5代码区块](#code-area)）

### 5.3-列表

 Markdown 的列表有两种：无序列表和有序列表。

- 无序列表：使用星号（*）、加号（+）或是减号（-）作为列表标记。列表标记符号在每一行的第一位（最多允许缩进3个空格），后面有至少一个空格。例：

  ![列表1](./images/list-1.png)

- 有序列表：数字接着一个英文句点(.)作为列表标记，任意数字开头加上英文句点都会形成有序列表。例：

  ![列表1](./images/list-2.png)

## 6.注意事项

所有 Markdown 语法涉及到的符号，请在英文输入法下输入。
## 7.参考

Markdown 语法说明（简体中文版）：[http://wowubuntu.com/markdown/](http://wowubuntu.com/markdown/)  
Markdown 语法说明（英文版）：[https://daringfireball.net/projects/markdown/syntax](https://daringfireball.net/projects/markdown/syntax)  
