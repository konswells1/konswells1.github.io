---
layout: default
title: "Research"
permalink: /research/
---

<div class="container-fluid page-layout">
  <div class="row">

    <!-- Optional sidebar -->
    <aside class="d-none d-xl-block col-xl-2">
      <!-- Future sidebar content -->
    </aside>

    <!-- Main content -->
    <main class="col-12 col-md-10 offset-md-1 col-xl-8 offset-xl-0 page-main">

      <h1>Research Themes</h1>

      <div class="research-list">
        {% assign sorted_research = site.research | sort: 'weight' %}
        {% for item in sorted_research %}
          <div class="research-card d-flex flex-column flex-md-row mb-4 align-items-start">
            <div class="research-card-image col-12 col-md-4">
              <img class="research-img" src="{{ item.image | relative_url }}" alt="{{ item.title }}">
              </div>
              <div class="research-card-text col-12 col-md-8 mt-3 mt-md-0 ps-md-3">
              <h2>{{ item.title }}</h2>
              <p>{{ item.excerpt }}</p>
              {{ item.content | markdownify }}
            </div>
          </div>
        {% endfor %}
      </div>

    </main>

  </div>
</div>



