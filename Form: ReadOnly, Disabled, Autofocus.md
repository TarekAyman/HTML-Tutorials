### **What Are These Attributes?**

HTML provides attributes to **control input behavior** for better user experience and data handling.

- **ReadOnly (`readonly`)**: The input field **cannot be edited**, but its value is sent when the form is submitted.
- **Disabled (`disabled`)**: The input field **cannot be edited or submitted**.
- **Autofocus (`autofocus`)**: Automatically focuses on an input field when the page loads.

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

      <!-- ReadOnly Input: Visible but cannot be edited -->
      <div>
        <label for="username">Username:</label>
        <input type="text" id="username" name="user" value="Osama" readonly required>
      </div>

      <br> <!-- Line Break -->

      <!-- Autofocus Input: The cursor will be placed in this field on page load -->
      <div>
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject" autofocus>
      </div>

      <br> <!-- Line Break -->

      <!-- Password Input with Min and Max Length -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="pass" placeholder="Write a complex password" minlength="10" maxlength="20" required>
      </div>

      <br> <!-- Line Break -->

      <!-- Disabled Input: Cannot be edited or submitted -->
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="mail" value="o@nn.sa" placeholder="Write a valid email" disabled required>
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

## **Explanation of Attributes:**

|**Attribute**|**Description**|
|---|---|
|**ReadOnly** `readonly`|The input field **can be seen but not edited**. The value **is submitted** with the form.|
|**Disabled** `disabled`|The input field **cannot be edited or submitted**.|
|**Autofocus** `autofocus`|The input field **receives focus automatically** when the page loads.|

## **Why Use These Attributes?**

✅ **ReadOnly inputs** help display important information **without allowing modification**.  
✅ **Disabled inputs** prevent users from submitting data **not meant to be changed**.  
✅ **Autofocus** improves user experience by directing attention to the **most important field**.
