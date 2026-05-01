---
layout: page
title: "Statements"
permalink: /statements/
---

<div class="row my-5">
  {% assign statements = site.posts | where: "tag", "statements" %}
  {% for post in statements %}
    <div class="col-12">
      <h6 class="my-0 text-black-tint-2">{{ post.date | date: "%b %-d, %Y" }}</h6>
      <a class="my-0 article-link" href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.short_description }}</p>
    </div>
  {% endfor %}
</div>
