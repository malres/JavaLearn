<!DOCTYPE html>
<html>
<head>
<title>笔记</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<style type="text/css">
/* GitHub stylesheet for MarkdownPad (http://markdownpad.com) */
/* Author: Nicolas Hery - http://nicolashery.com */
/* Version: b13fe65ca28d2e568c6ed5d7f06581183df8f2ff */
/* Source: https://github.com/nicolahery/markdownpad-github */

/* RESET
=============================================================================*/
#content_table{
	position:fixed;
	top:0%;
	right:0%;
	background-color:#fff;
	color:#be3131;
}
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
}

/* BODY
=============================================================================*/

body {
  font-family: Helvetica, arial, freesans, clean, sans-serif;
  font-size: 14px;
  line-height: 1.6;
  color: #333;
  background-color: #fff;
  padding: 20px;
  max-width: 960px;
  margin: 0 auto;
}

body>*:first-child {
  margin-top: 0 !important;
}

body>*:last-child {
  margin-bottom: 0 !important;
}

/* BLOCKS
=============================================================================*/

p, blockquote, ul, ol, dl, table, pre {
  margin: 15px 0;
}

/* HEADERS
=============================================================================*/

h1, h2, h3, h4, h5, h6 {
  margin: 20px 0 10px;
  padding: 0;
  font-weight: bold;
  -webkit-font-smoothing: antialiased;
}

h1 tt, h1 code, h2 tt, h2 code, h3 tt, h3 code, h4 tt, h4 code, h5 tt, h5 code, h6 tt, h6 code {
  font-size: inherit;
}

h1 {
  font-size: 28px;
  color: #000;
}

h2 {
  font-size: 24px;
  border-bottom: 1px solid #ccc;
  color: #000;
}

h3 {
  font-size: 18px;
}

h4 {
  font-size: 16px;
}

h5 {
  font-size: 14px;
}

h6 {
  color: #777;
  font-size: 14px;
}

body>h2:first-child, body>h1:first-child, body>h1:first-child+h2, body>h3:first-child, body>h4:first-child, body>h5:first-child, body>h6:first-child {
  margin-top: 0;
  padding-top: 0;
}

a:first-child h1, a:first-child h2, a:first-child h3, a:first-child h4, a:first-child h5, a:first-child h6 {
  margin-top: 0;
  padding-top: 0;
}

h1+p, h2+p, h3+p, h4+p, h5+p, h6+p {
  margin-top: 10px;
}

/* LINKS
=============================================================================*/

