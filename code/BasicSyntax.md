# Base Syntax

# Headings {标题}

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

Heading level 1===
==================

Heading level 2---
------------------

# 这个标题拥有 1 个 id {#my_id}

# 这个标题有 2 个 classes {.class1 .class2}

# Paragraphs {段落}

I really like using Markdown.

This is the first line.  
And this is the second line.

# Bold {黑体}

I just love **bold text**.
I just love __bold text__.
Love**is**bold
Love__is__bold

# Italic {斜体}

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

A_cat_meow

# Bold and Italic {黑体和斜体}

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text.

This is really___very___important text.

# Strikethrough {删除线}

~~The world is flat.~~ We now know that the world is round.

# Blockquotes {引用}

> Dorothy followed her through many of the beautiful rooms in her castle.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Nested Blockquotes {嵌套引用}

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

# Blockquotes with Other Elements {带有其他元素的引用}

> #### The quarterly results look great
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.

# Lists {列表}

1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

## Ordered Lists {有序列表}

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

## Unordered Lists {无序列表 - * +}

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

# Images {图片}

![Alt text](../assets/tux.png)

# Linking Images {链接图片}

[![An old rock in the desert](https://s2.loli.net/2023/04/04/TRK5AnxOLSiklMa.jpg "Magic")](https://s2.loli.net/2023/04/04/TRK5AnxOLSiklMa.jpg)

# Code
<!-- 代码 -->
At the command prompt, type `nano`.

# Escaping Backticks {转义反引号}

``Use `code` in your Markdown file.``

# Code Blocks {代码块}

    <html>
    <head>
        <title>Test</title>
    </head>

# Horizontal Rules {水平分割线}

***

---

_________________

# Links {链接}

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## Adding Titles {添加标题}

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URLs and Email Addresses {要快速将 URL 或电子邮件地址转换为链接，请将其放在尖括号中}

<https://www.markdownguide.org>
<fake@example.com>

## Formatting Links {格式化链接}

I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

## Reference-style Links {引用样式链接}

### Formatting the First Part of the Link {链接第一部分的格式}

[hobbit-hole][1]
[hobbit-hole] [1]

### Formatting the Second Part of the Link {链接第二部分的格式}

<!-- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle -->
<!-- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles" -->
<!-- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles' -->
<!-- [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles) -->
<!-- [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles" -->
<!-- [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles' -->
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

# Escaping Characters {转义字符}

\* Without the backslash, this would be a bullet in an unordered list.

## Characters You Can Escape

| Character | Name                                           |
| --------- | ---------------------------------------------- |
| \         | backslash                                      |
| `         | backtick (see also escaping backticks in code) |
| *         | asterisk                                       |
| _         | underscore                                     |
| { }       | curly braces                                   |
| [ ]       | brackets                                       |
| < >       | angle brackets                                 |
| ( )       | parentheses                                    |
| #         | pound sign                                     |
| +         | plus sign                                      |
| -         | minus sign (hyphen)                            |
| .         | dot                                            |
| !         | exclamation mark                               |
| \|        | pipe (see also escaping pipe in tables)        |
