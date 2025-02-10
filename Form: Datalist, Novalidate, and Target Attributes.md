## **New Features in This Form:**

### 1️⃣ **Datalist (`<datalist>`)**

- Provides **autocomplete suggestions** for an input field.
- Works like a dropdown list but allows **free text input**.

### 2️⃣ **Novalidate (`novalidate`)**

- Disables **browser validation**, allowing the form to be submitted even if required fields are empty or invalid.

### 3️⃣ **Target (`target="_blank"`)**

- Opens the **form submission in a new tab** instead of the same page.

## **Example Code:**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Book Store</title>
    <meta name="description" content="This Is Our Book Store">
  </head>
  <body>
    <h1>Book Store</h1>
    <p>Welcome to our <b>Book Store</b>!</p>

    <!-- Form Section -->
    <form action="" method="GET" novalidate target="_blank">
      
      <!-- Datalist Example -->
      <div>
        <label for="prog">Programming Language:</label>
        <input list="programming" id="prog" name="language" placeholder="Choose or type">
        
        <datalist id="programming">
          <option value="Python">
          <option value="PHP">
          <option value="C#">
          <option value="C">
          <option value="C++">
          <option value="Scala">
        </datalist>
      </div>

      <hr>

      <!-- Submit and Reset Buttons -->
      <input type="reset" value="Reset">
      <input type="submit" value="Save">

    </form>
  </body>
</html>
```

## **Explanation of New Features:**

|**Feature**|**Description**|
|---|---|
|**`<datalist>`**|Provides a list of **predefined options** for an input field, but still allows free text input.|
|**`novalidate`**|Disables **built-in form validation**, allowing submission even if fields are incomplete or invalid.|
|**`target="_blank"`**|Opens the form submission in a **new tab/window** instead of the same page.|

## **Why Use These Features?**

✅ **Datalist** improves user experience by offering **autocomplete suggestions**.  
✅ **Novalidate** is useful for testing forms **without validation restrictions**.  
✅ **Target="_blank"** helps in **preventing page reloads**, useful in multi-step forms.
