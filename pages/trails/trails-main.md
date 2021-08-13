---
title: Trails
layout: page
permalink: /trails/index.html
# Edit the markdown on in this file to describe your collection
---

## Trails 

<ul>
{% for trail in site.data.config-trails %}<li><a href="{{trail.url}}?id={{trail.objectid}}">{{trail.title}}</a> <br/>
{% include feature/gallery-trails.html filter="item.location contains 'all'" %}
<p>{{trail.desc}}
</p></li>{% endfor %}
</ul>