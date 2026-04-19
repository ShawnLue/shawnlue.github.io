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
{% assign sorted_publications = by_date | sort: "year" | reverse %}
{% assign current_year = "" %}

<div class="publications">
{% for post in sorted_publications %}
  {% if post.year %}
    {% assign post_year = post.year %}
  {% else %}
    {% assign post_year = post.date | date: "%Y" %}
  {% endif %}
  {% if post_year != current_year %}
    {% unless forloop.first %}</ul>{% endunless %}
    <h2 class="pub-year">{{ post_year }}</h2>
    <ul class="pub-list">
    {% assign current_year = post_year %}
  {% endif %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
</div>

<p class="pub-footnote"><em>* denotes equal contribution.</em></p>
