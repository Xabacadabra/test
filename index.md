---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /images/gardenight.gif
  caption:
excerpt: 'Recensioni e speculazioni caustiche riguardo Videogiochi, Serie TV, Fumetti e tante altre malevoli faccende.<br /><i>On Air Since 2013</i>'
---

{% for post in paginator.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

{% include paginator.html %}