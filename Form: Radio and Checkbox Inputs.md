### **What Are These Input Types?**

- **Radio Buttons (`type="radio"`)**: Allow users to select **only one option** from a group.
- **Checkboxes (`type="checkbox"`)**: Allow users to select **multiple options** at the same time.

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
    <form action="" method="GET">  <!-- Form submits data using GET method -->

      <!-- Hidden Input: Not visible to users but sent with form -->
      <input type="hidden" name="hidden_value" value="Osama">

      <!-- ReadOnly Input: Cannot be edited -->
      <div>
        <label for="username">Username:</label>
        <input type="text" id="username" name="user" value="Osama" readonly required>
      </div>

      <br>

      <!-- Autofocus Input: Cursor automatically appears here on page load -->
      <div>
        <label for="subject">Subject:</label>
        <input type="text" id="subject" name="subject" autofocus>
      </div>

      <br>

      <!-- Password Input with Min and Max Length -->
      <div>
        <label for="password">Password:</label>
        <input type="password" id="password" name="pass" placeholder="Write a complex password" minlength="10" maxlength="20" required>
      </div>

      <br>

      <!-- Disabled Email Input: Cannot be edited or submitted -->
      <div>
        <label for="email">Email:</label>
        <input type="email" id="email" name="mail" value="o@nn.sa" placeholder="Write a valid email" disabled required>
      </div>

      <br>

      <!-- Color Picker Input -->
      <div>
        <label for="color">Favorite Color:</label>
        <input type="color" id="color" name="color">
      </div>

      <br>

      <!-- Range Slider Input -->
      <div>
        <label for="range">Range:</label>
        <input type="range" id="range" name="range" min="0" max="100" step="20" value="80">
      </div>

      <br>

      <!-- Number Input -->
      <div>
        <label for="num">Choose a Number:</label>
        <input id="num" type="number" name="number" min="10" max="100" step="10">
      </div>

      <hr>  <!-- Horizontal line for separation -->

      <!-- Radio Buttons: User can select only ONE option -->
      <div>
        <input id="win" type="radio" name="os" value="Windows" checked>
        <label for="win">Windows</label>
      </div>
      <div>
        <input id="lin" type="radio" name="os" value="Linux">
        <label for="lin">Linux</label>
      </div>
      <div>
        <input id="mac" type="radio" name="os" value="Mac">
        <label for="mac">Mac</label>
      </div>

      <hr>  <!-- Horizontal line for separation -->

      <!-- Checkboxes: User can select MULTIPLE options -->
      <div>
        <input id="win1" type="checkbox" name="os1" value="Windows" checked>
        <label for="win1">Windows</label>
      </div>
      <div>
        <input id="lin1" type="checkbox" name="os1" value="Linux">
        <label for="lin1">Linux</label>
      </div>
      <div>
        <input id="mac1" type="checkbox" name="os1" value="Mac">
        <label for="mac1">Mac</label>
      </div>

      <br>

      <!-- Reset and Submit Buttons -->
      <input type="reset" value="Reset">  <!-- Resets all form fields -->
      <input type="submit" value="Save">  <!-- Submits the form -->

    </form>

  </body>
</html>
```

## **Explanation of Radio and Checkbox Inputs:**

|**Attribute**|**Description**|
|---|---|
|**Radio (`type="radio"`)**|Lets the user **choose only one option** from a group.|
|**Checkbox (`type="checkbox"`)**|Lets the user **select multiple options**.|
|**Checked (`checked`)**|Pre-selects an option when the page loads.|

## **Key Differences Between Radio and Checkbox**

|**Feature**|**Radio Button**|**Checkbox**|
|---|---|---|
|**Selection**|Only **one** option can be selected per group.|Multiple options can be selected.|
|**Grouping**|All radio buttons with the **same name** belong to one group.|Each checkbox works independently.|
|**Best Use Case**|Selecting **one preferred option** (e.g., OS type, gender, payment method).|Selecting **multiple applicable options** (e.g., interests, skills, features).|

## **Why Use These Inputs?**

✅ **Radio Buttons** ensure the user selects **only one** option.  
✅ **Checkboxes** allow users to **select multiple choices** when needed.  
✅ **User-friendly** form design helps improve usability and data accuracy.
