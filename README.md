# C# 入门经典最新版

___

**本书**是在**GNU GPL V3协议**下发布的免费C#教程。您可以任意使用本书中的内容和源代码。有任何意见和建议欢迎与我直接交流。___联系邮箱___：_380921128@qq.com_ 。

---

#_以下为MarkDown语法_

[跳转到结尾](#结尾)
<a href="结尾" id="开始">跳转到结尾</a>

使用 [^footer] 表示注脚。


~~这是一条删除线~~


---
+ 标题：Setext方式
大标题
===
小标题
---

+ 标题：Atx方式
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

---

**无序列表**
+ 无序列表
    - 无序列表
        * 无序列表
        * 无序列表
    - 无序列表
+ 无序列表

>html 实现方法
<ul>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ul>


---

**有序列表**

1. 有序列表
2. 有序列表
3. 有序列表
8. 有序列表


>html 实现方法
<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>


---

**文字超链 inline方式**

这里是[转到百度](http://www.baidu.com "百度链接")

>**html实现**
<p>This is an <a href="http://www.baidu.com/"> 百度链接</a>.</p>
带有Title属性
<p>This is an <a href="http://www.baidu.com/" title="这里是百度链接的Title属性">
百度链接</a>.</p>

---

图片超链 
![GitHub Mark](http://github.global.ssl.fastly.net/images/modules/logos_page/GitHub-Mark.png "GitHub Mark")

>html实现
<img src="http://github.global.ssl.fastly.net/images/modules/logos_page/GitHub-Mark.png" alt="alt text" title="Title" />



---

索引超链 Reference方式

[此处是文字超链][1]
![图片超链][2]
[1]:http://www.baidu.com
[2]:http://github.global.ssl.fastly.net/images/modules/logos_page/Octocat.png

<!-- 注释： title 属性是选择性的，链接名称可以用字母、数字和空格，但是不分大小写： -->
>html实现
<p>I get 10 times more traffic from <a href="http://google.com/"
title="Google">Google</a> than from <a href="http://search.yahoo.com/"
title="Yahoo Search">Yahoo</a> or <a href="http://search.msn.com/"
title="MSN Search">MSN</a>.</p>


---

自动链接
<http://www.baidu.com>

---

**代码**
+ **行内代码**

在第一行后指定编程语言，也可以不指定

<!-- 0 -->

```javascript

string s = "Hello World";

Console.WriteLine(s);

```

+ **段落代码**

每行文字前加4个空格或者1个Tab

    string s = "Hello World";

    Console.WriteLine(s);

+ **hexo**

『% codeblock [title] [lang:language] [url] [link text] %』

 code snippet

『% endcodeblock %』

>html 实现代码段落
<ol>
<li><p>A list item.</p></li>
<li><p>With multiple paragraphs.</p></li>
<li><p>Another item in the list.</p></li>
</ol>


___


这里是 <!-- 注释 -->
**注释**

---

**转义字符**

> 
反斜杠 \\
反引号 \`
星号 \*
> 
下划线 \_
大括号 \{\}
中括号 \[\]
小括号 \(\)
> 
井号 \#
加号 \+
减号 \-
英文句号 \.
感叹号 \!

---

**其他**

文本中可直接用html标签，但是要前后加上**_空行_**。


---

**表格**

Markdown的扩展语法，hexo不支持


| *year* | *Temperature(low)* | *Temperature(high)* |
|-|:-:|-:|
| 1900 | 10 | 20 |
| 2000 | 100 | 2000 |
| 20000 | 1000 | 10000 |

>html 语法实现

<table>
    <tr>
        <td> <b>year</b> </td>
        <td> <b>Temperature(low)</b> </td>
        <td> <b>Temperature(high)</b> </td>
    </tr>
    <tr>
        <td> 1900 </td>
        <td> 10 </td>
        <td> 20 </td>
    </tr>
    <tr>
        <td> 2000 </td>
        <td> 100 </td>
        <td> 2000 </td>
    </tr>

    <tr>
        <td> 20000 </td>
        <td> 1000 </td>
        <td> 10000 </td>
    </tr>
</table>

---

**代码框**

只需要用两个 \` 把中间的代码包裹起来

`Hello World!`

Hello World!

Hello World!

Hello World!

Hello World!`

---

**跳转到C#简介**

<a href="开始" id="结尾">跳转到开始</a>
<!-- [点击跳转](#jump) -->


---

_**个人微信**_ 
* 请您备注来访目的😁

![](/assets/IMG_1858.JPG)




