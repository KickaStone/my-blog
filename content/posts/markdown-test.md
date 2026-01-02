+++
date = '2026-01-03T05:10:00+08:00'
draft = false
title = 'Markdown 语法测试'
+++

这篇文章测试所有 Markdown 语法的渲染效果。

## 标题 Headings

# H1 一级标题
## H2 二级标题
### H3 三级标题
#### H4 四级标题
##### H5 五级标题
###### H6 六级标题

---

## 文本样式 Text Styles

这是普通文本。

**这是粗体文本** 或者 __这也是粗体__

*这是斜体文本* 或者 _这也是斜体_

***这是粗斜体*** 或者 ___这也是粗斜体___

~~这是删除线文本~~

这是 `行内代码` 的效果

上标: X<sup>2</sup> 下标: H<sub>2</sub>O

---

## 引用 Blockquotes

> 这是一段引用文字。
> 可以跨多行。

> 嵌套引用
>> 第二层引用
>>> 第三层引用

---

## 列表 Lists

### 无序列表

- 项目一
- 项目二
  - 子项目 2.1
  - 子项目 2.2
    - 子子项目
- 项目三

### 有序列表

1. 第一项
2. 第二项
   1. 子项目 2.1
   2. 子项目 2.2
3. 第三项

### 任务列表

- [x] 已完成任务
- [x] 另一个完成的任务
- [ ] 未完成任务
- [ ] 还有一个未完成的

---

## 链接 Links

[普通链接](https://www.google.com)

[带标题的链接](https://www.google.com "Google 首页")

自动链接: https://www.github.com

邮箱链接: <example@email.com>

[引用式链接][ref-link]

[ref-link]: https://www.example.com "引用式链接示例"

---

## 图片 Images

![Alt 文字](https://via.placeholder.com/400x200 "图片标题")

带链接的图片:
[![图片](https://via.placeholder.com/200x100)](https://www.example.com)

---

## 代码 Code

### 行内代码

使用 `console.log()` 来调试 JavaScript。

### 代码块

```javascript
// JavaScript 示例
function greet(name) {
    console.log(`Hello, ${name}!`);
    return {
        message: "Welcome",
        timestamp: new Date()
    };
}

greet("World");
```

```python
# Python 示例
def fibonacci(n):
    """计算斐波那契数列"""
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

for i in range(10):
    print(fibonacci(i), end=" ")
```

```go
// Go 示例
package main

import "fmt"

func main() {
    message := "Hello, Hugo!"
    fmt.Println(message)
}
```

```bash
# Shell 命令
hugo new content posts/new-post.md
hugo serve -D
```

```css
/* CSS 示例 */
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

---

## 表格 Tables

| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:--------:|-------:|
| 单元格 | 单元格 | 单元格 |
| 左 | 中 | 右 |
| 数据 | 数据 | 数据 |

更复杂的表格:

| 功能 | Hugo | Jekyll | Hexo |
|------|:----:|:------:|:----:|
| 速度 | ⚡ 极快 | 🐢 慢 | 🚀 快 |
| 语言 | Go | Ruby | Node.js |
| 模板 | Go Templates | Liquid | EJS/Pug |
| 学习曲线 | 中等 | 简单 | 简单 |

---

## 水平分割线

使用三个或更多的 `-` `*` `_`

---

***

___

---

## 脚注 Footnotes

这是一段带脚注的文字[^1]。

这里还有另一个脚注[^note]。

[^1]: 这是脚注的内容。
[^note]: 这是第二个脚注，可以写得更长一些，包含多行内容。

---

## 数学公式 Math (如果主题支持)

行内公式: $E = mc^2$

块级公式:

$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

---

## HTML 嵌入

<details>
<summary>点击展开/折叠</summary>

这是被折叠的内容。

- 项目 1
- 项目 2
- 项目 3

</details>

<kbd>Ctrl</kbd> + <kbd>C</kbd> 复制

<mark>高亮文本</mark>

---

## Emoji 表情 (如果支持)

:smile: :heart: :thumbsup: :rocket: :coffee:

或者直接使用 Unicode: 😀 ❤️ 👍 🚀 ☕

---

## 定义列表

术语一
: 这是术语一的定义。

术语二
: 这是术语二的定义。
: 术语可以有多个定义。

---

## 缩写

HTML 规范由 W3C 维护。

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium

---

## 总结

这篇文章涵盖了大部分常用的 Markdown 语法：

1. ✅ 标题 (H1-H6)
2. ✅ 文本样式 (粗体、斜体、删除线)
3. ✅ 引用
4. ✅ 列表 (有序、无序、任务)
5. ✅ 链接和图片
6. ✅ 代码块 (多种语言)
7. ✅ 表格
8. ✅ 分割线
9. ✅ 脚注
10. ✅ 数学公式
11. ✅ HTML 嵌入
12. ✅ Emoji

祝你写作愉快！ 🎉

