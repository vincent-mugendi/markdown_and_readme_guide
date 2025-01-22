# **Markdown Basics and Syntax**

Markdown is a lightweight markup language used to create formatted text using a plain-text editor. It's widely used for README files, documentation, and static content. Below is a quick guide to Markdown syntax to help you get started.

---

## **1. Headings**
Use the `#` symbol followed by a space to create headings. Add more `#` symbols to decrease the heading level.

```markdown
# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading
```

### Output:
# H1 Heading
## H2 Heading
### H3 Heading
#### H4 Heading
##### H5 Heading
###### H6 Heading

---

## **2. Emphasis**
- Use `*` or `_` for *italic* text.
- Use `**` or `__` for **bold** text.
- Use `~~` for ~~strikethrough~~ text.

```markdown
*Italic* or _Italic_
**Bold** or __Bold__
~~Strikethrough~~
```

### Output:
*Italic* or _Italic_  
**Bold** or __Bold__  
~~Strikethrough~~

---

## **3. Lists**
### Unordered Lists
Use `-`, `*`, or `+` to create unordered lists.

```markdown
- Item 1
  - Sub-item 1
  - Sub-item 2
- Item 2
```

### Ordered Lists
Use numbers followed by a period for ordered lists.

```markdown
1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2
```

### Output:
- Item 1
  - Sub-item 1
  - Sub-item 2
- Item 2

1. First item
2. Second item
   1. Sub-item 1
   2. Sub-item 2

---

## **4. Links**
Use `[Link Text](URL)` to create hyperlinks.

```markdown
[Google](https://www.google.com)
```

### Output:
[Google](https://www.google.com)

---

## **5. Images**
Use `![Alt Text](Image URL)` to add images.

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

### Output:
![Markdown Logo](https://markdown-here.com/img/icon256.png)

---

## **6. Code Blocks**
### Inline Code
Use backticks (`) for inline code.

```markdown
`inline code`
```

### Block Code
Use triple backticks (\`\`\`) or indent with four spaces for block code. Specify a language for syntax highlighting.

```markdown
```python
print("Hello, World!")
```
```

### Output:
```python
print("Hello, World!")
```

---

## **7. Blockquotes**
Use `>` for blockquotes.

```markdown
> This is a blockquote.
>> Nested blockquote.
```

### Output:
> This is a blockquote.  
>> Nested blockquote.

---

## **8. Tables**
Use pipes (`|`) and hyphens (`-`) to create tables.

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |
```

### Output:
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data 1   | Data 2   | Data 3   |
| Data 4   | Data 5   | Data 6   |

---

## **9. Horizontal Rules**
Use three or more dashes (`---`), asterisks (`***`), or underscores (`___`) to create horizontal rules.

```markdown
---
```

### Output:
---

---

## **10. Escaping Characters**
Use a backslash (`\`) to escape special Markdown characters.

```markdown
\*Not italicized\*
```

### Output:
\*Not italicized\*

---

## **11. Additional Resources**
For more advanced Markdown usage, visit:
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Flavored Markdown](https://github.github.com/gfm/)
