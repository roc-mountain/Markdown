# 编写整洁优雅的Markdown

[TOC]

## 前言

项目中经常有一个被人们忽略的文件:`README.md`，通常情况都是简单的两句，并没有深入的了解一下这个文件的编写规则，今天仔细的探究了一下，把学习结果记录下来，与大家共勉。

## 什么是Markdown

Markdown的目标是成为一种适用于网络的书写语言，实现「易读易写」。可读性，无论如何，都是最重要的。
一份使用 Markdown 格式撰写的文件应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。
Markdown 的语法受到一些既有 text-to-HTML 格式（包括 Setext、atx、Textile、reStructuredText、Grutatext 和 EtText）以及纯文本电子邮件的格式的影响，
全由一些符号所组成，这些符号经过精挑细选，其作用一目了然。
通常情况下，用 Markdown 语法编写的文件的后缀名为`.md`。

## Markdown编写工具

一般代码编辑器都是可以满足编写 Markdown 语法文件的，并且有预览的功能，
本人尝试的有：[sublime](https://www.sublimetext.com) 和 [VScode](https://code.visualstudio.com/)；
如果想要专业的Markdown编写工具，Mac系统推荐：[Mou](http://25.io/mou/)。Windows系统推荐：[MarkdownPad](http://www.markdownpad.com/)。

## Markdown语法

### 标题
  Markdown 支持两种标题的语法，类 Setext 和类 atx 形式。

* 第一种类 Setext 形式是用底线的形式，利用 = （最高级标题）和 - （第二级标题），任何数量的 = 和 - 都可以有效果。例：

![标题图1](./images/title-1.png)

* 第二种类 Atx 形式则是在行首插入 1 到 6 个 # ，对应到标题 1 到 6 级，最高6级。例：

![标题图2](./images/title-2.png)

你可以选择性地在类 atx 样式的标题行尾加上 #，
而行尾的 # 数量不用和开头一样（行首的井字符数量决定标题的级数）。例：

![标题图3](./images/title-3.png)

### 


## 注意事项

所有 Markdown 语法涉及到的符号，请在英文输入法下输入。
