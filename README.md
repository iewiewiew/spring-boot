[TOC]


# 参考资料
[Markdown官方教程](https://markdown.com.cn/)



# 1、Markdown 标题语法
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6



# 2、Markdown 段落语法
I really like using Markdown.

I think I'll use it to format all of my documents from now on.



# 3、Markdown 换行语法
This is the first line.    
And this is the second line.



# 4、Markdown 强调语法
## 粗体（Bold）
I just love **bold text**.  
I just love __bold text__.  
Love**is**bold

## 斜体（Italic）
Italicized text is the *cat's meow*.  
Italicized text is the _cat's meow_.  
A*cat*meow

## 粗体（Bold）和斜体（Italic）
This text is ***really important***.  
This text is ___really important___.  
This text is __*really important*__.  
This text is **_really important_**.  
This is really***very***important text.



# 5、Markdown 引用语法
要创建块引用，请在段落前添加一个 > 符号
> Dorothy followed her through many of the beautiful rooms in her castle.

多个段落的块引用
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

嵌套块引用
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

带有其它元素的块引用
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
    >
    >  *Everything* is going according to **plan**.



# 6、Markdown 列表语法
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item



# 7、Markdown 代码语法
At the command prompt, type `nano`.  
``Use `code` in your Markdown file.``



# 8、Markdown 分隔线语法
***

---

_________________



# 9、Markdown 链接语法
这是一个链接 [Markdown语法](https://markdown.com.cn)。  
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。  
<https://markdown.com.cn>  
<fake@example.com>  
I love supporting the **[EFF](https://eff.org)**.  
This is the *[Markdown Guide](https://www.markdownguide.org)*.  
See the section on [`code`](#code).



# 10、Markdown 图片语法
![这是图片](/assets/img/philly-magic-garden.jpg "Magic Gardens")  
[![沙漠中的岩石图片](/assets/img/shiprock.jpg "Shiprock")](https://markdown.com.cn)



# 11、Markdown 转义字符语法
\* Without the backslash, this would be a bullet in an unordered list.  
http://images.google.com/images?num=30&amp;q=larry+bird  
&copy;



# 12、Markdown 内嵌 HTML 标签
This **word** is bold. This <em>word</em> is italic.

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.



# 13、Markdown 表格
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

对齐
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |



# 14、Markdown 围栏代码块
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```



# 15、Markdown 脚注
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.
    
    `{ my code }`
    
    Add as many paragraphs as you like.

Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.



# 16、Markdown 标题编号
### My Great Heading {#custom-id}
[Heading IDs](#heading-ids)



# 17、Markdown 定义列表
First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.



# 18、Markdown 删除线
~~世界是平坦的。~~ 我们现在知道世界是圆的。



# 19、Markdown 任务列表语法
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media



# 20、Markdown 使用 Emoji 表情
去露营了！ :tent: 很快回来。

真好笑！ :joy:



# 21、Markdown 自动网址链接
自动将URL转换为链接
http://www.example.com

禁用自动URL链接
`http://www.example.com`
