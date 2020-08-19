---
permalink: /precedent gallery/
title: "Precedent Gallery"
classes: wide
sidebar:
  nav: "docs"

gallery:
  - url: /assets/images/test2.JPG
    image_path: /assets/images/test2.JPG
    alt: "placeholder image 2"
    title: "Good Precedent: This tree has clearly been regularly maintained to control its size and is a good example of how regular maintenance and species selection has allowed for healthy tree growth (and no visual hard landscape damage) despite the confined dimensions of the planter, and proximity to buildings. <br>"
  - url: /assets/images/test1.JPG
    image_path: /assets/images/test1.JPG
    alt: "placeholder image 1"
    title: "Bad Precedent: Whilst the tree in question is forming a sizable green structural element within the street landscape, it is clear there is not enough space for the roots. When considering existing trees within newly designed landscapes, make sure to consider their proximity to hard surfaces and structures. By giving trees (proposed and existing) the space they need and not restricting them to confined spaces damage to hard landscape elements is less likely. <br>"


---

<BR>
  
Check out the [Precedent Info][precedent-info] for more info on ...

[precedent-info]: /precedent gallery info/


{% capture notice-1 %}
#### Good Precedents may be due to:

* good planning/foresight
* good implementation
* well maintained
* working as intended (or better)
* high quality specification
* serendipity
* creating an attractive feature

{% endcapture %}

<div class="notice">
  {{ notice-1 | markdownify }}
</div>

{% capture notice-2 %}
#### Bad Precedents may be due to:

- poor planning/foresight
- unforeseen problems
- poor implementation
- lack of maintenance or neglect
- low quality specification
- not working as intended
- forming an unattractive feature


{% endcapture %}

<div class="notice">
  {{ notice-2 | markdownify }}
</div>




August 2020 - Trees in Raised Planters

{% include gallery id="gallery" layout="half" caption="This is a half gallery layout example." %}

