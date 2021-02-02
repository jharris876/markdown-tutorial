# Markdown Tutorial

Markdown is a simple markup language that derives its name from being simple and easy to use. This tutorial will provide the information required to get started using Markdown as well as links to other resources to help reinforce what is here.

## Paragraphs

Paragraphs in Markdown are simply consecutive lines of text. To start a new paragraph, put one blank line between it and the previous paragraph.

This is what a second paragraph looks like in this context: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis euismod  lacus vel augue sollicitudin vestibulum. Nullam ultrices nisl et dictum posuere. Morbi commodo est ut vestibulum imperdiet. Etiam faucibus ligula lacinia urna accumsan, ut euismod eros cursus. 

## Headings

Headings are created using the `#` character. You can have 6 levels of headings, with each level simply requiring an additional `#`. You should always put a space between the `#` and the heading name.

# Heading 1 `# Heading 1 `

## Heading 2 `## Heading 2 `

### Heading 3 `### Heading 3`

#### Heading 4 `#### Heading 4`

##### Heading 5 `##### Heading 5`

###### Heading 6 `###### Heading 6`

Note: to escape Markdown syntax, use `\`. 

## Bolding and Italicizing

To make text bold, surround it with `**`.

**This is bold text.**

To italicize text, surround it with `*`. Note that you can also use `_` to italicize text.

*This is italicized text.*

To make text bold *and* italicized, suround it with `***`.

***This text is bold and italicized.***

## Blockquotes

Using `>` you can place text in blockquotes.  `> Here is some text that has been placed in a blockquote.`

> Here is some text that has been placed in a blockquote.

## Lists

Markdown supports two type of lists; ordered and unordered. As you might imagine, an ordered list is numbered and an unordered list is only bulleted.

Ordered lists are made using numbers; a `.` or `)` must follow the number.

1. An

2. ordered

3. list.

Unordered lists support the use of `*` as well as `+` and `-` .

* An 

* unordered

* list.

Lists can also be nested by indenting items in sublists by four spaces. 

* A
  
  * nested.
    
    * list.

## Code

There are two easy methods for including segments of code in a Markdown document. For a single line of code, surround the line of text with backticks `` `. This is also useful for command line snippets or other text meant to be copied and pasted.

` javac *.java `

For a longer segment of code, create a fenced code block by placing triple backticks ````` above and below the code segment.

You can specify the language used by adding it after the first set of backticks: ````java`

```java
class HelloWorld
{
    public static void main(String[] args)
    {
        System.out.println("Hello, world!");
    }
}
```

## Links and Images

You can create links by surrounding the text you want to display in brackets `[]` followed by the URL in parentheses `()`.

`[TN Tech Website](https://tntech.edu)`

becomes: [TN Tech Website](https://tntech.edu)

Embedding an image uses a similar syntax:

`![Your Text Here](your-image.jpg)` 

## Additional Resources

[CommonMark](https://commonmark.org/)

[Markdown Guide](https://www.markdownguide.org/)
