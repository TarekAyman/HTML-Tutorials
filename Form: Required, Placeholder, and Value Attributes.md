### **What are Form Attributes?**

Form attributes help control **user input** by adding **validation, hints, and default values** to form fields.

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
      
      <!-- Username Input (Required with Placeholder) -->
      <div>
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required placeholder="Enter your username">
      </div>

      <br> <!-- Line Break -->

      <!-- Subject Input (Optional) -->
      <div>
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject">
      </div>

      <br> <!-- Line Break -->

      <!-- Password Input (Required with Placeholder) -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" required placeholder="Write a complex password">
      </div>

      <br> <!-- Line Break -->

      <!-- Email Input (Required with Default Value) -->
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required placeholder="Write a valid email" value="o@nn.sa">
      </div>

      <br> <!-- Line Break -->

      <!-- Submit Button -->
      <input type="submit" value="Save">

    </form>

  </body>
</html>
```

## **Explanation of Key Attributes:**

| **Attribute**       | **Description**                                           |
| ------------------- | --------------------------------------------------------- |
| `required`          | Makes the input **mandatory** before form submission.     |
| `placeholder="..."` | Shows **hint text** inside the input field before typing. |
| `value="..."`       | Sets a **default value** inside the input field.          |
## **Why Use These Attributes?**

✅ **Ensures required fields are filled** before submission.  
✅ **Improves user experience** by guiding input.  
✅ **Reduces errors** by pre-filling common values.  
✅ **Enhances accessibility** with clear form hints.
