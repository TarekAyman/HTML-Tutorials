#### **Summary & Explanation**

HTML provides various formatting elements to style and structure text. These elements help emphasize, modify, or distinguish parts of the text.

#### **Code Explanation with Comments:**

```html
<!doctype html>  <!-- Defines the document type as HTML5 -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding to support multiple languages -->
    <title>Book Store</title>  <!-- Defines the page title shown in the browser tab -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Description for search engines -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading of the page -->

    <!-- Bold and Strong (Important) Text -->
    <p>This Is My <b>Book Store</b>, Welcome</p>  <!-- <b> makes text bold but does not add importance -->
    <p>This Is My <strong>Book Store</strong>, Welcome</p>  <!-- <strong> makes text bold and adds semantic importance -->

    <!-- Italic and Emphasized Text -->
    <p>This Is My <i>Book Store</i>, Welcome</p>  <!-- <i> makes text italic for styling -->
    <p>This Is My <em>Book Store</em>, Welcome</p>  <!-- <em> makes text italic and adds emphasis (important for accessibility) -->

    <!-- Highlighted and Underlined Text -->
    <p>This Is My Book Store, <mark>Welcome</mark></p>  <!-- <mark> highlights text with a background color -->
    <p>This Is My Book Store, <u>Welcome</u></p>  <!-- <u> underlines the text -->

    <!-- Small, Deleted, and Inserted Text -->
    <p>This Is My Book Store, <small>Welcome</small></p>  <!-- <small> makes text smaller -->
    <p>This Is My <del>Book Store</del>, Welcome</p>  <!-- <del> represents deleted text (strikethrough) -->
    <p><del>$100</del> $80</p>  <!-- Example: Showing a discounted price -->

    <p>This Is My <ins>Book Store</ins>, Welcome</p>  <!-- <ins> represents inserted text (underlined by default) -->

    <!-- Subscript and Superscript -->
    <p>h<sub>2</sub>o</p>  <!-- <sub> makes text smaller and lowered (used in chemical formulas) -->
    <p>2<sup>2</sup></p>  <!-- <sup> makes text smaller and raised (used in exponents) -->
  </body>
</html>
```

#### **Key Notes:**

1. **Bold Elements:**
    
    - `<b>` → Bold text (for styling only, no extra meaning).
    - `<strong>` → Bold text **with importance** (used for important content).
2. **Italic Elements:**
    
    - `<i>` → Italic text (for styling only).
    - `<em>` → Italic text **with emphasis** (important for screen readers and accessibility).
3. **Other Formatting Elements:**
    
    - `<mark>` → Highlights text.
    - `<u>` → Underlines text (not recommended for links to avoid confusion).
    - `<small>` → Makes text smaller.
    - `<del>` → Strikethrough (deleted content).
    - `<ins>` → Underlined (inserted content).
    - `<sub>` → Subscript (H₂O, chemical formulas).
    - `<sup>` → Superscript (², exponents).

#### **Notes:**

- **Use semantic elements** (`<strong>`, `<em>`, `<del>`, `<ins>`) when meaning is important.
- **Use `<b>` and `<i>` sparingly** for styling, since they do not add extra meaning.
- **Avoid `<u>` for normal text** to prevent confusion with links.
