---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---
{% include base_path %}

I teach neuroscience and writing at Cornell as an Instructor of Record for my own first-year writing seminar, *Big Brain Moments*, and as a TA and Head TA for introductory neuroscience and behavior courses. In my classroom, I aim to build curiosity and self-reflection through hands-on learning, revision-based assessment, and a safe, inclusive community where students are willing to take intellectual risks. In 2026, I received Cornell's [Cornelia Ye Outstanding International Teaching Assistant Award](https://news.cornell.edu/stories/2026/07/cti-announces-2026-winners-ye-awards-graduate-achievements-teaching).

{% assign sections = site.teaching | sort: "order" %}
{% for s in sections %}
## [{{ s.title }}]({{ base_path }}{{ s.url }})
{{ s.excerpt | markdownify }}
{% endfor %}
