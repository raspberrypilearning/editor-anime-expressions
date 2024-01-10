<h2 class="c-project-heading--task">Style your header</h2>

--- task ---

If you want to apply styling to specific elements, you can create a **class** in a CSS file. You can then add a `class=` **attribute** to an element in your HTML code to let the browser know what styling should be applied. 

Back in your `index.html` file, add `class="border-bottom"`{:.language-html} in your `<header>`{:.language-html} tag.

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 29
---
  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom">
      <h1>Draw anime with me</h1>
    </header>

--- /code ---
</div>

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

When you add add `class="border-bottom"`{:.language-html} in your `<header>`{:.language-html} tag, it adds a special border at the bottom of our header to make it look cool.

</div>

**Test:** Click the **Run** button. 