---
categories:
- Layout
- Uncategorized
date: "2010-08-05T00:00:00Z"
header:
  actions:
  - label: Learn more
    url: https://unsplash.com
  caption: 'Photo credit: [**Unsplash**](https://unsplash.com)'
  og_image: /assets/images/page-header-og-image.png
  overlay_image: /assets/images/unsplash-image-1.jpg
last_modified_at: "2017-10-26T15:12:19-04:00"
tags:
- edge case
- image
- layout
title: 'Post: Overlay Image with OpenGraph Override'
---

This post has a header image with an OpenGraph override.

```yaml
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  og_image: /assets/images/page-header-og-image.png
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  actions:
    - label: "Learn more"
      url: "https://unsplash.com"
```