### **What Are These Input Types?**

HTML provides different input types to handle various types of user input efficiently.

- **Hidden (`<input type="hidden">`)**: Stores data without showing it to the user.
- **Reset (`<input type="reset">`)**: Resets all form fields to their initial values.
- **Color (`<input type="color">`)**: Allows users to select a color.
- **Range (`<input type="range">`)**: Creates a slider for numerical values.
- **Number (`<input type="number">`)**: Allows users to input only numerical values.

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

    <!-- Form Section -->
    <form action="" method="GET">  <!-- Form submits data using the GET method -->

      <!-- Hidden Input: Not visible to users, but sent with the form -->
      <input type="hidden" name="hidden_value" value="Osama">

      <!-- Username Input -->
      <div>
        <label for="username">Username:</label>
        <input type="text" id="username" name="user" required placeholder="Enter your username">
      </div>

      <br> <!-- Line Break -->

      <!-- Subject Input -->
      <div>
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject">
      </div>

      <br> <!-- Line Break -->

      <!-- Password Input -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="pass" required placeholder="Write a complex password">
      </div>

      <br> <!-- Line Break -->

      <!-- Email Input -->
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="mail" required placeholder="Write a valid email" value="o@nn.sa">
      </div>

      <br> <!-- Line Break -->

      <!-- Color Picker Input -->
      <div>
        <label for="color">Favorite Color:</label>
        <input type="color" id="color" name="color">
      </div>

      <br> <!-- Line Break -->

      <!-- Range Slider Input -->
      <div>
        <label for="range">Range:</label>
        <input type="range" id="range" name="range" min="0" max="100" step="20" value="80">
      </div>

      <br> <!-- Line Break -->

      <!-- Number Input -->
      <div>
        <label for="number">Choose a Number:</label>
        <input type="number" id="number" name="number" min="10" max="100" step="10">
      </div>

      <br> <!-- Line Break -->

      <!-- Reset and Submit Buttons -->
      <input type="reset" value="Reset">  <!-- Resets all form fields -->
      <input type="submit" value="Save">  <!-- Submits the form -->

    </form>

  </body>
</html>
```

## **Explanation of Input Types:**

|**Input Type**|**Description**|
|---|---|
|**Hidden** `<input type="hidden">`|Stores a value that is **not visible** to the user but is sent when the form is submitted.|
|**Reset** `<input type="reset">`|Clears all form inputs and resets them to **default values**.|
|**Color** `<input type="color">`|Displays a **color picker** to select a color.|
|**Range** `<input type="range">`|Creates a **slider** for selecting a value within a range.|
|**Number** `<input type="number">`|Allows only **numerical values**, with **min, max, and step** constraints.|
## **Why Use These Inputs?**

✅ **Hidden values** can be used to store session data.  
✅ **Reset button** provides an easy way to clear form fields.  
✅ **Color input** improves user experience with a **built-in picker**.  
✅ **Range input** is great for **volume control, brightness, and other sliders**.  
✅ **Number input** **restricts** users to entering **only numbers**.
