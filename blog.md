---
layout: default
title: Chemistry Tips & Updates
permalink: /blog/
---

<section class="hero" style="padding-top: 40px; padding-bottom: 20px;">
  <h1>Chemistry Blog</h1>
  <p class="tagline">Tips, Strategies, and Exam Updates</p>
</section>

<div class="blog-list">
  {% for post in site.posts %}
    <div class="blog-card">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <p class="date" style="color: var(--color-accent); font-size: 0.9rem;">{{ post.date | date: "%B %d, %Y" }}</p>
      <p>{{ post.excerpt }}</p>
      <a href="{{ post.url | relative_url }}" style="font-weight: bold;">Read More &rarr;</a>
    </div>
    <hr style="border-color: rgba(212, 175, 55, 0.2); margin: 30px 0;">
  {% endfor %}
</div>