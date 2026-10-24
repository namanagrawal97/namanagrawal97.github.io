---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---
{% include base_path %}

A short intro sentence or two about your teaching.

{% assign sections = site.teaching | sort: "order" %}
{% for s in sections %}
## [{{ s.title }}]({{ base_path }}{{ s.url }})
{{ s.excerpt | markdownify }}
{% endfor %}
