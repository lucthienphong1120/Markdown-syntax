# Giới thiệu

Đã có ai dùng **GitHub** bao lâu nay vẫn không biết các tệp với đuôi mở rộng .md là gì không?

**Markdown** là ngôn ngữ đánh dấu được John Gruber tạo ra vào năm 2004. **Markdown** sử dụng cú pháp khá đơn giản và dễ hiểu để đánh dấu văn bản, tạo thuận tiện cho việc chuyển đổi từ văn bản thuần sang **HTML**.

Thay vì dựa vào **HTML**, **Markdown** cho phép bạn định dạng văn bản mà trực quan hơn nhiều so với **HTML**.

Có thể bạn chưa biết: **Markdown** được sử dụng tại **Github** và **Discord**.

> Tài liệu được viết tay bởi [Lục Thiên Phong](https://github.com/lucthienphong1120), để giúp bạn có thêm hiểu biết và làm chủ về Markdown.

# Tóm tắt

- [Sơ lược](#sơ-lược)
  - [MarkDown (Markup languages)](#markdown-markup-languages)
  - [Một số trình soạn thảo dành cho Markdown](#một-số-trình-soạn-thảo-dành-cho-markdown)
- [Cách sử dụng](#cách-sử-dụng)
  - [Tiêu đề - Heading](#tiêu-đề---heading)
  - [Đoạn văn - Paragraph](#đoạn-văn---paragraph)
  - [Chữ in đậm - Bold](#chữ-in-đậm---bold)
  - [Chữ in nghiêng - Italic](#chữ-in-nghiêng---italic)
  - [In đậm và in nghiêng](#in-đậm-và-in-nghiêng)
  - [Chữ gạch giữa - Strikethrough](#chữ-gạch-giữa---strikethrough)
  - [Trích dẫn - Blockquote](#trích-dẫn---blockquote)
  - [Danh sách có thứ tự - Ordered List](#danh-sách-có-thứ-tự---ordered-list)
  - [Danh sách không có thứ tự - Unordered List](#danh-sách-không-có-thứ-tự---unordered-list)
  - [Đường kẻ ngang - Horizonal rules](#đường-kẻ-ngang---horizonal-rules)
  - [Code trong dòng - Inline Code](#code-trong-dòng---inline-code)
  - [Khối lệnh - Block Code](#khối-lệnh---block-code)
  - [Liên kết - Link](#liên-kết---link)
  - [Hình ảnh - Image](#hình-ảnh---image)
  - [Escape markdown](#escape-markdown)
  - [Bảng - Table](#bảng---table)
- [Kết thúc](#kết-thúc)

# Sơ lược

## MarkDown (Markup languages)

Sự thật là cái tên **"Markdown"** chính là một phép chơi chữ của từ **"Markup"**.

Mardown được sử dụng để xuất văn bản thô trên trình duyệt nhưng các ngôn ngữ đánh dấu khác lại có thể giao tiếp trực tiếp với máy tính. Đơn cử như `XML` là một ngôn ngữ đánh dấu văn bản mà cả con người lẫn máy móc có thể đọc được.

Một ngôn ngữ đánh dấu văn bản khác mà mọi người chắc hẳn ai học CNTT cũng biết vì độ nổi tiếng của nó, chính là `HTML`, `Markdown` không mang trong mình sứ mệnh "Kẻ huỷ diệt HTML" hay gì, mà mục đích của nó chính là làm đơn giản hoá việc đánh dấu văn bản và tăng cường tốc độ viết lách một cách đáng kể.

## Một số trình soạn thảo dành cho Markdown

- Mac, Windows, và Linux
  - [Typora](https://typora.io/)
  - [MacDown](https://macdown.uranusjr.com/)
- Online
  - [Dillinger](https://dillinger.io/)
  - [Hashify](https://hashify.me/)

# Cách sử dụng

## Tiêu đề - Heading

Bạn có thể viết loại tiêu đề `<h1>, <h2>,... <h6>` bằng cách thêm các dấu # tương ứng vào đầu dòng.

Một dấu # tương đương với `<h1>`, hai dấu # tương đương với `<h2>` ...

Cú pháp:
```
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
```
Kết quả:

# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6

## Đoạn văn - Paragraph

Để xuống dòng giữa các văn bản `<p>`, sử dụng một dòng trống để tách các dòng văn bản.

Cú pháp:
```
Đây là dòng 1

Đây là dòng 2
```
Kết quả:

Đây là dòng 1

Đây là dòng 2

## Chữ in đậm - Bold

Để in đậm văn bản `<b>`, thêm hai dấu * hoặc dấu _ trước và sau từ cần in đậm.

Cú pháp:
```
**Từ cần in đậm 1**

__Từ cần in đậm 2__
```
Kết quả:

**Từ cần in đậm 1**

__Từ cần in đậm 2__

## Chữ in nghiêng - Italic

Để in nghiêng văn bản `<i>`, thêm một dấu * hoặc dấu _ trước và sau từ cần in nghiêng.

Cú pháp:
```
*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_
```
Kết quả:

*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_

## In đậm và in nghiêng

Đơn giản, bạn chỉ cần ba dấu * hoặc dấu _ trước và sau từ đó.

Cú pháp:
```
***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___
```
Kết quả:

***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___

## Chữ gạch giữa - Strikethrough

Để tạo chữ gạch giữa, thêm 2 dấu ~ trước và sau từ đó.

Cú pháp:
```
~~Khuyến mại~~
```
Kết quả:

~~Khuyến mại~~


## Trích dẫn - Blockquote

Để tạo một blockquote, thêm dấu > vào trước mỗi dòng trích dẫn.

Cú pháp:
```
> Trích dẫn dòng 1
> Trích dẫn dòng 2
```
Kết quả:

> Trích dẫn dòng 1
> Trích dẫn dòng 2

## Danh sách có thứ tự - Ordered List

Để tạo danh sách `<ol><li>`, bạn chỉ cần thêm các số, dấu chấm trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba
```
Kết quả:

1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba

## Danh sách không có thứ tự - Unordered List

Để tạo danh sách `<ul><li>`, bạn chỉ cần thêm dấu * hoặc - hoặc + trước nội dung (dùng tab để phân cấp)

Cú pháp:
```
- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba
```
Kết quả:

- Mục thứ nhất
- Mục thứ hai
- Mục thứ ba

## Đường kẻ ngang - Horizonal rules

Để tạo đường kẻ ngang, sử dụng ba dấu * hoặc - hoặc _ trên một dòng.

Cú pháp:
```
---
***
___
```
Kết quả:

---
***
___

## Code trong dòng - Inline Code

Để viết inline code, bạn dùng 2 dấu ` ở trước và sau từ đó.

Cú pháp:
```
`inline code`
```
Kết quả:

`inline code`

## Khối lệnh - Block Code

Để viết 1 đoạn `code`, bạn dùng 3 dấu ` ở trước và sau đoạn đó (có thể thêm format ngôn ngữ đó).

Cú pháp:

![image](https://user-images.githubusercontent.com/90561566/160242871-aad90ad1-bd8d-4e5c-9146-3349fb7c8c98.png)

Kết quả:

```python
print("hello world")
```

## Liên kết - Link

Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn liên kết `<a href="https://github.com">Github</a>`, bạn dùng `[text](link)`.

Cú pháp:
```
Trực tiếp: https://github.com/lucthienphong1120

Gián tiếp: [Github](https://github.com/lucthienphong1120)
```
Kết quả:

Trực tiếp: https://github.com/lucthienphong1120

Gián tiếp: [Github](https://github.com/lucthienphong1120)

## Hình ảnh - Image

Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn ảnh `<img src="https://avatars.githubusercontent.com/u/583231 alt="Github">`, bạn dùng `![text](link ảnh)`.

Hoặc `![](link ảnh)` nếu không cần chữ khi hover.

Cú pháp:
```
![](https://avatars.githubusercontent.com/u/583231)
```
Kết quả:

![](https://avatars.githubusercontent.com/u/583231)

Để chèn liên kết vào ảnh `<a href="link"><img src="link ảnh" alt="chữ"></a>` thì chỉ cần kết hợp đúng cú pháp là được.

```
[ ![chữ](link ảnh) ] (link)
```

## Escape markdown

Đôi khi bạn sẽ cần những kí hiệu trùng với cú pháp của markdown. Để phân biệt, bạn chỉ cần thêm dấu \ trước những kí hiệu đó là được.

Cú pháp:
```
\`hai dấu nháy\`

\*\*\*ba dấu sao hai bên\*\*\*
```
Kết quả:

\`hai dấu nháy\`

\*\*\*ba dấu sao hai bên\*\*\*

## Bảng - Table

Để tạo bảng `<table>`, dùng cách sau

Cú pháp:
```
| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |
```
Kết quả

| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |

# Kết thúc

Hy vọng qua bài viết này, bạn sẽ không còn thấy Markdown khó nữa và sẽ nắm được cách dùng Markdown trong nhiều việc của mình hơn nhé.

Nếu thấy hay hãy đừng ngần ngại mà thả 1 sao cho tôi, chúc bạn 1 ngày làm việc thật tốt!

> Bạn có thể thoải mái đóng góp (contribute) hoặc liên kết (fork) dự án này.

> You are free to contribute or fork this repo.
