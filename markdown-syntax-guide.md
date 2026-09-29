# Markdown (.md) Syntax Guide

A quick reference for the most commonly used Markdown formatting elements.

---

## 1. Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
```

---

## 2. Text Formatting

| Syntax | Result |
|---|---|
| `**bold text**` | **bold text** |
| `*italic text*` | *italic text* |
| `***bold italic***` | ***bold italic*** |
| `~~strikethrough~~` | ~~strikethrough~~ |
| `` `inline code` `` | `inline code` |

---

## 3. Lists

**Unordered list:**
```
- Item 1
- Item 2
  - Nested item
```

**Ordered list:**
```
1. First item
2. Second item
3. Third item
```

**Task list (checkboxes):**
```
- [x] Completed task
- [ ] Pending task
```

---

## 4. Links and Images

```
[Link text](https://example.com)
![Alt text](image.png)
```

---

## 5. Code Blocks

Inline code uses single backticks: `` `code` ``

Fenced code blocks use triple backticks, with an optional language name for syntax highlighting:

<pre>
```python
print("Hello World")
```
</pre>

---

## 6. Blockquotes

```
> This is a quote
> Second line of the quote
```

---

## 7. Horizontal Rule (divider line)

```
---
```

---

## 8. Tables

```
| Name   | Age |
|--------|-----|
| Adarsh | 20  |
| Ravi   | 22  |
```

---

## 9. Escaping Special Characters

To show a symbol literally instead of triggering formatting, put a backslash before it:

```
\*not italic\*
\# not a heading
```

---

## 10. Line Breaks

- End a line with **two trailing spaces** to force a line break.
- Leave a **blank line** between text to start a new paragraph.

---

*This file itself is written in Markdown — open it in any Markdown viewer/editor to see the formatting rendered.*
