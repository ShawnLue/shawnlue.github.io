---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
You can also find the full list on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.
{% endif %}

{% assign by_date = site.publications | sort: "date" | reverse %}
{% assign year_groups = by_date | group_by: "year" %}
{% assign sorted_groups = year_groups | sort: "name" | reverse %}

<div class="publications">
{% for group in sorted_groups %}
  <h2 class="pub-year">{{ group.name }}</h2>
  <ul class="pub-list">
  {% for post in group.items %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
{% endfor %}
</div>

<p class="pub-footnote"><em>* denotes equal contribution.</em></p>
