# 中文GitHub Markdown语法入门

# 目录

[1.目录链接](#1目录链接)

[2.常用字体](#2常用字体)

[3.表格](#3表格)

[4.各种分段](#4各种分段)

[5.插入超链接](#5插入超链接)

[6.插入图片](#6插入图片)

## 1.目录链接

如果我们要在md文档内制作一个目录，并使这个目录是可以跳转到页面内标题的，其语法（请切换至Blame视图下查看语法）如下：

### 假如这是一个目录

[1.这个标题里有中文，有English，还有标点。](#这个标题里有中文有-English还有标点)

[2.与项目相关的 Non-apache.org 域名](#与项目相关的-non-apacheorg-域名)

[3.项目网站和 URL 原则：使用 * .apache.org](#项目网站和-url-原则使用--apacheorg)

---

#### 这个标题里有中文，有 English，还有标点。
#### 与项目相关的 NON-APACHE.ORG 域名
#### 项目网站和 URL 原则：使用 * .apache.org

我们看到，[]里内容与标题一致，而（）里内容则将标题中的所有标点（“-”保留）都删去，而把所有空格都换成“-”，其余保持不变。

其实最简单的方法是，在preview视图下，复制标题的链接：

<img width="536" alt="Screen Shot 2020-12-12 at 12 34 08 AM" src="https://user-images.githubusercontent.com/69114052/101929804-48990d80-3c12-11eb-8eff-83d7dbbb946e.png">

然后再回到edit视图中，把复制内容粘贴到（）中，将前面的网址删去即可：
<img width="1139" alt="Screen Shot 2020-12-12 at 12 35 01 AM" src="https://user-images.githubusercontent.com/69114052/101929703-2901e500-3c12-11eb-853b-d80d123a28c5.png">

## 2.常用字体

常有字体语法主要就是**粗体**和*斜体*（请切换至Blame视图下查看语法）

## 3.表格

用“|”与“-”即可制作表格（请切换至Blame视图下查看语法）

|第一行|是表头|
|---|---|
|第二行的“-”至少有三个||
|“-”在表格中只用出现一次|如第三行那样空着也是可以的|

## 4.各种分段

分段很简单，主要就用到井号、星号以及空格（请切换至Blame视图下查看语法）

### 比如这是一个标题
* 然后加星号写一个重点
  * 至少空两格就成了一个小重点
   
> 或者这样加>变为缩进
>> 加两个就再缩

    如果要变成这样类似引用的格式就要至少空四格，而且还要空行
    
    
## 5.插入超链接

插入超链接的基本操作是，我们首先用[]把想插入超链接的文字扩起来，然后再后面加上()，括号里填入超链接。比如这样：[点此回到此页面](https://github.com/JesseZhou-1/Markdown-Grammar-Instruction/blob/main/README.md)。（请切换至Blame视图下查看语法）

## 6.插入图片

想要插入图片的具体操作是首先把图片拖到你个人仓库的一个随便建的issue的comments里：
<img width="891" alt="Screen Shot 2020-12-11 at 12 39 54 AM" src="https://user-images.githubusercontent.com/69114052/101801609-7f572100-3b49-11eb-8e22-361e6236d338.png">

然后把生成的内容复制之后贴过来就可以了：
<img width="910" alt="Screen Shot 2020-12-11 at 12 44 45 AM" src="https://user-images.githubusercontent.com/69114052/101802151-1623dd80-3b4a-11eb-82c0-bca8cabb356e.png">

上面的两张图片就是这么插入的（请切换至Blame视图下查看语法）
