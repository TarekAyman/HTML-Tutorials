### **1. ARIA (Accessible Rich Internet Applications)**

ARIA attributes help improve accessibility by providing additional information to **screen readers** and assistive technologies.

### **2. Proper Heading Structure (`<h1>`, `<h2>`, `<h3>`)**

- **Semantic headings** (`<h1>`, `<h2>`, `<h3>`) improve navigation for screen readers.
- Helps users understand the page structure.

Example:

```html
<h1>Book Title</h1>
<h3>Chapter One</h3>
<h2>Inside Chapter One</h2>
```

✅ **Correct usage:** Headings are in a logical order.
### **3. `<p>` vs `<div>` for Readable Content**

- **Problem:** The `<div>` inside the body contains text that should be inside a `<p>`.
- **Fix:** Replace `<div>` with `<p>` for better screen reader interpretation.

❌ **Incorrect:**

```html
<div>
  Lorem ipsum dolor sit amet, consectetur adipisicing elit...
</div>
```

✅ **Correct:**

```html
<p>
  Lorem ipsum dolor sit amet, consectetur adipisicing elit...
</p>
```
### **4. `<input type="checkbox">` vs ARIA Checkbox**

✅ **Standard Checkbox (Better for Screen Readers):**

```html
<label for="skill1">Skill One</label>
<input id="skill1" type="checkbox" checked />
```
- **Built-in accessibility** (focusable, clickable, and announced correctly).

❌ **Custom ARIA Checkbox (Less Ideal)**

```html
<div role="checkbox" aria-checked="true" tabindex="0" aria-labelledby="plan1">Plan One</div>
<label id="plan1">Plan One Label</label>
```
- Requires additional JavaScript to make it fully functional.
- Not as user-friendly as a standard checkbox.

**Recommendation:** If possible, use **native `<input type="checkbox">`** instead of `role="checkbox"`.
### **5. `aria-labelledby` for Labels**

- Connects text labels with elements for screen readers.
- Example:

```html
<div role="checkbox" aria-checked="true" tabindex="0" aria-labelledby="plan1">Plan One</div>
<label id="plan1">Plan One Label</label>
```

✅ **Screen readers will read:**  
📢 _"Plan One, Checked"_
### **6. `tabindex="0"` for Keyboard Navigation**

- Allows users to navigate `div` elements using the **Tab key**.
- Example:

```html
<div tabindex="0">Plan Two</div>
<div tabindex="0">Plan Three</div>
```

✅ **Users can focus on these elements using the keyboard.**
### **Summary of Accessibility Improvements**

✅ **Use semantic headings** (`<h1>`, `<h2>`, `<h3>`) for structure.  
✅ **Replace `<div>` with `<p>`** for readable text.  
✅ **Use standard `<input type="checkbox">`** instead of `role="checkbox"`.  
✅ **`aria-labelledby` improves screen reader labels.**  
✅ **`tabindex="0"` allows keyboard focus on non-input elements.**
