# markdown-playground
Messing around with (github) Markdown.

Can you <span style="background-color: #FFFF00">highlight text</span>?
Answer seems to be no: &lt;mark> and/or &lt;span> with a background color do not work (at least not in Github Markdown, which seems to be fairly minimalist):

==highlighted text== (using doubled equals signs)

<mark>highlighted text using mark</mark>

Let's see if ~~strikethrough~~ text works. Seems to be fine.

```
Could use a code block as a comment? (but only if doc has no code blocks.
```

You can do `inline code for comments too`, but again, if the doc already contains inline code, that could be confusing.

[//]: # A markdown comment.
