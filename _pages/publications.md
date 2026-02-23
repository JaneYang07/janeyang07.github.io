---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md (data-driven; no jekyll-scholar for GitHub Pages) -->

{% include bib_search.liquid %}

<div class="publications">
  {% assign pub_years = site.data.publications | group_by: "year" | sort: "name" | reverse %}
  {% for year_group in pub_years %}
    <h2 class="bibliography">{{ year_group.name }}</h2>
    <ol class="bibliography">
      {% for pub in year_group.items %}
        <li>
          <div class="abbr">
            <abbr>{{ pub.abbr }}</abbr>
          </div>
          <div class="title">{{ pub.title }}</div>
          <div class="author">{{ pub.author }}</div>
          <div class="venue">{{ pub.venue }}</div>
          {% if pub.url or pub.pdf %}
            <div class="links">
              {% if pub.url %}<a href="{{ pub.url }}" target="_blank" rel="noopener">link</a>{% endif %}
              {% if pub.url and pub.pdf %} · {% endif %}
              {% if pub.pdf %}<a href="{{ '/assets/pdf/' | append: pub.pdf | relative_url }}" target="_blank" rel="noopener">pdf</a>{% endif %}
            </div>
          {% endif %}
          {% if pub.note %}<div class="note">{{ pub.note }}</div>{% endif %}
        </li>
      {% endfor %}
    </ol>
  {% endfor %}
</div>
