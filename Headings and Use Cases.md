In HTML, headings (`h1` to `h6`) are used to structure content hierarchically. They provide a way to define titles, chapters, sections, and subsections in a webpage. The most important heading is `h1`, and as the number increases (`h2` to `h6`), the importance decreases.
### Example Code:
```html
<!doctype html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Book Store</title>
    <meta name="description" content="This Is Our Book Store" />
  </head>
  <body>
    <!-- h1 - h6 -->
    <h1>Book Store</h1> <!-- Main title of the webpage -->
    <h2>Chapter Title Inside Book</h2> <!-- Subsection under main title -->
    <h3>Story Title Inside Chapter</h3> <!-- A section within the chapter -->

    <h4>Book Store</h4> <!-- Lower-level heading for smaller subsections -->
    <h5>Book Store</h5> <!-- Even more specific subsections -->
    <h6>Book Store</h6> <!-- The least important heading, usually for minor sections -->
    This Is My Book Store, Welcome
  </body>
</html>
```
### Headings Summary:
1. **`<h1>`**: Main title of the page. Should be unique and descriptive of the content.
2. **`<h2>`**: For major subsections or chapters.
3. **`<h3>`**: For sections inside subsections (e.g., story titles inside chapters).
4. **`<h4>` to `<h6>`**: For smaller subsections or details inside major sections.
### Use Cases:
- **`<h1>`**: To define the main title of a webpage (only one per page for SEO).
- **`<h2>`**: To define major sections, like chapters in a book or major content categories.
- **`<h3>`**: To define smaller sections inside major content.
- **`<h4>` - `<h6>`**: To further break down sections into increasingly smaller subsections.
