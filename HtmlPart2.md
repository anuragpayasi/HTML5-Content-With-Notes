# HTML Fundamentals – Day 2  
## HTML Elements & Tags  

---

## 1. HTML Tags  
HTML uses tags to define and display content on a web page.  

- Tags are written inside angle brackets < >  
- Tags tell the browser how to display content  
- Most HTML tags come in pairs  

**Example:**  
```html
<p>This is a paragraph</p>
```

Here:  
- `<p>` → Opening tag  
- `</p>` → Closing tag  

---

## 2. Opening and Closing Tags  

### Opening Tag  
- Starts an HTML element  
- Written without a slash  
```html
<h1>
```

### Closing Tag  
- Ends an HTML element  
- Written with a slash `/`  
```html
</h1>
```

### Complete Example:  
```html
<h1>HTML Elements</h1>
```

### Important Rule  
Most HTML tags must be properly closed to avoid layout issues.

---

## 3. Self-Closing Tags  
Some HTML tags do not have closing tags.  
These are called **self-closing tags**.

### Characteristics  
- Written in a single tag  
- Do not wrap content  
- Mostly used for inserting elements  

### Common Self-Closing Tags  
- `<br>` → Line break  
- `<hr>` → Horizontal line  
- `<img>` → Image  

### Examples  
```html
<p>This is line one<br>This is line two</p>
<hr>
<img src="image.jpg" alt="Sample Image">
```

---

## 4. HTML Elements  
An HTML element consists of:  
- Opening tag  
- Content  
- Closing tag  

**Example:**  
```html
<p>Learning HTML is important</p>
```

Here:  
- `<p>` → Opening tag  
- `Learning HTML is important` → Content  
- `</p>` → Closing tag  

### Tag vs Element  
- **Tag** → `<p>`  
- **Element** → `<p>Content</p>`  

---

## 5. Block-Level Elements  
Block-level elements:  
- Always start on a new line  
- Take full width available  
- Used for layout and structure  

### Common Block Elements  
- `<div>`  
- `<p>`  
- `<h1>` to `<h6>`  
- `<section>`  
- `<article>`  

**Example:**  
```html
<h1>Main Heading</h1>
<p>This is a paragraph.</p>
```
Each element appears on a new line.

---

## 6. Inline Elements  
Inline elements:  
- Do not start on a new line  
- Take only required width  
- Used inside block elements  

### Common Inline Elements  
- `<span>`  
- `<a>`  
- `<strong>`  
- `<em>`  
- `<img>`  

**Example:**  
```html
<p>This is <strong>important</strong> text.</p>
```
The text continues on the same line.

---

## 7. Block vs Inline (Comparison)

| Block Elements        | Inline Elements         |
|----------------------|-------------------------|
| Start on new line    | Stay on same line       |
| Full width           | Content width only      |
| Used for layout      | Used for text & small content |

---

## 8. Practical Example (Mixed Usage)

```html
<div>
    <h2>About HTML</h2>
    <p>HTML is used to create <strong>web pages</strong>.</p>
    <a href="#">Read More</a>
</div>
```

### Explanation  
- `<div>`, `<h2>`, `<p>` → Block elements  
- `<strong>`, `<a>` → Inline elements  

---

## 9. Common Beginner Mistakes  
- Forgetting closing tags  
- Using block elements inside inline elements incorrectly  
- Writing tags without proper structure  
- Confusing tags with elements  

---

## 10. Practice Tasks  

### Simple Task  
Create a page that includes:  
- One heading  
- One paragraph  
- One line break  
- One horizontal line  

### Deep Practice Task  
Create an HTML page with:  
- At least 3 block elements  
- At least 3 inline elements  
- Proper nesting of tags  

### Example idea:  
- Blog intro section  
- Highlighted text  
- Read more link  

---

## 11. Key Takeaways  
- Tags define how content is displayed  
- Elements include tags + content  
- Block elements control layout  
- Inline elements format content  
- Proper structure is mandatory  