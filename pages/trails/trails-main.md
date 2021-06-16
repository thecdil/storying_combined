---
title: Trails
layout: para
permalink: /trails/index.html
# Edit the markdown on in this file to describe your collection
---

## Trails 

<ul>
{% for trail in site.data.config-trails %}<li><a href="{{trail.url}}?id={{trail.objectid}}">{{trail.trail}}</a></li>{% endfor %}
</ul>