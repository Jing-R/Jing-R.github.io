---
layout: archive
title: "Journal"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.url == "/Journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Conference
====
{% for post in site.publications reversed %}
  {% if post.url == "/Conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


