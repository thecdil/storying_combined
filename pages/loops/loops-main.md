---
title: Loops
layout: para
permalink: /loops/index.html
# Edit the markdown on in this file to describe your collection
---

## Loops 

<ul>
{% for trail in site.data.config-trails %}<li><a href="{{trail.url}}?id={{trail.objectid}}">{{trail.trail}}</a></li>{% endfor %}
</ul>