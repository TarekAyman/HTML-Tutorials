### **1. `<code>` - Inline Code Display**

- Used to **display programming code** in a monospace font.
- Example:
```html
<code>var x = 10; var y = 20; console.log(x + y);</code>
```
- Displays code **inline** without preserving formatting.
### **2. `<pre>` - Preformatted Text**

- Displays text **exactly as written in the HTML**, including spaces and new lines.
- Example:
```html
<pre>
  This Is
  P
  New Line
  New Line
</pre>
```
- Unlike `<p>`, it **preserves** line breaks and spaces.
### **3. `<pre><code>` - Code Block with Formatting**

- Used to **combine `<pre>` and `<code>`** to show properly formatted, indented code.
- Example:
```html
<pre>
  <code>
    var x = 10;
    var y = 20;
    console.log(x + y);
  </code>
</pre>
```
- Ensures **code indentation is preserved**.
### **4. `<iframe>` - Embed External Content**

- Embeds **another webpage inside the current page**.
- Example:
```html
<iframe src="https://elzero.org/" width="800" height="400"></iframe>
```
-  Loads **Elzero's website** inside a frame **800x400 pixels**.
- Used for **videos, maps, and external pages**.
### **Summary of Code Functionality**

✅ **Display code snippets** with `<code>` and `<pre><code>`  
✅ **Preserve text formatting** with `<pre>`  
✅ **Embed external websites** using `<iframe>`
