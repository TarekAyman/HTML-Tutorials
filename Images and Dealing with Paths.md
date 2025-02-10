#### **Summary & Explanation**

The `<img>` tag is used to display images on a webpage. It requires the `src` (source) attribute to specify the image path and the `alt` (alternative text) attribute for accessibility and fallback text when the image is missing.

#### **Code Explanation with Comments:**

```html
<!doctype html>  <!-- Defines the document type as HTML5 -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding to UTF-8 -->
    <title>Book Store</title>  <!-- Page title -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Meta description -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading -->

    <p>This Is My <b>Book Store</b>, Welcome</p>  <!-- Paragraph with bold text -->

    <!-- Image 1: Absolute URL (External Image) -->
    <img decoding="async"
      src="https://elzero.org/wp-content/uploads/2018/06/cover-speed-website.png"
      alt="Speed Website Cover"
      width="200px"
      height="200px">
    <!-- "src" points to an image hosted on another website -->
    <!-- "alt" provides alternative text -->
    <!-- "width" and "height" define the size (can be set in pixels or percentages) -->

    <!-- Image 2: Relative Path (Local Image) -->
    <img decoding="async" src="imgs/home/cover-speed-website.png" alt="Local Image">
    <!-- "imgs/home/" means the image is inside the "home" folder inside "imgs" -->

    <!-- Image 3: Parent Directory Path -->
    <img decoding="async" src="../cover-speed-website.png" alt="Will Not Show">
    <!-- "../" moves one folder up in the directory structure -->
    <!-- If the file is not found, the image won't be displayed -->

    <!-- Image 4: Missing Image -->
    <img decoding="async" src="missing-image.png" alt="Logo Testing">
    <!-- If "missing-image.png" does not exist, the alt text "Logo Testing" will appear -->
  </body>
</html>
```

#### **Key Notes on Image Paths:**

1. **Absolute URL (External Image)**
    
    - Uses a full URL (`https://example.com/image.png`).
    - The image is loaded from another website.
2. **Relative Path (Local Image)**
    
    - Refers to an image stored within the project folder.
    - Example: `src="imgs/home/image.png"` → Inside `imgs/home/`.
3. **Parent Directory Path (`../`)**
    
    - Moves up one folder level.
    - Example: `src="../image.png"` → Moves one step back to the parent folder.
4. **Missing Images & `alt` Attribute**
    
    - If the image does not exist, the `alt` text is displayed.
    - Good for accessibility and SEO.

#### **Notes :**

- Always use **meaningful `alt` text** for better accessibility.
- **Avoid broken image links** by checking paths carefully.
- Use **relative paths** for project images to avoid dependency on external sources.
