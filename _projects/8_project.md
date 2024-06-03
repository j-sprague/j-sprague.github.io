---
layout: page
title: Wordle
description: Command-line version of Wordle, along with an algorithm that helps find the daily Wordle's answer
importance: 5
category: personal
---

Version of Wordle entirely playable within the command-line. Differently colored text may not show properly on Git; tested with PowerShell. Player can choose between 4, 5, or 6 letter words. All the words are ripped from their respective text file located in the repository. ("4c_word_list.txt")

Includes another Python script, "fun_killer.py" which helps find the solution to a Wordle based on information you already know: letters that aren't in the word, letters that are in the word with an unknown position, and letters that are in the word at a confirmed position.

<a href="https://github.com/j-sprague/Wordle">Repository Link</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/wordle.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Demo of command-line wordle being played. User input is entered after the colons on each line where one is present.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fun_killer.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Demo of fun_killer script and how it can assist you find the answer of a Wordle.
</div>

