# [MARKDOWN](https://www.markdownguide.org/basic-syntax/#overview)
1. [Headings](https://github.com/Huylrn/Docs/edit/master/MarkDown.md#1-headings-ti%C3%AAu-%C4%91%E1%BB%81)
2. [Paragraphs](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#2-paragraphs-v%C4%83n-b%E1%BA%A3n)
3. [Line break](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#3-line-break-t%E1%BA%A1o-nhi%E1%BB%81u-d%C3%B2ng)
4. [Emphasis](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#4-emphasis-nh%E1%BA%A5n-m%E1%BA%A1nh)
       + [Bold](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#bold)
       + [Italic](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#italic)
       + [Bold and Italic](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#bold-and-italic) 
5. [Blockquotes](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#5-blockquotes)
    + [5.1 Blockquotes with multiple paragrahs](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#51-blockquotes-with-multiple-paragrahs)
    + [5.2 Nested Blockquotes](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#52-nested-blockquotes)
    + [5.3 Blockquotes with other elements](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#53-blockquotes-with-other-elements)
6. [List](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#6-list-danh-s%C3%A1ch)
    + [6.1 Ordered List](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#61-ordered-list)
    + [6.2 Unordered List](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#62-unordered-list)
    + [6.3 Adding elements in list](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#63-adding-elements-in-list-all)
7. [Adding Code](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#7-adding-code)
8. [Horizontal rules](https://github.com/Huylrn/Docs/blob/master/MarkDown.md#8-horizontal-rules-%C4%91%C6%B0%E1%BB%9Dng-k%E1%BA%BB-n%E1%BA%B1m-ngang)
9. [Link]
10. [Images]
11. [ \  \]

***
***
***

## 1. Headings (Tiêu đề)[#Source](https://www.markdownguide.org/basic-syntax/#headings)

###### Sử dụng < #|-|= > để tạo tiêu đề.

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

## 2. Paragraphs (Văn bản)
    This is paragraphs.
    
## 3. Line break (Tạo nhiều dòng)
    This is the first line.
    And this is the second line.
    
## 4. Emphasis (Nhấn mạnh)

1. ###### Bold
        **bold text**
        or 
        __bold text__
2. ###### Italic 
        *italic text*
        or
        _italic text_
3. ###### Bold and Italic
        ***italic and bold text***

        ___italic and bold text___
        
        *__italic and bold text__*
        
        _**italic and bold text**_
        
        *_*italic and bold text*_*
        
        _*_italic and bold text_*_
        
## 5. Blockquotes

        > Followed me.
The Rendered output looks like this:

> Followed me.

---

#### 5.1 Blockquotes with multiple paragrahs

        > Dorothy followed her through many of the beautiful rooms in her castle.
        > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

The Rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---

#### 5.2 Nested Blockquotes

        > Dorothy followed her through many of the beautiful rooms in her castle.
        >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

The Rendered output looks like this:

> Dorothy followed her through many of the beautiful rooms in her castle.
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

---

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

## 6. List (Danh Sách)

#### 6.1 Ordered List

        1. first item
        2. second item
        3. third item 

---
        
        1. first item
        2. second item
            1. first item
            2. second item
        4. third item

#### 6.2 Unordered List

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

## 7. Adding Code

        `print("Hello,World!")`

The Rendered outout looks like this:
 `print("Hello,World!")`

## 8. Horizontal rules (Đường kẻ nằm ngang)

        ***
        ---
        ___

## 9. Link

        [Me§](https://github.com/Huylrn)
> [Me§](https://github.com/Huylrn)
* Formatting Links -> Ok

## 10. Images

## 11. Dùng < \ > để loại bỏ các lệnh
        \ * Helle,World!
\ * Hello,World!
