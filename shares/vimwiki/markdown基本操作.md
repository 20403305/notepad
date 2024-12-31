- [返回主页](index)


- [1. 表格](#1-表格)
  - [类型1: Html格式](#类型1-html格式)
  - [类型2: Markdown格式](#类型2-markdown格式)
- [2. 图片](#2-图片)
  - [1. `![]url`：用于插入图片](#1-url用于插入图片)
  - [2. `[]url`：用于插入超链接](#2-url用于插入超链接)
  - [总结对比：](#总结对比)
  - [关键区别：](#关键区别)



## 1. 表格
### 类型1: Html格式
Markdown格式的表格举例
```HTML
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>表格</title>
</head>
<body>
    <table border="1">
        <tr>
            <th>姓名</th>
            <th>年龄</th>
            <th>性别</th>
        </tr>
        <tr>
            <td>张三</td>
            <td>20</td>
            <td>男</td>
        </tr>
        <tr>
            <td>李四</td>
            <td>21</td>
            <td>女</td>
        </tr>
    </table>
```

### 类型2: Markdown格式
表格举例
| 姓名 | 年龄 | 性别 |
| ---- | ---- | ---- |
| 张三 | 20   | 男   |
| 李四 | 21   | 女   |


## 2. 图片
在 Markdown 格式中，`![]url` 和 `[]url` 有很大的区别，它们分别用于不同的目的。

### 1. `![]url`：用于插入图片
这个语法用于插入图片。

- **语法**：`![Alt text](URL)`
- **解释**：`!` 表示这是一个图片，`[]` 中通常是图片的替代文本（alt text），`()` 中是图片的 URL。
- **示例**：
  ```markdown
  ![This is an image](https://example.com/image.jpg)
  ```
  这个 Markdown 会被渲染为：
  ![This is an image](https://example.com/image.jpg)

- **功能**：在最终渲染时，这会显示一个图片。`Alt text` 是当图片无法加载时显示的文本，或者当用户用屏幕阅读器时提供的描述。

### 2. `[]url`：用于插入超链接
这个语法用于创建一个超链接。

- **语法**：`[Link text](URL)`
- **解释**：`[]` 中包含的是链接的文本，`()` 中是链接的目标 URL。
- **示例**：
  ```markdown
  [Click here](https://example.com)
  ```
  这个 Markdown 会被渲染为：
  [Click here](https://example.com)

- **功能**：在最终渲染时，这会生成一个超链接，用户点击这个链接时会跳转到指定的 URL。

### 总结对比：
| 语法     | 功能       |         示例          |               渲染结果 |
| -------- | :--------- | :-------------------: | ---------------------: |
| `![]url` | 插入图片   | `![Image](image.jpg)` |               显示图片 |
| `[]url`  | 创建超链接 | `[Link](https://...)` | 创建一个可点击的超链接 |

### 关键区别：
- **插入图片**：使用 `![]`，并且 URL 是图片的地址。
- **插入链接**：使用 `[]`，并且 URL 是目标网页的地址。

这两种语法在 Markdown 中各自用于不同的目的：`![]` 处理图片，`[]` 处理文本链接。


# 本文标签
:vscode:
:markdown:
