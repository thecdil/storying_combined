---
title: About Mountain Caribou
layout: para
permalink: /about/caribou.html
# Edit the markdown in this file to describe your collection
---
<style>table tr td:first-child{width:400px}</style>

# About Mountain Caribou

{% include feature/jumbotron.html objectid="two-mouth-meadow-imag214" position="top" %}

A subspecies of the woodland caribou (*rangifer tarandus caribou*), the mountain caribou is an ecotype primarily inhabiting inland regions of British Columbia and Western Alberta. Until recently, mountain caribou could be found in the high peaks and temperate rainforests of northeastern Washington, northern Idaho, and northwestern Montana.  By 2016, however, the inland mountain caribou had become one of the most endangered species in the lower 48, earning the name “gray ghosts” for their elusive, almost spectral presence in the jagged peaks and remote old-growth forests of Idaho’s South Selkirk Mountains on the Canadian border. 

{% include feature/image.html objectid="ballcreek-smallclearing-blackbeargaze" %}

At that time, it was estimated that the population had been winnowed down to a mere dozen; predation, climate change, and habitat destruction from logging, mining, and other forms of resource extraction exerted extreme pressures on Idaho’s dwindling caribou herd. Serious conservation efforts were made to combat these threats, including several augmentation programs, the listing of caribou as a threatened species under the endangered species act, the designation of critical caribou habitat in 2016, and even periodic wolf culls by helicopter.  However, conservation efforts were ended in January 2019, when the three remaining Idaho caribou were captured in a net and airlifted by helicopter into southern British Columbia. This event marked the official extinction of caribou in the lower 48, a species which once roamed throughout the northern US and lived as far south as the Salmon River, according to biologists.  

{% include feature/marginnote-image.html image="two-mouth-lakes-encounter" %}


Unlike the barren ground caribou of Alaska that migrate long distances and in large herds, mountain caribou evolved to migrate vertically, not to colder latitudes, but to the arctic conditions of high elevation old-growth forests of the South Selkirks. According to biologists, the seasonal migration pattern of mountain caribou initiates in the old growth cedar-hemlock bottoms at around 4,500 feet in early winter, where they’d feed on remaining summer forbs and lichen-heavy deadfall until the snow piled high and dense enough for them to migrate vertically to the elevated snowpack on mountain ridgelines. At that point, and for the duration of winter, they would feed exclusively on *bryoria fremontii* and *alectoria sarmentosa* –lichens formed on old growth englemann spruce and sub-alpine fir trees. They would remain mostly stationary until the spring warm-up triggered a downward migration that would follow the green-up back to the mountain summits for summer. Calving cow caribou would make an additional migration back to the ridgelines in early summer to give birth. The migration patterns of mountain caribou were largely a predator avoidance strategy. Their ability to live at high elevations and in deep snowpack (thanks to their snowshoe-like hooves) ensured an important spatial barrier between them and any potential predators. And the breeching and fragmentation of this barrier is essentially the reason for their absence. 

---




{% assign events = site.data.cariboutimeline %}
{% for event in events %}
<div class="row">
<div class="col-4 text-center align-self-center my-5">
<p class="h2">{{ event.date }}</p>
</div>
<div class="col-8 border-left my-5" style="border-width: 3px;">
<p class="h3 col-12 col-md-6">{{ event.text }}</p>
</div>
</div>
{% endfor %}

