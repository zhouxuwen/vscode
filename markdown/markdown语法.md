# markdown语法

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

* [markdown语法](#markdown语法)
	* [基本语法说明](#基本语法说明)
		* [标题](#标题)
		* [强调](#强调)
		* [列表](#列表)
			* [有序列表](#有序列表)
			* [无序列表](#无序列表)
		* [添加图片](#添加图片)
		* [链接](#链接)
		* [引用](#引用)
		* [分割线](#分割线)
		* [行内代码](#行内代码)
		* [代码块](#代码块)
			* [语法高亮](#语法高亮)
		* [任务列表](#任务列表)
		* [表格](#表格)
	* [扩展语法](#扩展语法)
		* [特殊符号](#特殊符号)

<!-- /code_chunk_output -->

## 基本语法说明

### 标题

```markdown
# 这是 <h1> 一级标题
## 这是 <h2> 二级标题
### 这是 <h3> 三级标题
#### 这是 <h4> 四级标题
##### 这是 <h5> 五级标题
###### 这是 <h6> 六级标题
```

### 强调

```markdown
*这会是 斜体 的文字*
_这会是 斜体 的文字_

**这会是 粗体 的文字**
__这会是 粗体 的文字__

_你也 **组合** 这些符号_

~~这个文字将会被横线删除~~
```


### 列表

#### 有序列表

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

#### 无序列表

```markdown
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

### 添加图片

```markdown
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

![GitHub Logo](/images/logo.png)
Dog: ![Alt Text](image/timg.jpg)

### 链接

```markdown
http://github.com - 自动生成！
[GitHub](http://github.com)
```

http://github.com - 自动生成！
[GitHub](http://github.com)

### 引用

```markdown
正如 Kanye West 所说：

> We're living the future so
> the present is our past.
```

正如 Kanye West 所说：

> We're living the future so
> the present is our past.

### 分割线

如下，三个或者更多的

```markdown
---
***
___
```

---

### 行内代码

```markdown
我觉得你应该在这里使用
`<addr>` 才对。
```

我觉得`printf();`

### 代码块

```markdown
    ```[语法类型]
    ```
```

#### 语法高亮

你可以给你的代码块添加任何一种语言的语法高亮

例如，给 ruby 代码添加语法高亮：

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```c
#include<stdio.h>
int main() {
    printf("hello world!");
    return 0;
}
```

### 任务列表

- [x] @mentions, #refs, [links](www.baidu.com), **formatting**, and ~~tags~~ supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### 表格

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

```markdown
first|second
-----|------
cell 1|cell 2
```

## 扩展语法

---

### 特殊符号

Emoji&Font-Amesome、上标、下标、角标、缩略。

```markdown
:smile:
:fa-car:
30^th^
H~2~O

==mark==

Content [^1]
[^1]: Hi! This is a footnote

The HTML specification
is maintained by the W3C.
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

```

:smile:
:fa-car:

[所有Emoji在这里
](https://www.webfx.com/tools/emoji-cheat-sheet/)

30^th^
H~2~O

==mark==

Content [^1]
[^1]: Hi! This is a footnote

The HTML specification
is maintained by the W3C.
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->
