### **What is the `<audio>` Element?**

The `<audio>` element is used to embed sound in a webpage. It supports multiple formats and provides controls for users to play, pause, and adjust the volume.

### **Simple Code Example:**

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

    <!-- Audio Element -->
    <audio controls autoplay loop muted>
      <source src="media/one_way_ticket.mp3" type="audio/mpeg">  <!-- MP3 format -->
      <source src="media/one_way_ticket.ogg" type="audio/ogg">  <!-- OGG format -->
      <source src="media/one_way_ticket.wav" type="audio/wav">  <!-- WAV format -->
      Your browser does not support the audio element.  <!-- Fallback message -->
    </audio>
    
  </body>
</html>

```
### **Explanation of Attributes:**

|**Attribute**|**Description**|**Example**|
|---|---|---|
|`<audio>`|Defines an audio player in HTML.|`<audio>...</audio>`|
|`controls`|Displays the play, pause, and volume controls.|`<audio controls></audio>`|
|`autoplay`|Starts playing the audio automatically.|`<audio autoplay></audio>`|
|`loop`|Repeats the audio after it ends.|`<audio loop></audio>`|
|`muted`|Starts the audio without sound.|`<audio muted></audio>`|
|`<source>`|Defines the audio file and format.|`<source src="file.mp3" type="audio/mpeg">`|
|Fallback Text|Displays text if the browser doesn’t support `<audio>`.|`Your browser does not support the audio element.`|

### **Why Use `<audio>`?**

✅ Supports multiple file formats for browser compatibility.  
✅ Provides built-in controls for user interaction.  
✅ Enhances user experience with background music or notifications.  
✅ Works on all modern browsers.
