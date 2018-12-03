---
layout: page
title: "Media"
meta_title: "Veröffentlichung in den Medien"
subheadline: "Veröffentlichung in den Medien"
permalink: "/media/"
header:
  image_fullwidth: lager_sw.jpg
image:
  thumb: lager_sw_thumb.jpg
---

Ein Überblick aller medialen Veröffentlichung, die rund um die "Fuck! Die 109 ist weg" Kampagne entstanden sind, und mehr:

<ul>
    {% for post in site.categories.media %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>