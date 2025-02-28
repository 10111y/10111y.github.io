# 3. HTML标签

HTML标签是构建网页内容的**基本单位**，HTML 使用各种标签（也叫元素）来定义页面的结构和内容。每个 HTML 标签通常都有**起始标签**和**结束标签**，其称之为双标签。一些没有结束标签的称之为单标签。此外，标签通常还包括**内容**和**属性**。

## 3.1 双标签

例如：

```html
<div>hello,world!</div>
```

- `<div>`：起始标签（又称为开标签），是 HTML 元素的开始部分，用来标识一个 HTML 元素的开始。它通常由一个左尖括号 <、元素名称和右尖括号 > 组成。
- `hello,world!`：标签体（也叫做元素体）是指 HTML 元素中的**内容部分**，位于起始标签（开标签）和结束标签（闭标签）之间。
- `</div>`：结束标签（又称为闭标签）用于标识一个元素的结束。结束标签与起始标签（开标签）配对使用，用于明确指定 HTML 元素的范围。

此外，标签不区分大小写，例如以下写法均正确，但是建议小写。

```html
<DIV>hello,world!</DIV>
<DIV>hello,world!</div>
<Div>hello,world!</dIV>
```

## 3.2 单标签

例如：

```html
<input>
<!-- or -->
<input/>
```

单标签无标签体，单标签两种表示方法，第二种中末尾的斜杠` / `是用来表示 **自闭合标签** 的写法，表示标签的自结束。

## 3.3 标签嵌套

例如：

```html preview
<div>
	hello,world!
	<input>
</div>
<br>
<input>
```

`<div>`标签与第三行的`<input>`标签属于嵌套关系，与第六行的`<input>`标签属于并列关系。 