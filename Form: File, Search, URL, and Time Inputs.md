### **What Are These Input Types?**

- **`<input type="file">`**: Allows users to **upload files**.
- **`<input type="search">`**: Provides a **search field** optimized for search queries.
- **`<input type="url">`**: Ensures users enter a **valid URL**.
- **`<input type="time">`**: Lets users **select a time**.

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
    <form action="" method="GET">
      
      <!-- File Upload -->
      <div>
        <label for="upload">Upload File:</label>
        <input type="file" id="upload" name="file">
      </div>

      <hr>

      <!-- Search Input -->
      <div>
        <label for="search">Search Books:</label>
        <input type="search" id="search" name="query" placeholder="Search for a book">
      </div>

      <hr>

      <!-- URL Input -->
      <div>
        <label for="url">Website:</label>
        <input type="url" id="url" name="website" placeholder="https://example.com">
      </div>

      <hr>

      <!-- Date Input -->
      <div>
        <label for="date">Pick a Date:</label>
        <input type="date" id="date" name="date">
      </div>

      <hr>

      <!-- Month Input -->
      <div>
        <label for="month">Select Month:</label>
        <input type="month" id="month" name="month">
      </div>

      <hr>

      <!-- Time Input -->
      <div>
        <label for="time">Choose Time:</label>
        <input type="time" id="time" name="time">
      </div>

      <hr>

      <!-- Reset and Submit Buttons -->
      <input type="reset" value="Reset">
      <input type="submit" value="Save">

    </form>

  </body>
</html>
```

## **Explanation of New Input Types:**

|**Element**|**Description**|
|---|---|
|**`<input type="file">`**|Allows users to select and upload a file.|
|**`<input type="search">`**|Optimized search field with a clear (X) button.|
|**`<input type="url">`**|Ensures input is a valid URL format (e.g., `https://example.com`).|
|**`<input type="date">`**|Provides a date picker for selecting a specific date.|
|**`<input type="month">`**|Lets users select a month and year (without a specific day).|
|**`<input type="time">`**|Allows users to input or select a time (hours & minutes).|

## **Why Use These Inputs?**

✅ **Improves user experience** by providing the right input type for each purpose.  
✅ **Enhances form validation** (e.g., `type="url"` prevents invalid URLs).  
✅ **More interactive UI**, especially with file uploads and date/time pickers.
