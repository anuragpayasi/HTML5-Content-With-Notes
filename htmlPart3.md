# HTML Fundamentals – Day 3
# HTML Text & Formatting Tags

## 1. Introduction
HTML gives us different tags to control how text appears on a webpage.  
Some tags make text big, some make it bold or italic, some highlight it, and some show code exactly as we type it.  
These tags help us present content in a clean and readable way.

---

## 2. Heading Tags (h1 to h6)
Heading tags are used to create titles and sections on a page.

### Definition
- Headings show the topic or title of a section.
- h1 is the main heading of the page.
- h6 is the smallest and least important heading.

### Example
```html
<h1>Main Title</h1>
<h3>Sub Topic</h3>
```

---

## 3. Paragraph and Text Break Tags

### a) p (Paragraph)
Used to write normal text in a paragraph.  
Paragraph always appears with space above and below.

```html
<p>This is a paragraph</p>
```

### b) br (Line Break)
Moves text to the next line without starting a new paragraph.

```html
Hello<br>World
```

### c) hr (Horizontal Line)
Creates a horizontal line to separate sections.

```html
<hr>
```

---

## 4. Bold & Emphasis Tags

### a) strong
Shows important text in bold.  
Search engines also consider it important.

```html
<strong>Important message</strong>
```

### b) b
Shows bold text but does not add importance.

```html
<b>Bold text</b>
```

---

## 5. Italic & Emphasis Tags

### a) em
Shows text in italic with meaning — used to stress or emphasize something.

```html
<em>Pay attention here</em>
```

### b) i
Shows italic text visually, without any special meaning.

```html
<i>Italic text</i>
```

---

## 6. More Text Formatting Tags

### a) mark
Highlights text with a yellow background.

```html
<mark>Highlighted text</mark>
```

### b) small
Displays smaller-sized text.

```html
<small>Small note</small>
```

### c) sup (Superscript)
Moves text slightly above the normal line.

```html
10<sup>2</sup>
```

### d) sub (Subscript)
Moves text slightly below the normal line.

```html
H<sub>2</sub>O
```

---

## 7. Code-Related Tags

### a) code
Used to display code or commands in a fixed-width font.

```html
<code>console.log("Hi")</code>
```

### b) pre
Shows text exactly as written — keeps spaces, tabs, and line breaks.

```html
<pre>
Line 1
Line 2
Line 3
</pre>
```

---

## 8. Difference Summary (Easy to remember)

| Tag   | Purpose                      |
|-------|------------------------------|
| h1–h6 | Headings from large to small |
| p     | Paragraph text               |
| br    | New line                     |
| hr    | Horizontal line              |
| strong| Bold + important             |
| b     | Only bold                    |
| em    | Italic + important           |
| i     | Only italic                  |
| mark  | Highlight                    |
| small | Small text                   |
| sup   | Upper text                   |
| sub   | Lower text                   |
| code  | Code display                 |
| pre   | Shows text exactly as typed  |

---

## 9. Common Mistakes Students Make

❌ Using h1 many times  
✔ Only one h1 per page  

❌ Writing text inside `<head>`  
✔ Visible text must be in `<body>`  

❌ Using `<br>` again and again instead of using `<p>`  
✔ Use paragraphs for proper spacing  

❌ Forgetting closing tags  
✔ Always close tags like `</p>`, `</strong>`, `</pre>`  

❌ Not saving file as `.html`  
✔ Correct extension is important  

❌ Mixing `<sub>` and `<sup>`  
✔ sup for upper, sub for lower  

❌ Writing code inside `<p>` instead of `<code>`  
✔ Use `<code>` for code text  

---

## 10. Practice Task  
Create a webpage with:
1. A main heading using h1  
2. One paragraph  
3. One bold (strong) and one italic (em) text  
4. A highlighted line  
5. One sup/sub example  
6. A pre + code example  
7. A horizontal line between two sections  