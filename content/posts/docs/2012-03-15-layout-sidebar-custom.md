---
author_profile: false
date: "2012-03-15T00:00:00Z"
excerpt: A post with custom sidebar content.
last_modified_at: "2021-06-23T07:53:04-04:00"
sidebar:
- image: /assets/images/350x250.png
  image_alt: image
  text: Some text here.
  title: Title
- nav: sidebar-sample
  text: More text here.
  title: Another Title
title: 'Layout: Sidebar Custom'
---

This post has a custom sidebar set in the post's YAML Front Matter.

An example of how that YAML could look is:

```yaml
sidebar:
  - title: "Title"
    image: "/assets/images/your-image.jpg"
    image_alt: "image"
    text: "Some text here."
  - title: "Another Title"
    text: "More text here."
    nav: sidebar-sample
```