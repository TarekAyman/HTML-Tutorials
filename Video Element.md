### **What is the `<video>` Element?**

The `<video>` element in HTML allows you to embed videos directly on a webpage. You can provide multiple formats to ensure compatibility across different browsers.

## **Example Code:**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding -->
    <title>Book Store</title>  <!-- Page title -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Meta description -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading -->
    <p>This Is My <b>Book Store</b>, Welcome</p>  <!-- Paragraph with bold text -->

    <!-- Video Element -->
    <video controls width="600" height="400" autoplay loop muted poster="imgs/home/cover-speed-website.png">
      <source src="media/ghosts.mp4" type="video/mp4">  <!-- MP4 format -->
      <source src="media/ghosts.ogg" type="video/ogg">  <!-- OGG format -->
      Your browser does not support the video tag.  <!-- Fallback message -->

      <!-- Subtitles / Captions -->
      <track src="my_file_en.vtt" kind="subtitles" srclang="en" label="English">
      <track src="my_file_it.vtt" kind="subtitles" srclang="it" label="Italian">
    </video>

  </body>
</html>

```

## **Explanation of Video Attributes:**

|**Attribute**|**Description**|
|---|---|
|`controls`|Displays play, pause, volume, and other controls.|
|`autoplay`|Automatically starts playing when the page loads.|
|`loop`|Repeats the video when it finishes.|
|`muted`|Starts the video without sound.|
|`poster`|Displays an image before the video starts playing.|
|`<source>`|Specifies the video file (different formats for compatibility).|
|`<track>`|Adds subtitles or captions for accessibility.|

## **Why Use the `<video>` Element?**

✅ **No Need for Plugins** (like Flash).  
✅ **Supports Multiple Formats** (MP4, OGG, WebM).  
✅ **Improves Accessibility** with captions.  
✅ **Customizable with JavaScript & CSS.**
