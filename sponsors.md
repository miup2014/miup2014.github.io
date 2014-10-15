---
layout: page
title: Apoios
permalink: /sponsors/
---

### Sponsors

{% for sponsor in site.sponsors %}
  <!-- <div style="margin-top: 2em" /> -->
  ![Logo]({{ baseurl }}/{{ sponsor.logo_medium }})

  {{ sponsor.content }}
{% endfor %}

### Institutional Support

* ![FEUP Logo](/assets/feup_logo_small.png)
* ![DEI Logo](/assets/dei_logo.jpg)
* NuIEEE
