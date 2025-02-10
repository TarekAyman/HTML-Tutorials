#### **Summary & Explanation**

These three elements are useful for **inline styling, line breaks, and horizontal separators** in HTML documents.

#### **Code Explanation with Comments:**

```html
<!doctype html>  <!-- Defines HTML5 document -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding -->
    <title>Book Store</title>  <!-- Page title -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Meta description -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading -->

    <!-- Span Example -->
    <p>This Is <span>My</span> <b>Book Store</b>, Welcome</p>
    <!-- <span> is used for inline styling or grouping elements without breaking the flow -->

    <!-- Break Line Example -->
    <p>This Is Second Paragraph, <br />Test <br />Test Again</p>
    <!-- <br> forces a new line (useful for addresses or poems) -->

    <!-- Horizontal Rule Example -->
    <hr />
    <!-- <hr> creates a horizontal line (used to separate sections) -->

    <p>Second Paragraph</p>  
  </body>
</html>
```

#### **Key Notes:**

1. **`<span>` (Inline Container)**
    
    - Used to apply **CSS styles** or JavaScript effects to a **specific part of text**.
    - It does **not break to a new line** (unlike `<div>`).
    - Example:
        `<p>This is a <span style="color: red;">highlighted</span> word.</p>`
        
2. **`<br>` (Line Break)**
    
    - Inserts a **line break** without creating a new paragraph.
    - Useful for writing **addresses, poetry, or formatting text** inside a `<p>`.
    - Example:
        `<p>Address:<br>123 Street<br>City, Country</p>`
        
3. **`<hr>` (Horizontal Rule)**
    
    - Creates a **horizontal line** to **visually separate content**.
    - Example:
        `<h2>Section 1</h2> <p>Content...</p> <hr> <h2>Section 2</h2>`
        
#### **Best Practices:**

✅ Use `<span>` for **styling inline text**, not for layout control.  
✅ Use `<br>` **sparingly** (for lists or addresses, but not for full layouts).  
✅ Use `<hr>` to **separate sections** where necessary.
