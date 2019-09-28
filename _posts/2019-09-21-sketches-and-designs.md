---
layout: post
title:  Sketches and Designs
image:  '/assets/img/07.jpg'
tags:   [art, design]
---
Every piece has a story! See the history and progress of my doodles here.

---
<html>

layout: default
images:
  - image_path: /assets/img/1.jpg
    title: Apple Pie
  - image_path: /assets/img/2.jpg
    title: Birthday Cake
  - image_path: /assets/img/3.jpg
    title: Black Forest
  - image_path: /assets/img/4.jpg
    title: Brownie
  - image_path: /assets/img/5.jpg
    title: Cheese Cake
  - image_path: /assets/img/6.jpg
    title: Chocolate Cake
  - image_path: /assets/img/7.jpg
    title: Fruit Cake
  - image_path: /assets/img/8.jpg
    title: Lamington
  - image_path: /assets/img/9.jpg
    title: Lemon Cake
---
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>

</html>
