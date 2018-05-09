---
layout: front
permalink: /
title: home
image:
    banner: images/banner-large.jpg
---

**Los monstruos del Caribe expuestos al análisis académico**

<div class="tiles">

{% for post in site.posts %}
{% include post-grid.html %}
{% endfor %}

</div>

Intro text

<hr/>
