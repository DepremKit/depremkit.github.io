---
title: Sonuçlar
nav:
  order: 3
---

# {% include icon.html icon="fa-solid fa-square-poll-vertical" %}Sonuçlar

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture col1 %}

{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}

{% endcapture %}

{% capture col2 %}

{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}

{% endcapture %}

{% capture col3 %}

{% include figure.html image="images/photo.jpg" caption="Lorem ipsum" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
