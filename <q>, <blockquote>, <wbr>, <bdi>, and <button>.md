1. <q> - Short Inline Quote
Used to add a short quotation inside text. Browsers usually automatically add quotation marks.
Example:
<p>The philosopher said: <q>Knowledge is power</q>.</p>
2. <blockquote> - Block Quote
Used for long quotations. Browsers usually indent blockquotes for emphasis.
Example:
<blockquote>
  "The only limit to our realization of tomorrow is our doubts of today." – Franklin D. Roosevelt
</blockquote>
3. <button> - Clickable Button
Creates an interactive button.
Example:
<button onclick="alert('Button Clicked!')">Click Me</button>
4. <wbr> - Word Break Opportunity
Suggests a line break opportunity in long words or URLs to prevent overflow.
Example:
<p>Visit: https://www.example.com/<wbr>verylongwordthatshouldbreakhere</p>
5. <bdi> - Bi-Directional Isolation
Ensures that text with different text direction (like Arabic or Hebrew) does not affect the surrounding text alignment.
Example:
<p>Username: <bdi>السلام</bdi>123</p>
Without <bdi>, the Arabic word might rearrange the order of the text.
With <bdi>, it preserves the intended structure.
Summary of Code Functionality
This HTML page demonstrates:
✅ Quoting text using <q> and <blockquote>
✅ Creating an interactive button with <button>
✅ Handling long words/URLs using <wbr>
✅ Maintaining correct text direction with <bdi>
