---
title: Trails
layout: page
permalink: /trails/index.html
# Edit the markdown on in this file to describe your collection
---

## Trails 


{% for t in site.data.config-trails %}
<div class="trail border-left border-dark pl-4 my-5"><a href="{{t.trailid}}.html?id={{t.objectid}}" class="h3 text-dark">{{t.trail}}</a> <br/>
<div class="row ml-4">
<div class="col-md-4">{% include feature/trails-gallery.html trail=t.trailid %}</div>
<div class="col-md-8"><p>{{t.desc}}</p></div>
<div class="col-12 my-4 d-none d-md-block">
{% include feature/trails-elevation.html trail=t.trailid %}
</div>
</div>
</div>
<hr class="my-5">{% endfor %}
