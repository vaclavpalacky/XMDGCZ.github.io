---
layout: page
title: Blog
permalink: blog.html

---
{% assign headText = "Nejnovější články" %}

<h2 class="blog-header" > <span>{{ headText }} </span> </h2>
{% include list-posts.html lang=page.lang category="articles" %}
