---
layout: post
title: Photgraphy book from the trekking
date: 2022-05-14
docurl: /pdfs/photos_from_trek.pdf
categories: Photography
---
---

This is a sample blog post 99. 

Aren't headings cool?


I dont know what it does 

<ul>
  {% for post in site.posts %}
    {% if post.docurl %}
      <li><a href="{{ site.baseurl }}{{ post.docurl }}">{{ post.title }}</a></li>
    {% else %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
    {{ post.excerpt }}
  {% endfor %}
</ul>
