
# 基本语法

**工欲善其事,必先利其器。**  
> [Markdown](http://markdown.p2hp.com/) 是一种轻量级标记语言，可以使用它来格式化几乎任何文档，是写博客，做记录的最佳选择。

## 标题

>要创建标题，请#在单词或短语的前面添加数字符号（）。您使用的数字符号的数量应与标题级别相对应。例如，要创建标题级别三（\<h3>），请使用三个数字符号（例如### My Header）。

| Syntax | 渲染输出 |
| :------ | :------- |
| # Heading level 1 | <font color=Black size=6>Heading level 1</font> |
| ## Heading level 2 | <font color=Black size=5>Heading level 2</font> |
| ### Heading level 3 | <font color=Black size=4>Heading level 3</font> |
| #### Heading level 4 | <font color=Black size=3>Heading level 4</font> |
| ##### Heading level 5 | <font color=Black size=2>Heading level 5</font> |
| ###### Heading level 6 | <font color=Black size=1>Heading level 6</font> |

## 段落

>要创建段落，请使用空白行分隔一行或多行文本。您不应缩进带有空格或制表符的段落。

| Syntax | 渲染输出 |
| :------ | :------- |
| <p>I really like using Markdown.</p> <p>I think I'll use it to format all of my documents from now on.</p> | <p>I really like using Markdown.</p> <p>I think I'll use it to format all of my documents from now on.</p> |

## 换行

> 要创建换行符（\<br>），请以两个或多个空格结束一行，然后键入return。

| Syntax | 渲染输出 |
| :------ | :------- |
| This is the first line.<br> And this is the second line. | This is the first line.<br> And this is the second line. |

## 着重

> 您可以通过使文本变为粗体或斜体来增加着重。

| element | Syntax | 渲染输出 |
| :-----: | :----: | :------:|
| **粗体** | \*\*bold text** | **bold text** |
| __粗体__ | \_\_bold text__ | __bold text__ |
| *斜体* | \*italicized  text* | *italicized  text* |
| _斜体_ | \_italicized  text_ | _italicized  text_ |
| ***粗体和斜体*** | \*\*\*bold_italicized text*** | ***bold_italicized text*** |
| ___粗体和斜体___ | \_\_\_bold_italicized text___ | ___bold_italicized text___ |

## 块引用

> 要创建blockquote，请>在段落前面添加一个 `>`。

`> Dorothy followed her through many of the beautiful rooms in her castle.`  

呈现的输出如下所示：

> Dorothy followed her through many of the beautiful rooms in her castle.

## 具有其他元素的块引用

> 块引用可以包含其他Markdown格式的元素。并非所有元素都可以使用-您需要进行实验以查看哪些元素有效。  

```text
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
> > fake news.
>
>  *Everything* is going according to **plan**.
```

呈现的输出如下所示：
> ### The quarterly results look great!
> 
> - Revenue was off the chart.
> - Profits were higher than ever.
> > fake news.
> 
> *Everything* is going according to **plan**.

## 列表

### 有序列表

> 要创建有序列表，请在订单项中添加数字和句点。数字不必按数字顺序排列，但列表应以数字开头。

```text
1. First item
2. Second item
3. Third item
3. Fourth item
8. Fifth item
6. Sixth item
7. Seventh item
   1. Indented item
   2. Indented item
5. Eighth item
```

呈现输出如下：

1. First item
2. Second item
3. Third item
3. Fourth item
8. Fifth item
6. Sixth item
7. Seventh item
   1. Indented item
   2. Indented item
5.  Eighth item

### 无序列表

> 要创建无序列表，请在订单项前添加破折号（-），星号（*）或加号（+）。缩进一个或多个项目以创建嵌套列表。

```text
- First item
- Second item
- Third item
+ Fourth item
* Fifth item
+ Sixth item
- Seventh item
  + Indented item
  * Indented item
* Eighth item
```

呈现输出如下：

- First item
- Second item
- Third item
+ Fourth item
* Fifth item
+ Sixth item
- Seventh item
  + Indented item
  * Indented item
* Eighth item

## 在列表中添加元素

> 要在保留列表连续性的同时在列表中添加另一个元素，请将该元素缩进四个空格或一个制表符，如以下示例所示。

### 段落

```text
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.
```

呈现的输出如下所示：

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### 块引用

```text
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```

呈现的输出如下所示：

* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

### 插入代码块

> 代码块通常缩进四个空格或一个制表符。当它们在列表中时，将它们缩进八个空格或两个选项卡，也可以使用围栏代码块，既` ```代码块``` `。

```text
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.
```
呈现的输出如下所示：

1. Open the file.
2. Find the following code block on line 21:

        <html>
            <head>
            <title>Test</title>
            </head>

3. Update the title to match the name of your website.

### 插入图片

```text
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](./../../images/00-start/markdown/tux.png)

3. Close the file.
```

呈现的输出如下所示：

1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](./../../images/00-start/markdown/tux.png)

3. Close the file.


## 代码

