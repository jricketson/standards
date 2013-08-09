---
layout: default
title: Code Category
---

<div id="home">
  <h1>{{ page.title }}</h1>
  <section class="posts">
    <ul class="posts">
      {% for post in site.categories.code %}
        {% include post_summary.html %}
      {% endfor %}
    </ul>
  </section>
</div>
