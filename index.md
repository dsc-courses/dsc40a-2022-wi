---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }} 🧠
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

**Disclaimer:** Until this disclaimer is removed, everything on this site is a work in progress and may be changed.

<!-- [Lecture Recordings](https://podcast.ucsd.edu/watch/fa21/dsc40a_a00){: .btn .btn-blue } [Assignment Solutions](https://campuswire.com/c/GF82D3B2E/feed/73){: .btn .btn-purple }-->

**Welcome!** Please start by reading this website, especially the [syllabus](../syllabus) and the schedule below. To join course meetings, group work sessions, and office hours, click the button below: 

[Join Zoom](https://ucsd.zoom.us/j/91995392966?pwd=M0RGN0t6U21qb0ZLNkMzRHF0QU55UT09){: .btn .btn-blue }

{% for module in site.modules %}
{{ module }}
{% endfor %}
