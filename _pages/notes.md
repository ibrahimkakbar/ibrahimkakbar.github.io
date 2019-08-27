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

This is where all my notes pertaining to any subject will be placed. This will include course material from slides/books/videos/supplements/etc. that I have re-written to suit my style of comprehension. I am currently in the process of rendering all my notes and will be adding them slowly.

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
