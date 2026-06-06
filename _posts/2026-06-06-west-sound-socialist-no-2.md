---
layout: post
title: "West Sound Socialist No. 2: Housing"
permalink: /west-sound-socialist-no-2
tag: publication
short_description: "Issue 2: Housing"
show_hero: false
show_author: false
show_toc: false
share: false
gdrive_id: "1Kxsc_Wbm8f7tj8xSQuQHf4EZpZl08mk-"
thumbnail_image: /assets/images/optimized/wss-cover-thumb.jpg
cover_image: /assets/images/optimized/wss-cover-portrait.jpg
cover_image_alt: "West Sound Socialist No. 2 cover"
image_alt: "West Sound Socialist No. 2 thumbnail"
---

<div class="zine-issue-card my-4">
  <div class="zine-issue-menu">
    <div class="zine-issue-menu-actions">
      <a class="btn btn-primary mr-2 mb-2 mb-sm-0" href="https://drive.google.com/file/d/{{ page.gdrive_id }}/view?usp=sharing" target="_blank" rel="noopener">Read Issue</a>
      <a class="btn btn-secondary" href="https://drive.google.com/uc?export=download&id={{ page.gdrive_id }}" target="_blank" rel="noopener">Download PDF</a>
    </div>
  </div>
  <div class="zine-issue-cover-wrap">
    {% if page.cover_image %}
      <img class="zine-issue-cover" src="{{ page.cover_image | relative_url }}" alt="{{ page.cover_image_alt | default: page.title }}">
    {% else %}
      <div class="zine-issue-cover-placeholder">
        <span class="zine-issue-cover-kicker">The West Sound Socialist</span>
        <strong>{{ page.title }}</strong>
        <span>{{ page.short_description }}</span>
      </div>
    {% endif %}
  </div>
</div>
