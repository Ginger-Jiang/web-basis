## CSS

- CSS 指层叠样式表 (Cascading Style Sheets)
- 样式定义如何显示 HTML 元素
- 样式通常存储在样式表中
- 把样式添加到 HTML 4.0 中，是为了解决内容与表现分离的问题
- 外部样式表可以极大提高工作效率
- 外部样式表通常存储在 CSS 文件中
- 多个样式定义可层叠为一

## 语法规范

CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明。

```css
selector {declaration1; declaration2; ... declarationN }
```

- 选择器通常是您需要改变样式的 HTML 元素。
- 每条声明由一个属性和一个值组成。
- 属性（property）是您希望设置的样式属性（style attribute）。每个属性有一个值。属性和值被冒号分开。

下面这行代码的作用是将 h1 元素内的文字颜色定义为红色，同时将字体大小设置为 14 像素。
在这个例子中，h1 是选择器，color 和 font-size 是属性，red 和 14px 是值。

```css
h1 {
  color: red;
  font-size: 14px;
}
```

### 值的不同写法和单位

```css
h1 {
  color: #fff;
  font-size: 14px;
}
p {
  color: rgb(255, 0, 0);
}
```

> 如果值为若干单词，则要给值加引号：

除了英文单词 red，我们还可以使用十六进制的颜色值 #ff0000：

![1](../../image/css/ct_css_selector.gif)

## CSS 代码风格

### 多重声明

如果要定义不止一个声明，则需要用分号将每个声明分开

```css
p {
  text-align: center;
  color: black;
  font-family: arial;
}
```

### 空格和大小写

- 推荐使用小写
- 推荐在选择器后保留一个空格
- 推荐在属性值前面, 冒号后面保留一个空格

大多数样式表包含不止一条规则，而大多数规则包含不止一个声明。多重声明和空格的使用使得样式表更容易被编辑：

```css
body {
  color: #000;
  background: #fff;
  margin: 0;
  padding: 0;
  font-family: Georgia, Palatino, serif;
}
```

> 是否包含空格不会影响 CSS 在浏览器的工作效果，同样，与 XHTML 不同，CSS 对大小写不敏感。不过存在一个例外：如果涉及到与 HTML 文档一起工作的话，class 和 id 名称对大小写是敏感的。
