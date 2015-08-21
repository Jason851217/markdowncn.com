# Markdown 语法

- 目录
    - [标题](#header)
    - [换行](#newline)
    - [加粗](#bold)
    - [列表](#list)
    - [添加图片](#image)
    - [添加超链接](#link)  
    - [引用](#blockquote)
    - [代码](#code)
    - [代码块](#code-block)
    - [表格](#table)
    - [免费编辑器](#editor)

<a name="header"></a>
## 标题

在标题内容前添加 `# + 空格` 就可以实现标题样式的添加：

- 一级标题就添加一个 `#` + 空格，例如：# 我是一级标题
- 二级标题就添加两个 `#` + 空格，例如：## 我是二级标题。

依次类推...

<a name="newline"></a>
## 换行

书写示例：

```
我是第一行（后面有两个空格）  
我是第二行
```

效果：  

我是第一行（后面有两个空格）  
我是第二行

<a name="bold"></a>
## 加粗

书写示例：

```
**我是粗体**
```

效果：  
**我是粗体** 

<a name="list"></a>
## 列表

### 一级列表（不带序号）

书写示例：

```
- 列表 1（减号 + 空格）
- 列表 2
```

效果：

- 列表 1（减号 + 空格）
- 列表 2

### 一级列表（带序号）

书写示例：

```
1. 列表 1（自然数 + 点 + 空格）
2. 列表 2
```

效果：

1. 列表 1（自然数 + 点 + 空格）
2. 列表 2

### 二级列表（不带序号）

书写示例：

```
- 列表 1（一级列表：减号 + 空格）
    - 列表 1.1（二级列表：四个空格 + 减号 + 空格）
    - 列表 1.2
- 列表 2
```

效果：

- 列表 1（一级列表：减号 + 空格）   
    - 列表 1.1（二级列表：四个空格 + 减号 + 空格）   
    - 列表 1.2   
- 列表 2

### 二级列表（带序号）

书写示例：

```
- 列表（一级列表：减号 + 空格）
    1. 列表（二级列表：四个空格 + 序号 + 点 + 空格）
    2. 列表
- 列表 2
```

效果：

- 列表 1（一级列表：减号 + 空格）  
    1. 列表（二级列表：四个空格 + 自然数 + 点 + 空格）  
    2. 列表
- 列表 2

<a name="image"></a>
## 添加图片

书写示例：

```
![图片描述性文字，非必填，比如：我是示例图片的描述](图片相对或绝对地址，比如：images/example.png)
```

效果：  

![我是示例图片的描述](images/example.png)    

<a name="link"></a>
## 添加超链接  

书写示例：

```
[链接描述文字，比如：点击跳转到极客学院)](链接地址，比如：http://www.jikexueyuan.com)
```

效果：  

[点击跳转到极客学院](http://www.jikexueyuan.com) 

<a name="blockquote"></a>
## 引用

书写示例：

```
>注意：  
我是引用的内容（空一行就结束引用）。
```

效果：
  
>注意：  
我是引用的内容（空一行就结束引用）。

<a name="code"></a>
## 代码

书写示例：

```
`请把我标亮`
```

效果：  

`请把我标亮` 

<a name="code-block"></a>
## 代码块

书写示例：

<pre>
```
// 代码区域的上下分别用三个 ` 括起来
public class Person {
    // 代码缩进请使用 四个空格，不要使用 Tab
}
```
</pre>

效果： 

```
// 代码区域的上下分别用三个 ` 括起来
public class Person {
    // 代码缩进请使用 四个空格，不要使用 Tab
}
```

<a name="table"></a>
## 表格

书写示例：

```
|Prefix  |Framework   |
|--------|------------|
|NS      |Foundation (OS X and iOS) and Application Kit (OS X)  |
|UI      |UIKit (iOS)  |
|AB      |Address Book  |
|CA      |Core Animation  |
|CI      |Core Image  |
```

效果： 

|Prefix  |Framework   |
|--------|------------|
|NS      |Foundation (OS X and iOS) and Application Kit (OS X)  |
|UI      |UIKit (iOS)  |
|AB      |Address Book  |
|CA      |Core Animation  |
|CI      |Core Image  |

<a name="editor"></a>
## 免费编辑器

### Windows 平台

MarkdownPad  
<http://markdownpad.com>


### Mac 平台

MacDown  
<http://macdown.uranusjr.com/>   

>注：
>不推荐 [Mou](http://25.io/mou)，原因 `文件大了超级卡`。 
