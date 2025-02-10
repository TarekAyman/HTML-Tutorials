### **What are Form Attributes?**

Form attributes **control how form data is processed** when submitted.

- **`action`**: Specifies where to send the form data (e.g., a server script).
- **`method`**: Defines how to send the data (`GET` or `POST`).
- **`name`**: Assigns a name to each field, used to identify form data on the server.

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
    <form action="process.php" method="POST">  <!-- Form submits data to 'process.php' -->

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

      <!-- Submit Button -->
      <input type="submit" value="Save">

    </form>

  </body>
</html>
```
## **Explanation of Key Attributes:**

| **Attribute**          | **Description**                                                    |
| ---------------------- | ------------------------------------------------------------------ |
| `action="process.php"` | Sends form data to **process.php** when submitted.                 |
| `method="POST"`        | Uses **POST** to securely send data (does not show in URL).        |
| `method="GET"`         | Alternative method: data appears in **URL parameters**.            |
| `name="..."`           | Assigns a name to each input field for **server-side processing**. |

## **Why Use These Attributes?**

✅ **Defines where form data goes** (`action`).  
✅ **Controls how data is sent** (`method`).  
✅ **Identifies form fields** for backend processing (`name`).  
✅ **Ensures better security and organization**.
