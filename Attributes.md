#### **Summary & Explanation**

HTML attributes provide additional information about an element. They are written inside the opening tag and help control how elements behave or appear. Attributes usually come in **name="value"** format.

#### **Code Explanation with Comments:**

```html
<!doctype html>  <!-- Defines the document type as HTML5 -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding to UTF-8 to support different languages -->
    <title>Book Store</title>  <!-- Defines the page title shown in the browser tab -->
    
    <!-- Meta tag with the "name" and "content" attributes to describe the webpage -->
    <meta name="description" content="This Is Our Book Store" />

    <!-- The <link> tag with "rel" and "href" attributes is used to connect an external stylesheet -->
    <link rel="stylesheet" href="">  <!-- "href" should contain the path to a CSS file -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- <h1> element with no attributes, just text content -->

    <p>This Is My Book Store, Welcome</p>  <!-- <p> contains text, but no attributes -->

    <!-- Image element with attributes: -->
    <img decoding="async" src="" alt="">  
    <!-- "src" is the source (URL) of the image -->
    <!-- "alt" provides alternative text if the image fails to load -->
    <!-- "decoding='async'" improves page loading performance -->

    <p></p>  <!-- Empty paragraph, should contain text or be removed -->

    <!-- Anchor (link) element with the "href" attribute for navigation -->
    <a href=""></a>  <!-- "href" should contain the URL to link to -->

    <!-- Audio and Video elements with "src" attributes to specify media files -->
    <audio src=""></audio>  <!-- "src" should point to an audio file -->
    <video src=""></video>  <!-- "src" should point to a video file -->
  </body>
</html>

```
#### **Key Notes on Attributes:**

1. **Attributes modify HTML elements** and provide extra functionality.
2. **Common attributes**:
    - `src` → Specifies the source of media (images, audio, video).
    - `alt` → Provides alternative text for images.
    - `href` → Defines the destination URL for `<a>` (anchor) elements.
    - `rel` → Specifies the relationship between the current document and the linked resource.
3. **Empty attributes (`""`) are incomplete** → They need values to work properly.
4. **Some attributes (like `decoding="async"`) improve performance** by optimizing how resources load.
