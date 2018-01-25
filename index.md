---
layout: splash
permalink: /
header:
  overlay_color: "#5e616c"
  overlay_image: /images/gardenight.gif
  caption:
excerpt: 'Recensioni e speculazioni caustiche riguardo Videogiochi, Musica, Animazione, Serie Tv e tante altre malevoli faccende.<br /><br /><i>On Air Since 2013</i>'
---

<div class="grid__wrapper">
{% for post in site.posts limit:8 %}
  {% include archive-single.html type="grid" %}
 {% endfor %}
</div>