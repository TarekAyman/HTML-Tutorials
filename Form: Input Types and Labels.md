### **What is an HTML Form?**

An **HTML form** allows users to input data that can be sent to a server for processing. It includes elements like text fields, buttons, checkboxes, and more.

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
    <form>
      
      <!-- Username Input -->
      <div>
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" placeholder="Enter your username">
      </div>

      <br> <!-- Line Break -->

      <!-- Password Input -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password">
      </div>

      <br> <!-- Line Break -->

      <!-- Submit Button -->
      <input type="submit" value="Login">

    </form>

  </body>
</html>

```

## **Explanation of Form Elements:**

|**Element**|**Description**|
|---|---|
|`<form>`|Defines an input form to collect user data.|
|`<label>`|Describes the input field (linked to the input using `for`).|
|`<input type="text">`|Text field for entering a username.|
|`<input type="password">`|Password field that hides input characters.|
|`<input type="submit">`|Button to submit the form data.|
|`placeholder="..."`|Provides a hint inside the input field.|

## **Why Use Forms in HTML?**

✅ **Collects user input** for login, registration, feedback, etc.  
✅ **Improves accessibility** with proper labels.  
✅ **Enhances user experience** with placeholders and validation.  
✅ **Integrates with backend systems** to process data.
