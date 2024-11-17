# The Complete Guide to README Markdown Syntax

Markdown is a lightweight markup language for formatting text. It is commonly used in README files on GitHub. Below is a comprehensive guide to Markdown syntax with rendered outputs.

---

## Table of Contents
```markdown
- [Headers](#headers)
- [Text Formatting](#text-formatting)
- [Lists](#lists)
  - [Unordered Lists](#unordered-lists)
  - [Ordered Lists](#ordered-lists)
- [Links](#links)
- [Images](#images)
- [Code Blocks](#code-blocks)
- [Blockquotes](#blockquotes)
- [Horizontal Lines](#horizontal-lines)
- [Tables](#tables)
- [Task Lists](#task-lists)
- [Escaping Characters](#escaping-characters)

Output:
- Headers
- Text Formatting
- Lists
- Unordered Lists
- Ordered Lists
- Links
- Images
- Code Blocks
- Blackquotes
- Horizontal Lines
- Tables
- Task Lists
- Escaping
```

---

### Headers

```git
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

### Fonts
```git
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
***~~Italic, bold, and strikethrough1~~***
```
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
***~~Italic, bold, and strikethrough1~~***	

---

### Lists
> Unordered
```git
* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b
```
* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b
OR `- Item 1`
   - Item 1
   
> Ordered
```git
1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg
```
1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg
      
---

### Links
```git
* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>
```
* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>

### Images
#### Inline Images
```git
![Alt Text](https://via.placeholder.com/150 "Image Title")
```
![Alt Text](https://via.placeholder.com/150 "Image Title")

---

### Code Blocks
#### Inline Code
```git
Use backticks (`) for inline code, like `code`.
```
Use backticks (`) for inline code, like `code`.

### Multiline Code Blocks
```git
```python
def hello_world():
    print("Hello, World!")
```
python
def hello_world():
    print("Hello, World!")

---

> Blockquotes
```git
> This is a blockquote.
>> Nested Blockquote.
```
> This is a blockquote.
>> Nested Blockquote.

---

### Horizontal Lines
```git
---
```
---

### Tables
```git
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |
```
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Data     | Data     |
| Row 2    | Data     | Data     |

---

### Task Lists
```git
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```
- [x] Task 1
- [ ] Task 2
- [ ] Task 3

---

### Escaping Characters
```git
\*This will not be italicized\*
```
\*This will not be italicized\*

---

### Combining Markdown Features
```git
### **Bold Heading**
> A blockquote with `inline code` and a [link](https://example.com).
```
**Bold Heading**
> A blockquote with `inline code` and a [link](https://example.com).```
