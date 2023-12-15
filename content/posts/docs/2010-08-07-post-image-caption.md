---
categories:
- Post Formats
date: "2010-08-07T00:00:00Z"
tags:
- image
- Post Formats
title: 'Post: Image (Caption)'
---

{% capture fig_img %}
![Foo]({{ "/assets/images/unsplash-gallery-image-3.jpg" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Photo from Unsplash.</figcaption>
</figure>