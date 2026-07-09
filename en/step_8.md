## Style your header

If you want to apply styling to specific elements, you can create a **class** in a CSS file.

You can then add a `class=` **attribute** to an element in your HTML code to let the browser know what styling should be applied.

Back in your `index.html` file, add `class="border-bottom"` in your `<header>` tag.

```html filename="index.html" line_numbers="true" line_number_start="27" line_highlights="29"
  <body>
    <!-- The page header code goes here -->
    <header class="border-bottom">
      <h1>Draw anime with me</h1>
    </header>

```

> [!TIP]
>
> When you add `class="border-bottom"` in your `<header>` tag, it adds a special border at the bottom of your header.

## Now run your code

Click the **Run** button and check that the header now has a border along the bottom.
