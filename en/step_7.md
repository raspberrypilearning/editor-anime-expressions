<h2 class="c-project-heading--task">Style your page</h2>

The next steps show you how to use CSS to change the colours, fonts, and layout on your web page.

--- task ---

Unfold the `<head>` section of your code so that you can view the code inside it.

![The mouse clicks on the little triangle next to the line 3 number to collapse the head code.](images/step_2_collapse.gif)

--- /task ---

--- task ---

At the bottom of your `<head></head>` section, remove the `<!--` and `-->` arrows from the start and end of both lines of link code:

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 21
line_highlights: 23-24
---   
    <!-- Include CSS style file -->

    <link href="style.css" rel="stylesheet" type="text/css" />
    <link href="candy.css" rel="stylesheet" type="text/css" />
  </head>

--- /code ---
</div>