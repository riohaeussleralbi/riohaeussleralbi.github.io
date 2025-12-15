---
layout: page
title: Semiorthogonal decomposition of stable $\infty$-categories.
description: Work in progress, advised by [Prof. Dr. Tobias Dyckerhoff](https://www.math.uni-hamburg.de/home/dyckerhoff/).
img: assets/img/beilinsonsod_img.jpg
importance: 1
category: work
related_publications: false
---

Semiorthogonal decompositions of triangulated categories, first introduced by Bondal and Kapranov in 1989, have been a central tool in the study of derived categories for a long time. They give a systematic way to divide triangulated categories, e.g. the derived category $D^b(X)$ of coherent sheaves on an algebraic variety $X$ (or more generally a noetherian scheme), into simpler pieces. Perhaps most importantly, a semiorthogonal decomposition of a triangulated category $\mathcal T$ yields a direct sum decomposition of its $K$-theory $K(\mathcal T)$.

A natural (but vague) question in this context is the following: Given a semiorthogonal decomposition $\langle \mathcal A_0, \dots, \mathcal A_n \rangle$ of $\mathcal T$, what is a natural condition to impose so that $\mathcal T$ is reconstructible from the subcategories $\mathcal A_0, \dots, \mathcal A_n$ together with some form of gluing data? It turns out that if all of the inclusions of the subcategories $\mathcal A_0, \dots, \mathcal A_n$ admit left adjoints, then the subcategories form a lax $n$-simplex, i.e. a strictly unitary lax functor $[n] \to \mathcal Cat$ into the $2$-category of (small) categories. One would hope that $\mathcal T$ is then determined by this lax functor. However, essentially due to the non-functoriality of the cone, a calculation to reconstruct $\mathcal T$ fails.

<!-- <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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

{% endraw %} -->
