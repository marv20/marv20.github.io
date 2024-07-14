---
layout: page
title: Flowers
description: with background image
img: assets/img/t1.jpg
height: 
importance: 1
category: fun
related_publications: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="position: relative; width: 100%; height: 200px; overflow: hidden;">
        {% include figure.liquid loading="eager" path="assets/img/b1.jpg" title="example image" class="img-fluid rounded z-depth-1" style="position: absolute; top: 50%; left: 50%; height: 100%; width: 100%; object-fit: cover; transform: translate(-50%, -50%);" %}
    </div>
    <div class="col-sm mt-3 mt-md-0" style="position: relative; width: 100%; height: 200px; overflow: hidden;">
        {% include figure.liquid loading="eager" path="assets/img/b2.jpg" title="example image" class="img-fluid rounded z-depth-1" style="position: absolute; top: 50%; left: 50%; height: 100%; width: 100%; object-fit: cover; transform: translate(-50%, -50%);" %}
    </div>
    <div class="col-sm mt-3 mt-md-0" style="position: relative; width: 100%; height: 200px; overflow: hidden;">
        {% include figure.liquid loading="eager" path="assets/img/b3.jpg" title="example image" class="img-fluid rounded z-depth-1" style="position: absolute; top: 50%; left: 50%; height: 100%; width: 100%; object-fit: cover; transform: translate(-50%, -50%);" %}
    </div>
</div>

<div class="caption">
    Cherry Blossom Sunrise 2024 from the Tidal Basin Washington, DC
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/b4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Cherry Blossom First Sunrise 2024 from the Tidal Basin Washington, DC
</div>

You can also put regular text

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/b5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/kite.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
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
