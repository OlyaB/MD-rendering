[//]: # 
(Prompt for the chat to render this file: 
Take the text from the attached file and just write it as it is, in your own text, not in a snippet. Use the markdown rendering as used in the file.
)

# Markdown Syntax Example

This file is a demonstration of all the elements of Markdown syntax. Use it to test your Markdown rendering styles.

---

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Paragraph, link, inline code
A line of text with whitespaces in the end  
*italic,* **bold,** ***bold and italic***  

[A standalone link](https://www.markdownguide.org)  
[A link](https://www.markdownguide.org) inside a text line

Here is some `inline code`.  
And some more on `another line`.  
Inline code that is also `[A link](https://www.markdownguide.org)`  
A line of text without an inline code to check line height

A paragraph after a new line with some more examples:  
~~crossed out.~~  
Emojis: 🎉 👍 ✨ 🚀  

---

A paragraph after a line with escape chars:  
\*not italicized\*  
\# This is not a header

## Code

### Fenced Code Blocks

#### JavaScript Example
A paragraph of text before a code block:
```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}
greet("World");
```

A paragraph of text after a code block.

#### Python Example
```python
def greet(name):
    print(f"Hello, {name}!")

greet("World")
```

## Lists

A paragraph of text before a list:

- Item
    - Subitem
    - Subitem
      - Subitem
      - Subitem
- Item

1. First
2. Second
    1. Second (subitem A)
    2. Second (subitem B)
3. Third


1. Let's mix different list styles
   * Bullet 1
     1. Numbered 1
     2. Numbered 2
   * Bullet 2

A paragraph of text after a list.

- [x] Checkbox checked
- [ ] Checkbox unchecked
    - [ ] Indented checkbox
- [ ] And another checkbox


## Images

![Markdown Logo](https://markdown-here.com/img/icon256.png)

## Blockquotes

> "To be, or not to be, that is the question." – William Shakespeare

## Tables

| Syntax      | Description | Example       |
|-------------|-------------|---------------|
| Header      | Title       | Row 1 Content |
| Paragraph   | Text        | Row 2 Content |
