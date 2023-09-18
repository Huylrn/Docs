# [MARKDOWN](https://www.markdownguide.org/basic-syntax/#overview)
- [MARKDOWN](#markdown)
  - [1. Headings - Tiêu đề](#1-headings---tiêu-đề)
  - [2. Paragraphs - Văn bản](#2-paragraphs---văn-bản)
  - [3. Line break - Tạo nhiều dòng](#3-line-break---tạo-nhiều-dòng)
  - [4. Emphasis - Nhấn mạnh](#4-emphasis---nhấn-mạnh)
      - [4.1 Bold](#41-bold)
      - [4.2 Italic](#42-italic)
      - [4.3 Bold and Italic](#43-bold-and-italic)
      - [4.4](#44)
      - [4.5 Subscript and Superscript](#45-subscript-and-superscript)
      - [4.6 Strikethrough - Gạch bỏ](#46-strikethrough---gạch-bỏ)
  - [5. Blockquotes - Khối trích dẫn](#5-blockquotes---khối-trích-dẫn)
      - [5.1 Blockquotes with multiple paragrahs](#51-blockquotes-with-multiple-paragrahs)
      - [5.2 Nested Blockquotes](#52-nested-blockquotes)
      - [5.3 Blockquotes with other elements](#53-blockquotes-with-other-elements)
  - [6. List - Danh Sách](#6-list---danh-sách)
      - [6.1 Ordered List - Theo bậc](#61-ordered-list---theo-bậc)
      - [6.2 Unordered List - Không theo bậc](#62-unordered-list---không-theo-bậc)
      - [6.3 Adding elements in list (All)](#63-adding-elements-in-list-all)
      - [6.4 Task List](#64-task-list)
  - [7. Code](#7-code)
  - [8. Horizontal rules - Đường kẻ nằm ngang](#8-horizontal-rules---đường-kẻ-nằm-ngang)
  - [9. Link](#9-link)
  - [10. Images](#10-images)
  - [11. Table - Bảng](#11-table---bảng)
  - [12. Note](#12-note)
  - [13. Dùng \< \\ \> để loại bỏ các lệnh](#13-dùng----để-loại-bỏ-các-lệnh)

***
***
***

## 1. Headings - Tiêu đề

 Sử dụng < #|-|= > để tạo tiêu đề.

    "# Heading level 1."
    or
    "Heding level 1.
    ="
    
---

    "## Heading level 2."
    or
    "Heading level 2.
    -"
    
Note: Max là level 6 (######).

## 2. Paragraphs - Văn bản
    This is paragraphs.
    
## 3. Line break - Tạo nhiều dòng
    This is the first line.
    And this is the second line.
    
## 4. Emphasis - Nhấn mạnh

#### 4.1 Bold
        **bold text**
        or 
        __bold text__
#### 4.2 Italic 
        *italic text*
        or
        _italic text_
#### 4.3 Bold and Italic
        \(italic and bold text\)

        ***italic and bold text***

---
`more`

        ___italic and bold text___
        
        *__italic and bold text__*
        
        _**italic and bold text**_
        
        *_*italic and bold text*_*
        
        _*_italic and bold text_*_
        
#### 4.4 

#### 4.5 Subscript and Superscript
        <sub>Subscript</sub>  
        <sup>Superscript</sup>
> This is a <sub>subscript</sub> text.

> This ia a <sup>Superscript</sup> text.
 

#### 4.6 Strikethrough - Gạch bỏ
        ~~Noa"-"~~
> ~~Noa"-"~~


## 5. Blockquotes - Khối trích dẫn


        > Followed me.
The Rendered output looks like this:

> Followed me.


#### 5.1 Blockquotes with multiple paragrahs

        > Dorothy followed her through many of the beautiful rooms in her castle.
        > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

The Rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.



#### 5.2 Nested Blockquotes

        > Dorothy followed her through many of the beautiful rooms in her castle.
        >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

The Rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.



#### 5.3 Blockquotes with other elements

        > #### The quarterly results look great!
        >
        > - Revenue was off the chart.
        > - Profits were higher than ever.
        >
        >  *Everything* is going according to **plan**.

The Rendered output looks like this:

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

## 6. List - Danh Sách

#### 6.1 Ordered List - Theo bậc

        1. first item
        2. second item
        3. third item 

---
        
        1. first item
        2. second item
            1. first item
            2. second item
        4. third item

#### 6.2 Unordered List - Không theo bậc

        - first item
        - second item
        
---

        + first item
        + second item
        
---

        * first item
        * second item

---

        -first item
            + first item

#### 6.3 Adding elements in list (All)

#### 6.4 Task List
```py
- [x] First item.
+ [ ] Second item.
* [ ] Third item
```
The rendered looks like this:
- [x] First item.
+ [ ] Second item.
* [ ] Third item

## 7. Code

        `print("Hello,World!")`

The Rendered outout looks like this:
 `print("Hello,World!")`

 ---

 + Formatting code.

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

        ***
        ---
        ___

## 9. Link

        [Me§](https://github.com/Huylrn)
> [Me§](https://github.com/Huylrn)
* Formatting Links -> Ok

## 10. Images

😄`Command + V` from image.

`<img width="230" alt="image" src="https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032">`


<img width="230" alt="image" src="https://github.com/Huylrn/Docs/assets/141661219/bee8aef2-1022-4630-9483-f7be7890b032">

## 11. Table - Bảng

    |A\B|B1|B2|B3|
    |-|-|-|-|
    |A1 |1|2|3|
    |A2 |5|6|2|
    |A3 |6|9|0|
|A\B|B1|B2|B3|
|-|-|-|-|
|A1 |1|2|3|
|A2 |5|6|2|
|A3 |6|9|0|

## 12. Note
        [^1]: Note is here.
        Note? [^1]
[^1]: Note is here.

> Note? [^1]


## 13. Dùng < \ > để loại bỏ các lệnh
        \* Helle,World\!
        \`Hehehe\`
\* Hello,World\!

\`Hehehe\`
