# Markdown Tips

1. [Headings](#headings)
1. [Line Breaks](#line-breaks)
1. [Emphasis](#emphasis)
    - [Bold](#bold)    
    - [Italic](#italic)
    - [Bold and italic](#bold-and-italic)
    - [Strikethrough](#strikethrough)
1. [Blockquotes](#blockquotes)
    - [Single Line Blockquotes](#single-line-blockquote)
    - [Multiple Line Blockquotes](#multiple-line-blockquote)
    - [Nested Blockquotes](#nested-blockquotes)
    - [Blockquotes with other elements](#blockquotes-with-other-elements)
1. [Lists](#lists)
    - [Ordered Lists](#ordered-lists)
    - [Unordered Lists](#unordered-lists)
    - [Mixed Lists](#mixed-lists)
    - [Task Lists](#task-lists)
1. [Code](#code)
1. [Horizontal Rules](#horizontal-rules)
1. [Links](#links)

## Headings

| Markdown           | Output             |
| ------------------ | ------------------ |
| `# Heading 1`      | <h1>Heading 1</h1> |
| `## Heading 2`     | <h2>Heading 2</h2> |
| `### Heading 3`    | <h3>Heading 3</h3> |
| `#### Heading 4`   | <h4>Heading 4</h4> |
| `##### Heading 5`  | <h5>Heading 5</h5> |
| `###### Heading 6` | <h6>Heading 6</h6> |

And more ...

```markdown
Heading 1
=========

Heading 2
---------
```

## Line Breaks

End line with two or more spaces

```markdown
This is first line.  
This is the second line
```

This is first line.  
This is the second line


## Emphasis

### Bold

| Markdown                | Output                |
| ----------------------- | --------------------- |
| `Here is **bold** text` | Here is **bold** text |
| `Here is __bold__ text` | Here is __bold__ text |
| `Here is b**ol**d text` | Here is b**ol**d text |

### Italic

| Markdown                | Output                |
| ----------------------- | --------------------- |
| `Here is *italic* text` | Here is *italic* text |
| `Here is _italic_ text` | Here is _italic_ text |
| `Here is i*tali*c text` | Here is i*tali*c text |

### Bold and Italic

| Markdown                             | Output                             |
| ------------------------------------ | ---------------------------------- |
| `Here is ***bold and italic*** text` | Here is ***bold and italic*** text |
| `Here is ___bold and italic___ text` | Here is ___bold and italic___ text |
| `Here is **_bold and italic_** text` | Here is **_bold and italic_** text |
| `Here is __*bold and italic*__ text` | Here is __*bold and italic*__ text |
| `Here is bold***and***italic text`   | Here is bold***and***italic text   |

### Strikethrough

| Markdown                             | Output                             |
| ------------------------------------ | ---------------------------------- |
| `Here is ~~strikethrough~~ text`     | Here is ~~strikethrough~~ text     |


## Blockquotes

### Single Line Blockquote

```markdown
> This is Blockquote
```

> This is Blockquote

### Multiple Line Blockquote

```markdown
> This is Blockquote
>
> Here is second line 
```

> This is multiline Blockquote
> 
> Here is second line

### Nested Blockquotes

```markdown
> This is multiline Blockquote
>
>> Here is nested Blockquote
```

> This is multiline Blockquote
>
>> Here is nested Blockquote

### Blockquotes with other elements

```markdown
> #### Some heading
>
> - Some list item 1
> - Some list item 2
> - ...
```

> #### Some heading
>
> - Some list item 1
> - Some list item 2
> - ...


##  Lists

### Ordered Lists

```markdown
1. First item
2. Second item
3. ...

1. First item
1. Second item
1. ...

1. First item
5. Second item
9. ...
```

1. First item
2. Second item
3. ...

```markdown
1. First item
2. Second item
    1. First sub item
    2. Second sub item
3. ...
```

1. First item
2. Second item
   1. First sub item    
   2. Second sub item
3. ...

### Unordered Lists

```markdown
- First item
- Second item
- ...

* First item
* Second item
* ...

+ First item
+ Second item
+ ...
```

- First item
- Second item
- ...

```markdown
- First item
- Second item
    - First sub item
    - Second sub item
- ...
```

- First item
- Second item
  - First sub item
  - Second sub item
- ...

### Mixed Lists

```markdown
1. First item
2. Second item
    - First sub item
    - Second sub item
3. ...
```

1. First item
2. Second item
    - First sub item
    - Second sub item
3. ...

### Task Lists

```markdown
- [x] First item
- [x] Second item
- [ ] Third item
- [ ] ...
```

- [x] First item
- [x] Second item
- [ ] Third item
- [ ] ...

## Code

`Here is one line code block`

```markdown
Here is multiline
code block
```

## Horizontal Rules

```markdown
***

---

___
```

***

## Links

| Markdown                                 | Output                                 |
| ---------------------------------------- | -------------------------------------- |
| `[Github](https://github.com)`           | [Github](https://github.com)           |
| `[Github](https://github.com "Tooltip")` | [Github](https://github.com "Tooltip") |
| `<https://github.com>`                   | <https://github.com>                   |
| `![Robot Image](images/robot.jpeg)`      | ![Robot Image](images/robot.jpeg)      |
| `[Links](#links)`                        | [Links](#links)                        |
