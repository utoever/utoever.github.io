---
title: "Jenkins"
layout: category
permalink: /categories/
author_profile: true
taxonomy: jenkins
sidebar:
  nav: "categories"
---

{% if site.tag_archive.type and page.tags[0] %}
  {% include tag-list.html %}
{% endif %}

{% if site.category_archive.type and page.categories[0] %}
  {% include category-list.html %}
{% endif %}
