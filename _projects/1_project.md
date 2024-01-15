---
layout: page
title: m.A.A.d. Academy
description: Music as Alternate Discourse
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Founded in 2018, m.A.A.d Academy is the first science fiction universe-city created from studying and annotating music lyrics; it is both a university of science fiction and a university in science fiction.

m.A.A.d academy strictly adheres to and practices m.A.A.d Science

<b>Music As Alternate Discourse</b> Multimodal discourse analysis is an approach to discourse which focuses on how meaning is made through the use of multiple modes of communication as opposed to just language. This includes music production, music theory and implications in pop-culture.

<b>Minds Analyzed And Dissected</b> Psycholinguistics or psychology of language is the study of the psychological and neurobiological factors that enable humans to acquire, use, comprehend and produce language.

<b>Mainly Avant-garde Academic Discipline</b> Science fiction studies is the common name for the academic discipline that studies and researches the history, culture, and works of science fiction and, more broadly, speculative fiction.

<b>Musings of an All-Knowing, All-Powerful Diety</b> Reality warping defies all laws of narrative physics. Here, defying semiotic gravity. Semiotics is the study of meaning-making, significance in language and meaningful communication.

<b>My Angry Adolescence Divided</b> Kendrick Lamar's discography and all related artists starring in m.A.A.d TV are the research data. m.A.A.d TV is a music-television sketch comedy with major themes including living in pandemonium, ego-death, fame and discovering your life's purpose.

<b>Me, an Angel on Angel Dust</b> This is a meta-study of Schizophrenia which is a long-term mental disorder involving a breakdown in the relation between thought, emotion, and behavior. This leads to faulty perception, inappropriate actions and feelings, withdrawal from reality and personal relationships into fantasy and delusion.

The writings are designed to provide insight not only into the mind of Kendrick Lamar, but to bend, stretch and expand the mind of the reader so as to elicit divergent cognition which will enhance creativity and no-doubtedly precipitate madness. They say there's a fine line between genius and madness. At m.A.A.d Academy we say, mAAdness is beyond <a href="https://genius.com/">Genius</a>.

Enjoy your stay.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
