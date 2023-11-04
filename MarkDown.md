# [MARKDOWN](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
***End***[^end]
[^end]:start
<details>
<summary>Menu</summary>

- [MARKDOWN](#markdown)
  - [1. Headings - Tiêu đề](#1-headings---ti%C3%AAu-%C4%91%E1%BB%81)
  - [2. Paragraphs - Văn bản](#2-paragraphs---v%C4%83n-b%E1%BA%A3n)
  - [3. Line break - Tạo nhiều dòng](#3-line-break---t%E1%BA%A1o-nhi%E1%BB%81u-d%C3%B2ng)
  - [4. Emphasis - Nhấn mạnh](#4-emphasis---nh%E1%BA%A5n-m%E1%BA%A1nh)
  - [5. Blockquote - Khối trích dẫn](#5-blockquote---kh%E1%BB%91i-tr%C3%ADch-d%E1%BA%ABn)
  - [6. List - Danh Sách](#6-list---danh-s%C3%A1ch)
  - [7. Code](#7-code)
  - [8. Horizontal rules - Đường kẻ nằm ngang](#8-horizontal-rules---%C4%91%C6%B0%E1%BB%9Dng-k%E1%BA%BB-n%E1%BA%B1m-ngang)
  - [9. Link](#9-link)
  - [10. Images](#10-images)
  - [11. Table - Bảng](#11-table---b%E1%BA%A3ng)
  - [12. FootNotes - Tạo ghi chú](#12-footnotes---t%E1%BA%A1o-ghi-ch%C3%BA)
  - [13. Comments](#13-comments)
  - [14. Collapsed sections - Danh sách có thể tương tác](#14-collapsed-sections---danh-s%C3%A1ch-c%C3%B3-th%E1%BB%83-t%C6%B0%C6%A1ng-t%C3%A1c)
  - [17. Dùng \< \\ \> để ngăn chặn các lệnh](#17-d%C3%B9ng----%C4%91%E1%BB%83-ng%C4%83n-ch%E1%BA%B7n-c%C3%A1c-l%E1%BB%87nh)

</details>

***

## 1. Headings - Tiêu đề

- Sử dụng < #|-|= > để tạo tiêu đề.
    
    ```md
    "# Heading level 1."
    or
    "Heading level 1.
    ="
    ```

    ```md
    "## Heading level 2."
    or
    "Heading level 2.
    -"
    ```
    
> Note: Max là level 6 (######).

## 2. Paragraphs - Văn bản
    This is paragraphs.
    
## 3. Line break - Tạo nhiều dòng
    This is the first line.
    And this is the second line.
    
## 4. Emphasis - Nhấn mạnh

- #### 4.1 Bold
    ```md
    **bold text**
    or 
    __bold text__
    ```

- #### 4.2 Italic 
    ```md
    *italic text*
    or
    _italic text_
    ```
- #### 4.3 Bold and Italic
    ```md
    \(italic and bold text\)
    
    ***italic and bold text***
    ```

    ```md
    ___italic and bold text___
    
    *__italic and bold text__*
    
    _**italic and bold text**_
    
    *_*italic and bold text*_*
    
    _*_italic and bold text_*_
    ```
        
- #### 4.4 Subscript and Superscript
    ```md
    <sub>Subscript</sub>  
    <sup>Superscript</sup>
    ```
    - This is a <sub>subscript</sub> text.
    - This ia a <sup>Superscript</sup> text.

- #### 4.5 Strikethrough - Gạch bỏ
    ```md
    ~~Noa"-"~~
    ```
    > ~~Noa"-"~~


## 5. Blockquote - Khối trích dẫn
```md
> Followed me.
```
The Rendered output looks like this:
> Followed me.


- #### 5.1 Blockquote with multiple paragraphs
    ```md
    > Dorothy followed her through many of the beautiful rooms in her castle.
    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    ```

  - The Rendered output looks like this:

    > Dorothy followed her through many of the beautiful rooms in her castle.
    > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.



- #### 5.2 Nested Blockquote
    ```md
    > Dorothy followed her through many of the beautiful rooms in her castle.
    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
    ```

  - The Rendered output looks like this:
    > Dorothy followed her through many of the beautiful rooms in her castle.
    >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.



- #### 5.3 Blockquote with other elements
    ```md
    > #### The quarterly results look great!
    >
    > - Revenue was off the chart.
    > - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.
    ```

  - The Rendered output looks like this:

    > #### The quarterly results look great!
    >
    > - Revenue was off the chart.
    > - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.

## 6. List - Danh Sách

- #### 6.1 Ordered List - Theo bậc
    ```md
    1. first item
    2. second item
    3. third item 
    ```

    ```md
    1. first item
    2. second item
        1. first item
        2. second item
    3. third item
    ```        

- #### 6.2 Unordered List - Không theo bậc
    ```md
    - first item
    - second item
    ```
    
    ```md
    + first item
    + second item
    ```
    
    ```md
    * first item
    * second item
    ```

    ```md
    -first item
        + first item
    ```

- #### 6.3 Adding elements in list (All)

- #### 6.4 Task List
    ```py
    - [x] First item.
    + [ ] Second item.
    * [ ] Third item
    ```
  - The rendered looks like this:
    - [x] First item.
    + [ ] Second item.
    * [ ] Third item

## 7. Code

```md
`print("Hello,World!")`
```

- The Rendered output looks like this:
`print("Hello,World!")`

 ---

- Formatting code.

       ```html
       <!DOCTYPE html>
        <html lang="en">
        <head>
           <meta charset="UTF-8">
           <meta name="viewport" content="width=device-width, initial-scale=1.0">
           <title>Document</title>
        </head>
        <body>
    
        </body>
        </html>
         ```

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    </head>
    <body>
    
    </body>
    </html>
    ```

## 8. Horizontal rules - Đường kẻ nằm ngang
```md
***
---
___
```

## 9. Link

```md
[Me§](https://github.com/Huylrn)
```
>[Me§](https://github.com/Huylrn)
* Formatting in [..] -> **Ok**

## 10. Images

- 😄`Command + V` from image.

    `<img width="230" alt="image" src="https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032">`

    <img width="230" alt="image" src="https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032">

- default
    ```md
    ![Not found](https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032)
    ```

    ![Not found](https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032)


## 11. Table - Bảng

```md
| A\B | B1  | B2  | B3  |
| --- | --- | --- | --- |
| A1  | 1   | 2   | 3   |
| A2  | 5   | 6   | 2   |
| A3  | 6   | 9   | 0   |
| A\B | B1  | B2  | B3  |
| -   | -   | -   | -   |
| A1  | 1   | 2   | 3   |
| A2  | 5   | 6   | 2   |
| A3  | 6   | 9   | 0   |
```
| A\B | B1  | B2  | B3  |
| --- | --- | --- | --- |
| A1  | 1   | 2   | 3   |
| A2  | 5   | 6   | 2   |
| A3  | 6   | 9   | 0   |
| A\B | B1  | B2  | B3  |
| -   | -   | -   | -   |
| A1  | 1   | 2   | 3   |
| A2  | 5   | 6   | 2   |
| A3  | 6   | 9   | 0   |

## 12. FootNotes - Tạo ghi chú
```md
[^1]: Note is here.
Note? [^1]
```
[^1]: Note is here.

Note? [^1]

## 13. Comments
```md
<!-- Write comments is here. -->
```
## 14. Collapsed sections - Danh sách có thể tương tác 

````md
<details>

<summary>Tips for collapsed sections</summary>

You can add text within a collapsed section. 

You can add an image or a code block, too.
```ruby
   puts "Hello World"
```
</details>
````

<details>

<summary>Tips for collapsed sections</summary>

You can add text within a collapsed section. 

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

## 17. Dùng < \ > để ngăn chặn các lệnh
```md
\* Helle,World!\*
```
\* Hello,World!\*
