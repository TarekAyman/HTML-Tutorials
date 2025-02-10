#### **Summary & Explanation**

Tables in HTML are used to display data in a structured **row-column** format.  
They are useful for organizing information like reports, schedules, and pricing tables.
#### **Code Explanation with Comments:**

```html
<!doctype html>  <!-- Defines HTML5 document -->
<html>
  <head>
    <meta charset="UTF-8" />  <!-- Sets character encoding -->
    <title>Book Store</title>  <!-- Page title -->
    <meta name="description" content="This Is Our Book Store" />  <!-- Meta description -->
  </head>
  <body>
    <h1>Book Store</h1>  <!-- Main heading -->
    <p>This Is My <b>Book Store</b>, Welcome</p>  <!-- Paragraph with bold text -->

    <!-- Table Structure -->
    <table border="1">  <!-- Creates a table with a border -->
      <caption>
        Students Marks  <!-- Table title -->
      </caption>

      <!-- Table Header Row -->
      <tr>
        <th>First</th>  <!-- Table header cell (bold & centered by default) -->
        <th>Last</th>
        <th>Marks</th>
      </tr>

      <!-- Table Data Rows -->
      <tr>
        <td>Osama</td>  <!-- Table data cell -->
        <td>Mohamed</td>
        <td>40</td>
      </tr>
      <tr>
        <td>Osama</td>
        <td>Mohamed</td>
        <td>40</td>
      </tr>
      <tr>
        <td>Osama</td>
        <td>Mohamed</td>
        <td>40</td>
      </tr>
      <tr>
        <td>Osama</td>
        <td>Mohamed</td>
        <td>40</td>
      </tr>

      <!-- Row with Merged Cells -->
      <tr>
        <td colspan="2">Total</td>  <!-- colspan="2" makes the cell span 2 columns -->
        <td>160</td>
      </tr>
    </table>
  </body>
</html>

```
#### **Key Notes on Tables:**

1. **Table Structure Elements**
    
    - `<table>` → Creates a table.
    - `<caption>` → Adds a title to the table.
    - `<tr>` → Table Row.
    - `<th>` → Table Header Cell (bold by default).
    - `<td>` → Table Data Cell (regular content).
2. **Table Formatting**
    
    - `border="1"` → Adds a border to the table (for testing, but better done with CSS).
    - `colspan="2"` → Merges two columns into one.
3. **Best Practices**
    
    - Use **CSS instead of `border="1"`** for better styling.
    - Organize tables using `<thead>`, `<tbody>`, and `<tfoot>` for better readability.

### **Improved Table with `<thead>`, `<tbody>`, and `<tfoot>`**

```html
<table border="1">
  <caption>Students Marks</caption>
  <thead>
    <tr>
      <th>First</th>
      <th>Last</th>
      <th>Marks</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Osama</td>
      <td>Mohamed</td>
      <td>40</td>
    </tr>
    <tr>
      <td>Ali</td>
      <td>Hassan</td>
      <td>50</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Total</td>
      <td>90</td>
    </tr>
  </tfoot>
</table>
```
