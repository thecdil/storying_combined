---
title: Trails
layout: page
permalink: /trails/index.html
# Edit the markdown on in this file to describe your collection
---

## Trails 

<ul>
{% for t in site.data.config-trails %}<li><a href="{{t.trailid}}.html?id={{t.objectid}}" class="h2 text-dark">{{t.trail}}</a> <br/>
{% include feature/gallery-trails.html trail=t.trailid %}
<p>{{t.desc}}
</p></li>{% endfor %}
</ul>