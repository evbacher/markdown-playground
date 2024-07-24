TEST: Markdown conversion via new Google Docs .md export:

This is a raw conversion from a Google Doc (HTML headings option for MD, no other options).

# MAIN: Docs to Markdown (GD2md-html)

This page demonstrates the features of [Docs to Markdown](https://workspace.google.com/marketplace/app/docs\_to\_markdown/700168918607) conversion from a Google Doc to a simple Markdown or HTML file. 

**Note**: Not all Markdown renderers support all Markdown features. For example github Markdown does not support a table of contents (\[TOC\]), footnotes, or definition lists. Also, some Markdown environments strip heading IDs and replace them with their own generated IDs. You’ll have to do some manual adjustments, depending on your target environment.

[Headings](\#headings)

[Heading IDs](\#heading-ids)

[Blank headings](\#blank-headings)

[Basic paragraphs](\#basic-paragraphs)

[Font attribute runs including extra whitespace at the ends](\#font-attribute-runs-including-extra-whitespace-at-the-ends)

[Mixed font spans](\#mixed-font-spans)

[Mixed code spans](\#mixed-code-spans)

[Lists](\#lists)

[Numbered lists (ordered lists)](\#numbered-lists-(ordered-lists))

[Unordered lists](\#unordered-lists)

[Another ordered list](\#another-ordered-list)

[A nested ordered list](\#a-nested-ordered-list)

[Lists with code blocks](\#lists-with-code-blocks)

[Lists with embedded paragraphs](\#lists-with-embedded-paragraphs)

[Definition lists](\#definition-lists)

[Definition list examples](\#definition-list-examples)

[Code blocks](\#code-blocks)

[Code blocks with lang specification](\#code-blocks-with-lang-specification)

[Code blocks with HTML](\#code-blocks-with-html)

[Tables](\#tables)

[Links](\#links)

[Images](\#images)

[Drawings](\#drawings)

[Equations](\#equations)

[Right-to-left text](\#right-to-left-text)

[Soft line-breaks](\#soft-line-breaks)

[Special characters (FEATURE REQUEST)](\#special-characters-(feature-request))

[Subscript and superscript processing](\#subscript-and-superscript-processing)

[Bugs](\#heading=h.s045t7da0oww)

**Note**: If you find any bugs, please file them at [https://github.com/evbacher/gd2md-html/issues](https://github.com/evbacher/gd2md-html/issues). Thanks for helping to make Docs to Markdown better\!

# Headings {#headings}

Docs to Markdown converts headings to the corresponding heading level in Markdown or HTML. If you use a lot of Heading 1 headings in your Doc, but you want to adhere to the HTML convention of only a single H1 heading per page, you can use the Demote headings option.

# Heading IDs {#heading-ids}

If you generate a table of contents (with blue links) in your Doc, Docs to Markdown will create IDs for each heading—this also allows proper conversion of intra-doc links. If your Markdown environment does not handle heading attributes, you can choose the HTML headings/IDs option.

# Blank headings {#blank-headings}

From here to END BLANK HEADINGS are headings that are empty or contain only whitespace.

#   	

##   		  

###   		   

######    			   

END BLANK HEADINGS

## Basic paragraphs {#basic-paragraphs}

This is a paragraph.[^1] (Docs to Markdown also supports footnotes) A sentence with some embedded code. Docs to Markdown changes “smart quotes” to straight quotes in code to guard against cut-and-paste errors.

## Font attribute runs including extra whitespace at the ends {#font-attribute-runs-including-extra-whitespace-at-the-ends}

For example a **bold run with some whitespace** on either end. Here’s an *italic run* with added whitespace. And a ~~strikethrough run~~ with additional whitespace. And some code with added whitespace. And some underline with added whitespace. Links [http://www.google.com](http://www.google.com). Link with no space:[http://www.google.com](http://www.google.com).

Some *italic**text**alternating**with**bold**italic*** but no spaces between font changes.

## Mixed font spans {#mixed-font-spans}

Some regular text, *followed by an italic span* ***with some embedded bold*** *text*. (Note: this may still be a problem, depending on how it’s formatted in the Google Doc. Like this: Some regular text, *followed by an italic span **with some embedded bold** text*.

Some more regular text. Some ~~strikethrough text~~ here. 

Some ~~strikethrough text at the end of the paragraph.~~

Followed by some regular text.

## Mixed code spans {#mixed-code-spans}

Docs to Markdown uses Markdown for most inline code, but it will also handle mixed code spans like this: $ ls \-l ***filename***, by using HTML markup.

## Lists {#lists}

Docs to Markdown supports numbered lists, ordered lists, and definition lists.

### Numbered lists (ordered lists) {#numbered-lists-(ordered-lists)}

Here is a numbered list:

1. Item one.  
1. Item two.

### Unordered lists {#unordered-lists}

And here is a bullet list:

* A list item without any punctuation  
* A list item with an embedded command: ps aux | grep conky | grep \-v grep | awk '{print $2}' | xargs kill  
* Some mixed-font code: ls \-l ***filename***. Followed by some normal text.

### Another ordered list {#another-ordered-list}

1. First item  
1. Second item  
1. Third item

### A nested ordered list {#a-nested-ordered-list}

1. First item  
1. Second item  
   1. First nested item  
   1. Second nested item  
1. Third item

### Lists with code blocks {#lists-with-code-blocks}

You can have a code block within a list item, as long as you indent the code  (in the Doc) the same amount as the list: 

* A text item, followed by a code block that's indented and should be part of this item:  
  // A comment.  
  some code;  
    callFunction();  
    
* Another item.  
  * A nested list item with a command:  
    $ cat file | grep dog | wc

### Lists with embedded paragraphs {#lists-with-embedded-paragraphs}

Note: Works for Markdown, still a known issue for HTML.

* A bullet list with an additional paragraph:  
  This is another paragraph.  
    
  This is a new paragraph, but also part of this list item. It should be indented  
* Another item.  
  * A nested item.  
    This is a new paragraph within the nested item.  
    // Some code after a nested paragraph.  
    callSomeFunction();  
* Another list item.  
* And another.  
  * Nested  
    A paragraph within a list item.  
    * Nested  
      A paragraph within a list item.  
  * Reducing the nesting level.  
* First-level list item.

A regular paragraph.

### Definition lists {#definition-lists}

Because Google Docs does not have a definition list element, Docs to Markdown uses a simple but explicit syntax that is similar to the kramdown syntax for definition lists:

?term on a line by itself (starting with a question mark)  
:Definition preceded by a colon.

### Definition list examples {#definition-list-examples}

**Note**: Github-flavored Markdown does not support Markdown definition-list syntax. You can select a definition list in a Google Doc and convert it to HTML if you’re using it in a GFM page.

? term  
: Definition here.

?term1  
?term2  
: First paragraph of definition.  
: Second paragraph of definition.

renders as:

?   term  
: Definition here.

?term1  
?term2  
: First paragraph of definition.  
: Second paragraph of definition.

?   A term that has some ***crazy formatting*** and characters (not recommended)//.  
: Definition of crazy term.

But a definition term cannot be empty:

?  
: Empty term above causes an error here.

## Code blocks {#code-blocks}

A code block (note that by default, Docs to Markdown does *not* add language descriptors to code blocks, but see [Code Blocks with lang specification](\#code-blocks-with-lang-specification)):

package main

import "fmt"

func main() {  
	fmt.Println("Hello, 世界")  
}

A single-cell table also becomes a code block:

| \#include\<stdio.h\>main(){    printf(“Hello World”);} |
| :---- |

If you have “smart quotes” in regular text, they should be preserved. But if you have any smart quotes in “code” or code blocks, Docs to Markdown removes them during the conversion:

func main() {  
	fmt.Println(“Why would you do this?”)  
}

## Code blocks with lang specification {#code-blocks-with-lang-specification}

Docs to Markdown supports an optional lang specification on the first line of the code sample (in the Doc source). The syntax is: lang: *langspec*

For example, here is a code block that specifies lang:c on the first line:

lang:c  
\#include\<stdio.h\>  
main()  
{  
    printf("Hello World");  
}

This also works in single-cell tables: here is a single-cell table that specifies lang: java on the first line:

| lang: java public class HelloWorld {     public static void main(String\[\] args) {         System.out.println("Hello, World");     } } |
| :---- |

## Code blocks with HTML {#code-blocks-with-html}

Code with some embedded HTML tags that should be displayed, not interpreted:

lang:html  
This is \<code\>some code\</code\>  
and some \<strong\>bold text\</strong\>.

A single-cell table with some HTML inside:

| This is some code      We want to handle as code block; Preserve whitespace, \<code\>HTML tags\</code\>, etc. Make a fenced code block in Markdown,         pre in HTML. |
| :---- |

## Tables {#tables}

Docs to Markdown generates HTML tables.

A table:

| Some text. | some code   var i \= 0; |
| :---- | :---- |
| More text. | A list: [mozzarella cheese](https://en.wikipedia.org/wiki/Mozzarella) |

You can also merge columns and rows in tables:

| This row merges the first three columns. one |  |  | four |
| :---- | :---- | :---- | :---- |
| one | two | **These two rows are merged**  three | four |
| one | two |  | four |

## Links {#links}

Some regular URL links:

* [http://www.google.com/](http://www.google.com/)  
* [https://fivethirtyeight.com/](https://fivethirtyeight.com/)

Some links with titles:

* [Jason Kottke's blog](http://kottke.org/)  
* [Bean Road](https://beanroad.blogspot.com/)

## Images {#images}

A plain image:

![][image1]

Note that the image link will be broken until you store the image file on your server and adjust the path and width if necessary.

Alternatively, you can use a Drawing to display an image. Here's an example where we've pasted the image into a Drawing and referenced it after converting the doc:

![IMG\_20161231\_153334114.jpg][image2]

Tip: You can limit the width of an image in Markdown by adding (for example) {width="75%"} after the link markup (if your Markdown engine supports such syntax). For HTML, just add a width="75%" attribute to the img tag.

## Drawings {#drawings}

Google Docs does not provide an API for accessing the data in a Google Drawing. If you have an inline drawing, Docs to Markdown will warn and provide an alert in the converted output:

You can display Google Drawings (and images in Drawings) by reference. See [Google Drawings by reference](https://github.com/evbacher/gd2md-html/wiki/Google-Drawings-by-reference) for details.

Here's an example where we've referred to a drawing by reference (after converting):

Tip: For any drawing that you display by reference, be sure to change the permissions to make it viewable by anyone with the link.

## Equations {#equations}

If you insert an equation using Google Docs, Docs to Markdown will warn and insert an alert message in the output. However, if your target publishing platform supports LaTeX equations, you can use LaTeX syntax directly.

A Google Docs equation:

ei= \-1

A LaTeX equation:

$$e^{i\\pi } \= \-1$$

renders as:

$$e^{i\\pi } \= \-1$$

## Right-to-left text {#right-to-left-text}

A few Arabic words هذه فقرة تجريبية inside an English paragraph:

They should appear as in this RTL paragraph:  
هذه فقرة تجريبية 

## Soft line-breaks {#soft-line-breaks}

lineBreak  
This line contains a shift-enter soft line-break here  
This bit is after the line break.

This is a line with some bold text interrupted by a soft line **break (shift-enter) here**  
**Followed by more bold** and some more regular text.

This paragraph has an explicit line-break (Enter) here.  
And this is a separate paragraph.

## Special characters (FEATURE REQUEST) {#special-characters-(feature-request)}

FEATURE REQUEST: Angle bracket escapes:

* Angle brackets: If you put angle brackets in your text: \< or \>, we don't want that to render as an HTML tag. So, we use \&amp;lt; for the opening bracket by default. However, if you select the Render HTML tags option, the opening \< will not be replaced.  
* Test: it seems that loose angle brackets \< and \> do not behave like HTML tags. But when there is no whitespace: \<some text\>, they do behave like HTML tags. To change that behavior, we’ll need to (by default) escape the opening angle bracket and turn it into \&amp;lt;.   
* But if you really want an angle bracket while using the default setting (to insert a few HTML tags), you can escape it: \\\<tag\>, \\\<div class=’someclass’\>. Not escaped: \<tag\>. Also not escaped: \<p\>This is an HTML paragraph.\<p\>  
* Escaped: \\\<p\>This is an HTML paragraph.\\\<p\>

Note that we need to replace the opening \<, even if it occurs at the beginning of a line, like this:

\<br\>\<img src="img1.png"/\>\<br\>

Let’s also check for one at the end of a line, though that would be unusual: \<

Apparently, it's not a problem in code blocks (the tags are never rendered):

`This is a code block with some <html> tags.`

This is some regular text.

| This is a single-cell table code block with some \<html\> tags. |
| :---- |

This is some more regular text.

## Subscript and superscript processing {#subscript-and-superscript-processing}

A sentence with subscript and superscript and some more regular text and [a link to Google](http://www.google.com).  
And more **bold** and mixed **bold *italic*** code and some more text. Some *italic text*.

Another paragraph with **some bold text**.

SUPA subscript or superscript at the beginning or end of a paragraph should not break things:SUB

1. A numbered list following a terminal subscript.  
1. Another list item.

## Horizontal rules

This is a horizontal rule:  
---

This is a regular paragraph.

## Bugs

* Current open bugs: [https://github.com/evbacher/gd2md-html/issues](https://github.com/evbacher/gd2md-html/issues)   
* New bug or feature request: [https://github.com/evbacher/gd2md-html/issues/new](https://github.com/evbacher/gd2md-html/issues/new). Thanks for helping to make Docs to Markdown better\!

This document ends with a regular paragraph.

[^1]:  Docs to Markdown supports footnotes\!
