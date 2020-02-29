## 什么是 HTML

HTML 是用来描述网页的一种语言

    - HTML 指的是超文本标记语言(Hyper Markuo Language)
    - HTMl 是一种标记语言
    - 标记语言是一套标记标签
    - HTML 使用标记标签来描述网页

### W3C 简介

    万维网联盟（英语：World Wide Web Consortium，缩写W3C），又称W3C理事会，是万维网的主要国际标准组织[2]。为半自治非政府组织（quasi-autonomous non-governmental organisation）。

### MDN 简介

    MDN Web Docs（旧称Mozilla Developer Network、Mozilla Developer Center，简称MDN）是一个汇集众多Mozilla基金会产品和网络技术开发文档的免费网站[1]。

## HTMl 标签

HTML 标记标签通常被称为 HTMl 标签

    - HTML 标签是由**尖括号**包围的关键词
    - HTML 标签通常是**成对**出现的
    - 标签对中的第一个标签是**开始标签**, 第二个标签是**结束标签**
    - 开始和结束标签也被称为**开放标签**和**闭合标签**

## HTML 文档 = 网页

    - HTML 文档**描述网页**
    - HTML 文档**包含 HTML 标签** 和纯文本
    - HTML 文档也被称为**网页**

## 例子

Web 浏览器的作用是读取 HTML 文档, 并以网页的形式显示出他们. 浏览器不会显示 HTML 标签, 而是使用标签来解释页面的内容

    ```html
    <html>
      <body>
        <h1>
          第一个标签
        </h1>
        <p>段落</p>
      </body>
    </html>
    ```

## 例子解释

    - `<html>` 与 `</html>` 之间的文本描述网页
    - `<body>` 与 `</body>` 之间的文本是可见的页面内容
    - `<h1>` 与 `<h1>` 之间的文本被显示为标题
    - `<p>` 与 `</p>` 之间的文本被显示为段落
