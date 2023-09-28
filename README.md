# MARKDOWN FILE

Định dạng tệp . MD (markdown) là định dạng tệp văn bản đơn giản để tạo và hiển thị nội dung của các tài liệu có cấu trúc,
sắp xếp dễ đọc hơn và rõ ràng hơn. Định dạng này được phát triển bởi John Gruber vào năm 2004 nhờ kết hợp giữa các nguyên
tắc đơn giản của định dạng văn bản và mã code HTML.

## Một số quy tắc cơ bản

- [Headings](#headings)
- [Styling text](#styling-text)
- [Quoting text](#quoting-text)
- [Quoting code](#quoting-code)
- [Links](#links)
- [Section links](#section-links)
- [Relative links](#relative-links)
- [Images](#images)
- [Lists](#lists)
- [Task lists](#task-lists)
- [Footnotes](#footnotes)
- [Hiding content with comments](#hiding-content-with-comments)
- [Ignoring Markdown formatting](#ignoring-markdown-formatting)

## Headings

Để viết được **tiêu đề** ta chỉ cần viết kí tự `#` phía trước tiêu đề. Cấp của tiêu đề sẽ từ 1-6 tương ứng với số lượng kí tự `#`.

``` markdown
# A first-level heading
## A second-level heading
### A third-level heading
```

## Styling text

Styling text là viết các đoạn văn bản dướng dạng đặc biệt như: in đậm, in nghiêng, gạch bỏ, ...
Các styling text thường dùng:

| Style                     | Syntax                | Example                       | Output            |
|        :----              |  :----:               |  :----:                       | ----:             |
|In đậm                     | `** **` hoặc `__ __`  | `**Hello**` hoặc `__Hello__`  | **Hello**         |
|In nghiêng                 | `* *` hoặc `_ _`      | `*Hello*` hoặc `_Hello_`      | *Hello*           |
|Gạch nghang                | `~~ ~~`               | `~~Hello~~`                   | ~~Hello~~         |
|Đậm và nghiêng lồng nhau   | `** **` và `_ _`      | `**Hello _World_**`           | **Hello *World*** |
|Đậm và nghiêng toàn bộ     | `*** ***`             | `***Hello World***`           | ***Hello World*** |
|Chỉ số trên                | `<sup> </sup>`        | `2<sup>2</sup>`               | 2< sup>2</sup>    |
|Chỉ số                     | `<sub> </sub>`        | `2<sub>2</sub>`               | 2< sub>2</sub>    |

## Quoting text

Để dẫn trích một đoạn văn bản hoặc một câu nói, ta sử dụng kí tự `>` trược đoạn văn bản. </br>
Ví dụ:
Một vị ông áo đỏ nào đó đã từng nói:
> Muốn thành công thì phải trải qua đắng cay ngọt bùi, ..., phải có làm thì mới có ăn ...

## Quoting code

Dùng để hiển thị 1 đoạn code. Sử dụng kí hiệu cặp ```. </br>

Ví dụ:

```markdown
a = 1
b = 2
print(a+b)
```

## Links

Ta có thể tạo đường dẫn cho 1 đoạn text bằng cách bỏ đoạn text vào ngoặc `[]` và đường link để vào dấu ngoặc `()`. </br>
Ví dụ:</br>

```markdown
Những năm gần đây, [AI - Artificial Intelligence (Trí Tuệ Nhân Tạo)](https://vi.wikipedia.org/wiki/Tr%C3%AD_tu%E1%BB%87_nh%C3%A2n_t%E1%BA%A1o), và cụ thể hơn là Machine Learning (Học Máy hoặc Máy Học) nổi lên như một bằng chứng của cuộc cách mạng công nghiệp lần thứ tư (1 - động cơ hơi nước, 2 - năng lượng điện, 3 - công nghệ thông tin). Trí Tuệ Nhân Tạo đang len lỏi vào mọi lĩnh vực trong đời sống mà có thể chúng ta không nhận ra.
```

Kết quả:</br>
Những năm gần đây, [AI - Artificial Intelligence (Trí Tuệ Nhân Tạo)](https://vi.wikipedia.org/wiki/Tr%C3%AD_tu%E1%BB%87_nh%C3%A2n_t%E1%BA%A1o), và cụ thể hơn là Machine Learning (Học Máy hoặc Máy Học) nổi lên như một bằng chứng của cuộc cách mạng công nghiệp lần thứ tư (1 - động cơ hơi nước, 2 - năng lượng điện, 3 - công nghệ thông tin). Trí Tuệ Nhân Tạo đang len lỏi vào mọi lĩnh vực trong đời sống mà có thể chúng ta không nhận ra.

## Section links

Bạn có thể tạo 1 đường dẫn đến một section (tiêu đề nào đó) trong bài viết.</br>
Ví dụ: </br>

```markdown
Click vào đây để đến section [Lists](#Lists)
```

Kết quả:</br>
Click vào đây để đến section [Lists](#lists)

## Relative links

Tương tự như link phía trên, bạn cũng có thể tạo liên kết dẫn đến thư mục trong repository của thư mục github.

```markdown
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

## Images

Đế chèn hình ảnh vào bài viết, ta dùng kí tự `!` sau đó đến dấu ngoặc vuông chứa đoạn văn bản mô tả hình ảnh khi hình không thể load trong `[]`, sau
đó là ngoặc tròn chứa liên kết bên trong `()`.</br>
Ví dụ:

```markdown
![Trí tuệ nhân tạo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fnhandan.vn%2Ftop-10-cong-nghe-tri-tue-nhan-tao-hang-dau-hien-nay-post741992.html&psig=AOvVaw2YRaSIOij25NMfLOGIoCOm&ust=1685122509776000&source=images&cd=vfe&ved=0CBEQjRxqFwoTCJCu69WAkf8CFQAAAAAdAAAAABAI)
```

Kết quả:</br>
![Trí tuệ nhân tạo](https://image.nhandan.vn/Uploaded/2023/athlrainagbna/2023_03_08/tri-tue-nhan-tao-ai-2-3436.jpg)

## Lists

Để tạo được danh sách ta có 2 cách:

- Sử dụng kí hiệu.
- Sử dụng số. </br>

Để tạo được được list dùng kí hiệu, ta có thể dụng một trong cách kí tự sau `*` , `-` hoặc `+`

```markdown
- George Washington
* John Adams
+ Thomas Jefferson
```

Để tạo được được list dùng kí hiệu, ta có thể dụng số

```markdown
1. George Washington
2. John Adams
3. Thomas Jefferson
```

Ngoài ra ta còn có thể dùng các tạo list con bên trong 1 phần tử list lớn hơn.

```markdown
1. Name
    - George Washington
    - John Adams
    - Thomas Jefferson
2. Job
    ...
```

Kết quả: </br>

1. Name
    - George Washington
    - John Adams
    - Thomas Jefferson
2. Job </br>
    ...

## Task lists

Để tạo được task list, chỉ cần dùng kí tự `[]` trước mỗi task, và điền kí tự `x` vào bên trong để đánh dấu.</br>
Ví dụ:

```markdown
- [x] George Washington
- [] John Adams
- [] Thomas Jefferson
```

Kết quả:

- [x] George Washington
- [ ] John Adams
- [ ] Thomas Jefferson

## Footnotes

Footnotes là tạo những chú thích.</br>
Ví dụ: </br>

```markdown
Here is a simple footnote[^1].
A footnote can also have multiple lines[^2].
[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
```

Kết quả:
Here is a simple footnote [^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.

## Hiding content with comments

Để tạo comment trong định dạng `.md` ta sử dụng kí tự comment giống HTML.

```markdown
<!-- This content will not appear in the rendered Markdown -->
```

## Ignoring Markdown formatting

Nếu ta muốn sử dụng các kí tự như ngoặc vuông hoặc * nhưng bị dính với định dạng của markdown, ta có thể bỏ qua điều đó bằng kí hiệu `\`.  </br>
Ví dụ:

```markdown
Let's rename \*our-new-project\* to \*our-old-project\*.
```

Kết quả: </br>
Let's rename \*our-new-project\* to \*our-old-project\*.
