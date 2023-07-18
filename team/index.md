---
title: Takım
nav:
  order: 5
---

# {% include icon.html icon="fa-solid fa-users" %}Takım

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: vb" %} {% include list.html data="members" component="portrait" filters="role: ^(?!vb$)" %}
