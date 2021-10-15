---
title: About Caribou
layout: para
permalink: /about/caribou.html
# Edit the markdown in this file to describe your collection
---
<style>table tr td:first-child{width:400px}</style>

# About Caribou


{:.w-75 .my-4}
**caribou, n.** A reindeer belonging to any of several subspecies found in North America; esp. the migratory Rangifer tarandus groenlandicus.
etymology: <French caribou (1609) < Micmac *qaripu*, earlier form of qalipu (pronounced /xalibu/, cognate with Maliseet-Passamaquoddy mokalip caribou: see maccarib n.), reflecting an agent noun of an Algonquian verb with the sense ‘to shovel snow, to clear away snow’ (compare Ojibwa mangaanibii he shovels snow), so called on account of the animal's habit of scraping away snow to feed on the vegetation underneath. "Caribou." *Oxford English Dictionary*

<div class="row">
{% assign events = site.data.cariboutimeline %}
{% for event in events %}
<div class="col-4 text-center align-self-center my-5">
<p class="h2">{{ event.date }}</p>
</div>
<div class="col-8 border-left my-5" style="border-width: 3px;">
<p class="h3 w-50">{{ event.text }}</p>
</div>
{% endfor %}
</div>