a {
  color: #4183C4;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* LISTS
=============================================================================*/

ul, ol {
  padding-left: 30px;
}

ul li > :first-child, 
ol li > :first-child, 
ul li ul:first-of-type, 
ol li ol:first-of-type, 
ul li ol:first-of-type, 
ol li ul:first-of-type {
  margin-top: 0px;
}

ul ul, ul ol, ol ol, ol ul {
  margin-bottom: 0;
}

dl {
  padding: 0;
}

dl dt {
  font-size: 14px;
  font-weight: bold;
  font-style: italic;
  padding: 0;
  margin: 15px 0 5px;
}

dl dt:first-child {
  padding: 0;
}

dl dt>:first-child {
  margin-top: 0px;
}

dl dt>:last-child {
  margin-bottom: 0px;
}

dl dd {
  margin: 0 0 15px;
  padding: 0 15px;
}

dl dd>:first-child {
  margin-top: 0px;
}

dl dd>:last-child {
  margin-bottom: 0px;
}

/* CODE
=============================================================================*/

pre, code, tt {
  font-size: 12px;
  font-family: Consolas, "Liberation Mono", Courier, monospace;
}

code, tt {
  margin: 0 0px;
  padding: 0px 0px;
  white-space: nowrap;
  border: 1px solid #eaeaea;
  background-color: #f8f8f8;
  border-radius: 3px;
}

pre>code {
  margin: 0;
  padding: 0;
  white-space: pre;
  border: none;
  background: transparent;
}

pre {
  background-color: #f8f8f8;
  border: 1px solid #ccc;
  font-size: 13px;
  line-height: 19px;
  overflow: auto;
  padding: 6px 10px;
  border-radius: 3px;
}

pre code, pre tt {
  background-color: transparent;
  border: none;
}

kbd {
    -moz-border-bottom-colors: none;
    -moz-border-left-colors: none;
    -moz-border-right-colors: none;
    -moz-border-top-colors: none;
    background-color: #DDDDDD;
    background-image: linear-gradient(#F1F1F1, #DDDDDD);
    background-repeat: repeat-x;
    border-color: #DDDDDD #CCCCCC #CCCCCC #DDDDDD;
    border-image: none;
    border-radius: 2px 2px 2px 2px;
    border-style: solid;
    border-width: 1px;
    font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;
    line-height: 10px;
    padding: 1px 4px;
}

/* QUOTES
=============================================================================*/

blockquote {
  border-left: 4px solid #DDD;
  padding: 0 15px;
  color: #777;
}

blockquote>:first-child {
  margin-top: 0px;
}

blockquote>:last-child {
  margin-bottom: 0px;
}

/* HORIZONTAL RULES
=============================================================================*/

hr {
  clear: both;
  margin: 15px 0;
  height: 0px;
  overflow: hidden;
  border: none;
  background: transparent;
  border-bottom: 4px solid #ddd;
  padding: 0;
}

/* TABLES
=============================================================================*/

table th {
  font-weight: bold;
}

table th, table td {
  border: 1px solid #ccc;
  padding: 6px 13px;
}

table tr {
  border-top: 1px solid #ccc;
  background-color: #fff;
}

table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

/* IMAGES
=============================================================================*/

img {
  max-width: 100%
}
</style>
<a href='video.jsp'>当天视频</a>
</head>
<body>
<h1>XML</h1>
<p>1-4,星期四 8:36:54 </p>
<hr />
<h3>XML</h3>
<h3>XML简介</h3>
<pre><code>XML指的是 　可扩展标记语言　．

XML 具有平台无关性, 是一门独立的标记语言 !
XML具有自我描述性 , 主要应用于数据的存储 与 网络的数据传输 !


我们以后常用于  web项目的配置, 框架阶段学习时, 框架的配置 !
</code></pre>

<h3>SE项目</h3>
<pre><code>题目#A#B#C#D


题目: 

    哈哈哈#哈哈哈
</code></pre>

<h3>XML语法</h3>
<pre><code>1.  XML文档文件声明

    在xml文件的第一行, 加入文档声明 , 描述当前XML版本 以及 文本的编码格式 !
    &lt;?xml version=&quot;1.0&quot; encoding=&quot;UTF-8&quot; ?&gt;

2.  节点 , 元素 , 标签 (指的是同一个东西)

    节点分为开始节点与结束节点 , 开始节点与结束节点之间是节点的内容!

    开始节点语法:&lt;节点名称&gt; 
    结束节点语法:&lt;/节点名称&gt;

    例如: 描述一个电话号: 
        &lt;tel&gt;18516955565&lt;/tel&gt;


3.  XML文档中的节点, 允许嵌套, 不允许交叉

    例如: 描述一个人的通讯方式: 

        &lt;comm&gt;
            &lt;tel&gt;18516955565&lt;/tel&gt;
            &lt;qq&gt;123456789&lt;/qq&gt;
        &lt;/comm&gt;

4.  XML文档, 必须存在且只允许存在一个根标签
    &lt;persons&gt;
        &lt;person&gt;
            &lt;name&gt;张大飞&lt;/name&gt;
            &lt;age&gt;18&lt;/age&gt;
        &lt;/person&gt;

        &lt;person&gt;
            &lt;name&gt;张二飞&lt;/name&gt;
            &lt;age&gt;14&lt;/age&gt;
        &lt;/person&gt;
    &lt;/persons&gt;

5.  XML文档属性 

    属性名与属性值之间使用英文等号连接 , 
    多个属性之间使用空格隔开
    属性值, 必须使用双引号引住

    格式: 

        &lt;开始标签 属性名1=&quot;属性值1&quot; 属性名2=&quot;属性值2&quot; ... n&gt;内容&lt;/结束标签&gt;

6.  注释
        多行注释: 

        &lt;!-- 注释部分 --&gt;
</code></pre>

<h3>XML文件案例:</h3>
<pre><code>&lt;?xml version=&quot;1.0&quot; encoding=&quot;UTF-8&quot; ?&gt;
&lt;person&gt;
    &lt;!-- zhe li shi xing ming  --&gt;
    &lt;name&gt;高飞&lt;/name&gt;
    &lt;age&gt;18&lt;/age&gt;
&lt;/person&gt;
</code></pre>

<h4>术语</h4>
<pre><code>1.  元素/节点/标签
    指的是同一个东西 !

2.  根节点: 
    在一个XML中, 范围最大的 , 最外部的节点, 指的就是根节点


3.  子节点/父节点
    子节点与父节点的概念 ,是相对的 !
    例如如下案例中, person是name与age节点的父节点 !
        反过来说, name与age是person的子节点
    &lt;person&gt;
        &lt;name&gt;高飞&lt;/name&gt;
        &lt;age&gt;18&lt;/age&gt;
    &lt;/person&gt;


4.  兄弟节点:
    两个节点, 拥有同一个直接父节点


5.  文本节点

    指的是XML标签中的纯文本

    例如:
        &lt;person&gt;
            &lt;name&gt;高天&lt;/name&gt;
            &lt;sex&gt;   &lt;/sex&gt;
            &lt;age&gt;18&lt;/age&gt;
        &lt;/person&gt;
    上面的案例中: 文本节点指的是: 

    高天,   ,18
</code></pre>

<h3>练习:</h3>
<pre><code>使用XML , 描述一个学生student , 拥有四个子节点

    -   school 学校
    -   name 姓名
    -   age 年龄
    -   id 学号

&lt;?xml version=&quot;1.0&quot; encoding=&quot;UTF-8&quot; ?&gt;
&lt;student&gt;
    &lt;school&gt;一本道精英学院&lt;/school&gt;
    &lt;name&gt;高飞&lt;/name&gt;
    &lt;age&gt;16&lt;/age&gt;
    &lt;id&gt;东京热07组1001号学员&lt;/id&gt;
&lt;/student&gt;
</code></pre>

<h3>XML的Java解析</h3>
<h3>面试题:</h3>
<pre><code>Java中有哪些XML的解析方式, 分别有什么优点和缺点

答: 

    Java中存在4种XML解析方式(或者回答2种)

    -   sax解析
        事件驱动机制 , 当解析器发现元素开始, 元素结束, 文本, 属性 等等时 , 发送事件, 通知程序员进行解析!

        事件驱动方式, 占用内存较低, 但是效率较差!

        优点:
            占用资源少
        缺点:
            效率差 , 文档解析时, 可读不可修改!


    -   dom解析
        将整个文件, 加载到内存, 建立文档树模型 !

        缺点:
            在解析时,  会将整个文档, 加载到内存, 可能存在一些无用节点,  浪费内存 和 时间!

        优点: 
            将整个文档在内存中建立了树模型, 可以很方便的对内容进行删除和修改 !

    -   JDOM解析
        -   属于DOM解析的封装
    -   DOM4J解析
        -   属于DOM解析的封装
</code></pre>

<h3>DOM4J解析流程</h3>
<pre><code>1.  引入dom4j.jar文件

2.  在代码中, 通过输入流, 指向XML文件
    一般情况下, XML文件, 建议存放在src目录下!

    InputStream is = Class.getClassLoader().getResourceAsStream(&quot;xxx.xml&quot;);

    注意: 
        以后在进行后台项目开发时, 客户端传递的数据, 一般情况下, 就在一个输入流中

3.  创建XML的读取对象(SAXReader) , 用来读取XML流!
    SAXReader sr = new SAXReader(); 

4.  通过读取对象的读取方法(read方法), 读取这个输入流! 并获取文档对象
    Document doc = sr.read(is);

5.  通过文档对象, 获取XML文档的根元素对象
    Element root = doc.getRootElement();

6.  通过Element的API 解析文件
</code></pre>

<h4>Element 常用方法</h4>
<pre><code>-   获取当前节点的子节点迭代器
    方法名:    elementIterator
    无参数列表, 返回Iterator&lt;Element&gt;

-   获取第一个匹配的直接子节点
    方法名: element
    参数列表: String tagName 
            tagName: 要获取的子节点名称
    返回值类型: Element

-   获取节点名称
    方法名:    getName
    无参数列表, 返回字符串,表示节点的名称 !

-   获取节点值
    方法名: getText
    无参数列表, 返回字符串, 表示节点的文本内容

-   设置节点值
    方法名: setText
    参数列表: String text
            text: 表示要设置的节点的值

-   获取属性对象
    方法名:    attribute
    参数列表: String 属性名称
    返回值:    Attribute 属性对象

-   获取属性值
    方法名:    attributeValue
    参数列表: String 属性名称
    返回值: String 属性值
</code></pre>

<h3>Attribute(属性) 常用方法</h3>
<pre><code>-   获取属性名称
    方法名: getName()
    无参数列表
    返回值: String name


-   获取属性值
    方法名: getValue()
    无参数列表
    返回值: String value
</code></pre>

<h3>XPATH 解析XML  ***</h3>
<pre><code>路径表达式:

1.  /   从根节点开始查找子节点

2.  //  从当前节点 查找子节点|间接子节点                       *****
3.  .   选择当前节点
4.  ..  选择当前节点的父节点
5.  @   选择属性    ***


使用XPATH路径表达式: 

需要借助Node类型对象 
(Node类型, 是一个接口, 是Attribute,Element,Document接口的父接口)

1.  一次查询匹配的多个节点
    方法名:selectNodes
    参数列表:   String 路径表达式
    返回值: List集合,泛型为Node


2.  一次查询匹配的第一个节点
    方法名:    selectSingleNode
    参数列表:   String 路径表达式
    返回值:Node node


//data//item//title : 找到菜的标题

//data//item//tags : 菜的描述
</code></pre>

<h3>XML的Java生成</h3>

</body>
</html>
<!-- This document was created with MarkdownPad, the Markdown editor for Windows (http://markdownpad.com) -->