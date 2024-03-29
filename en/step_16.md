<h2 class="c-project-heading--task">Make it responsive</h2>

--- task ---

CSS can be used to make your web page appear different when viewed on different devices.

Find the **second** `<section>`{:.language-html}. 

Add `class="wrap"`{:.language-html} to the `<section>`{:.language-html} tag.

--- /task ---

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 40
line_highlights: 41
---
    <!-- The first drawing and instructions go here -->
    <section class="wrap">
      <img src="love.png" alt="A line drawing of a smiling character with hearts for eyes.">
      <p>To make your anime character look like they are in love, replace the eyes with two rounded hearts. You can add three more hearts inside for a fun effect.</p>
    </section>

--- /code ---
</div>

**Test:** Click the **Run** button. Adjust the size of the output window to see responsiveness of your page.

![image resized for screen](images/responsive-image.png)