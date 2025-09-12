---
layout: default
title: "Research"
permalink: /research/
---

<h1>Research Themes</h1>

<div class="research-list">
  {% assign sorted_research = site.research | sort: 'weight' %}
  {% for item in sorted_research %}
    <div class="research-card">
      <div class="research-image">
        <img src="{{ item.image | relative_url }}" alt="{{ item.title }}">
      </div>
      <div class="research-text">
        <h2>{{ item.title }}</h2>
        <p>{{ item.excerpt }}</p>
        {{ item.content | markdownify }}
      </div>
    </div>
  {% endfor %}
</div>

