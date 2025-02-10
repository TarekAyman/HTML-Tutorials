#### **Summary & Explanation**

The `<p>` element in HTML is used to define paragraphs of text. Each `<p>` tag creates a new paragraph, which is displayed on a new line with default spacing around it.

#### **Code Explanation with Comments:**
```html
<!doctype html>  <!-- Defines the document type as HTML5 -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding to support multiple languages -->
    <title>Book Store</title>  <!-- Defines the title of the webpage (appears in the browser tab) -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Provides a short description for search engines -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading of the page -->

    <!-- Paragraph elements: Each <p> tag creates a separate paragraph -->
    <p>This Is My Book Store, Welcome</p>
    <p>We Have A Big Sale</p>

    <!-- These lines are written outside <p> tags, so they will appear on the same line -->
    Line 1
    Line 2
    Line 3
  </body>
</html>
```
#### **Important Notes:**

1. The `<p>` tag automatically adds space above and below the text.
2. If text is written outside of `<p>`, it appears without spacing and continues on the same line.
3. Using multiple `<p>` tags helps in organizing content properly and improving readability.
4. Always use `<p>` for blocks of text instead of writing directly in `<body>`.
