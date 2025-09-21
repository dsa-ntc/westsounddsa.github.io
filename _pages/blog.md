---
layout: page
title: "Blog"
permalink: /blog/
---

<h2>West Sound DSA Stands In Solidarity With The Transgender Community</h2>

As we continue to witness the Trump administration’s harshness and brutality against immigrants and other minority groups, including transgender people, we stand for the protection of our comrades. West Sound DSA believes that no part of a person’s identity is an implication of criminality. It does not create a reason to oppress them. It is a part of being human.
We affirm our support for and solidarity with our transgender comrades. They have fought continuous battles for the rights of others and we will not sit idly by as they, or any other group, are put in the line of danger. A brighter future for the working class includes all, especially our transgender comrades.
We hope you'll continue to work with us to support our transgender comrades and other vulnerable communities. 


<div class="row my-5">
  {% for post in site.posts %}
    <div class="col-12">
      <h6 class="my-0 text-black-tint-2">{{ post.date | date: "%b %-d, %Y" }}</h6>
      <a class="my-0 article-link" href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.short_description }}</p>
    </div>
  {% endfor %}
</div>

