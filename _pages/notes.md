---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: false
---

{% include base_path %}

{% for post in site.notes %}
  {% include archive-single.html %}
{% endfor %}

These are all my notes pertaining to any subject where I felt the need to mark down what I was reading to remember it! In addition to the notes kept here I locally use [Notable](https://github.com/notable/notable) to take notes as it blends markdown and katex nicely. If I figure out how to render those files online I shall consider adding them.

**Ideal Structure**:
- Field # 1(i.e. Math/ECE/Music/MAE/etc.)
	- Category #1
		- Revelant Notes
	- ...
	- Category #M
		- Relevant Notes
- ...
- Field #N
	- Category #1
		- Relevant Notes
	- ...
	- Category #P
		- Relevant Notes
