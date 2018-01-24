---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /images/gardenight.gif
  caption:
excerpt: 'Un blog colmo di recensioni e speculazioni caustiche riguardo Videogiochi, Serie TV, Fumetti e tutte quelle robe nerd'
---

{% for post in paginator.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}