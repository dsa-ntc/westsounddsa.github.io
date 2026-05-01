---
layout: page
title: "The West Sound Socialist"
permalink: /the-west-sound-socialist/
---
<p>Spreading the good news of socialism throughout Kitsap County, with a kickass blend of poetry, fiction, non-fiction, and art.</p>

{% assign publications = site.posts | where: "tag", "publication" %}

<div class="row my-4">
  {% if publications.size > 0 %}
    {% for post in publications %}
      <div class="col-12 mb-3">
        <h6 class="my-0 text-black-tint-2">{{ post.date | date: "%b %-d, %Y" }}</h6>
        <a class="my-0 article-link" href="{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.short_description }}</p>
      </div>
    {% endfor %}
  {% else %}
    <div class="col-12">
      <p>No publications have been posted yet.</p>
    </div>
  {% endif %}
</div>

Send submissions, ideas, letters to the editor, or inquiries to:
westsoundsocialist@gmail.com