> 要将单词或短语表示为代码，请将其括在勾号（`）中。

| Syntax | 渲染输出 |
| :----: | :------:|
| At the command prompt, type \`nano`. | At the command prompt, type `nano` |

## 转义刻度线

> 如果要表示为代码的单词或短语包含一个或多个刻度线，可以通过将单词或短语括在双刻度线（``）中来对其进行转义。

| Syntax | 渲染输出 |
| :----: | :------:|
| \`\`Use \`code` in your Markdown file.``. | ``Use `code` in your Markdown file.`` |

## 代码块

> 要创建代码块，请在代码块的每一行缩进至少四个空格或一个制表符，也可以使用围栏代码块，既` ```代码块``` `。

\`\`\`html  
\<html>  
&emsp;&emsp;\<head>  
&emsp;&emsp;\</head>  
\</html>  
\`\`\`  
呈现的输出如下所示：

```html
<html>
  <head>
  </head>
</html>
```

## 水平线

> 要创建水平线***，请单独在一行上使用三个或更多的星号（），破折号（---）或下划线（___）。

```text
***
---
___
```

所有这三个的渲染输出看起来都相同：

***
---
___

## 链接

> 要创建链接，请将链接文本括在方括号（例如[Duck Duck Go]）中，然后立即在URL后面加上括号（例如(https://duckduckgo.com)）中的URL 。

```text
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).
```

呈现的输出如下所示：

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## 添加标题

> 您可以选择为链接添加标题。当用户将鼠标悬停在链接上时，这将显示为工具提示。要添加标题，请将其括在URL后面的括号中。

```text
My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").
```

呈现的输出如下所示：

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## 网址和电子邮件地址

> 要将URL或电子邮件地址快速转换为链接，请将其括在尖括号中。

```text
<https://markdown.p2hp.com>
<fake@example.com>
```

呈现的输出如下所示：

<https://markdown.p2hp.com>  
<fake@example.com>

## 格式化链接

> 为了强调链接，请在方括号和括号之前和之后添加星号。

```text
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://markdown.p2hp.com)*.
```

呈现的输出如下所示：

I love supporting the **[EFF](https://eff.org)**.  
This is the *[Markdown Guide](https://markdown.p2hp.com)*.

## 参考样式链接

> 引用样式链接是一种特殊的链接，它使URL在Markdown中更易于显示和阅读。引用样式的链接分为两部分：与文本保持内联的部分以及在文件中其他位置存储的部分，以使文本易于阅读。

### 格式化链接的第一部分

参考样式链接的第一部分使用两组括号进行格式化。第一组方括号包围应显示为链接的文本。第二组括号显示了一个标签，该标签用于指向您存储在文档其他位置的链接。

尽管不是必需的，但您可以在第一组和第二组支架之间包含一个空格。第二组括号中的标签不区分大小写，可以包含字母，数字，空格或标点符号。

这意味着以下示例格式对于链接的第一部分大致相同：

```text
[hobbit-hole][1]
[hobbit-hole] [1]
```

### 格式化链接的第二部分

引用样式链接的第二部分使用以下属性设置格式：

1. 标签放在方括号中，后紧跟冒号和至少一个空格（例如[label]: ）。
2. 链接的URL，您可以选择将其括在尖括号中。
3. 链接的可选标题，您可以将其括在双引号，单引号或括号中。

这意味着以下示例格式对于链接的第二部分几乎都是等效的：

```text
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)
```

您可以将链接的第二部分放在Markdown文档中的任何位置。有些人将它们放在出现的段落之后，而其他人则将它们放在文档的末尾（例如尾注或脚注）。

### 将零件放在一起的示例

假设您添加一个URL作为到段落的标准URL链接，并且在Markdown中看起来像这样：

```text
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.
```

尽管它可能指向有趣的附加信息，但显示的URL确实不会给现有的原始文本增加太多，除了使其难以阅读之外。要解决此问题，您可以改为设置网址格式：

```text
In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
```

在上述两种情况下，呈现的输出将相同：

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

## 图片

> 要添加图像，请添加感叹号（!），然后在括号中添加替代文本，并在括号中添加图像资源的路径或URL。您可以选择在括号中的URL之后添加标题。

```text
![Philadelphia's Magic Gardens. This place was so cool!](./../../images/00-start/markdown/philly-magic-garden.jpg "Philadelphia's Magic Gardens")
```

呈现的输出如下所示：

![Philadelphia's Magic Gardens. This place was so cool!](./../../images/00-start/markdown/philly-magic-garden.jpg "Philadelphia's Magic Gardens")

### 链接图像

要向图像添加链接，请将图像的Markdown括在方括号中，然后在括号中添加链接。

```text
[![An old rock in the desert](./../../images/00-start/markdown/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```

呈现的输出如下所示：

[![An old rock in the desert](./../../images/00-start/markdown/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

## 转义字符

> 要显示原义字符，否则将用于设置Markdown文档中的文本格式\，请在字符前面添加反斜杠（）。

```text
\* Without the backslash, this would be a bullet in an unordered list.
```

呈现的输出如下所示：

\* Without the backslash, this would be a bullet in an unordered list.