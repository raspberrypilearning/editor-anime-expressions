## Edit your style sheet

![The 'Project files' panel open in the Code Editor, with the 'Project files' icon highlighted.](images/select-style.png)

Select the `style.css` file to open it in a new tab.


**Find:** Scroll down and find the rule that controls the style of the `<h2>` heading. 

At the moment, the `<h2>` heading is aligned to the left. Change the code so that the heading is centred.

```css filename="style.css" line_numbers="true" line_number_start="109" line_highlights="111"

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: center; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

```

> [!TIP]
>
> When you add CSS styling to an **element**, it applies that styling to every single element on the page that has the same tag.

## Now run your code

Click the **Run** button and check that the "Facial expressions" heading is centred.
