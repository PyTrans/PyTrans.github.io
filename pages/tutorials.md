---
layout: page
show_meta: false
title: "Welcome to the tutorials!"
subheadline: "Gategoires"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/tutorials/"
---
<ul>
    {% for post in site.categories.Tutorials %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ pages.url }}">{{ pages.title }}</a></li>
    {% endfor %}
</ul>