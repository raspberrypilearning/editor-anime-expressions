<h2 class="c-project-heading--task">Edit your style sheet</h2>

--- task ---

Click on the `Project files` icon in the Code Editor then select the `style.css` file top open in in a new tab.

![The Code Editor with the style.css file highlighted](images/select-style.png)

**Find:** Scroll down and find the rule that controls the style of the `<h2>`. 

At the moment, the `<h2>` heading is aligned to the left.

Change the `text-align` property of the `h2` rule to `center`.

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 109
line_highlights: 111
---  

h2 {
  font: var(--title-font); /* Font style stored in the title-font variable */
  text-align: center; /* Align the text */
  padding: 1.5rem; /* Add some space all around the heading */
}

--- /code ---
</div>

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

When you add CSS styling to an **element**, it applies that styling to every single element on the page that has the same tag. 

</div>

**Test:** Click the **Run** button. 