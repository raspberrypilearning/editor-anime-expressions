## Add more styles

Your CSS file has three classes called `primary`, `secondary`, and `tertiary`.

The `primary` class sets a contrasting background and text colour for most of the main content.

Add `class="primary"` to `<main>`.

The colours used by the `primary` class come from the theme variables in your CSS files. This step might not create a big visible change yet, because the `main` rule is already using the same colour pair.

```html filename="index.html" line_numbers="true" line_number_start="33" line_highlights="34"
    <!-- The main content for the webpage goes between the main tags -->
    <main class="primary">

```

## Now run your code

Click the **Run** button and check that the page still opens normally and uses the same main colours as before.
