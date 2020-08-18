---
permalink: /precedents/
title: "Precedents"
classes: wide
sidebar:
  nav: "docs"

gallery:
  - url: /assets/images/test1.JPG
    image_path: /assets/images/test2.JPG
    alt: "placeholder image 2"
    title: "Image 2 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title caption"
  - url: /assets/images/test1.JPG
    image_path: /assets/images/test1.JPG
    alt: "placeholder image 1"
    title: "Image 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title captionImage 1 title caption"

---

<BR>
  


{% capture notice-1 %}
#### Good Precedents may be due to:

* good planning/foresight
* good implementation
* well maintained
* working as intended (or better)
* serendipity
* creating an attractive feature

{% endcapture %}

<div class="notice">
  {{ notice-1 | markdownify }}
</div>

{% capture notice-2 %}
#### Good Precedents may be due to:

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

