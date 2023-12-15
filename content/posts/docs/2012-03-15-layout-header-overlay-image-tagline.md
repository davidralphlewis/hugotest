---
categories:
- Layout
- Uncategorized
date: "2012-03-15T00:00:00Z"
header:
  caption: 'Photo credit: [**Unsplash**](https://unsplash.com)'
  overlay_image: /assets/images/unsplash-image-1.jpg
last_modified_at: "2020-01-07T13:05:25-05:00"
tagline: This is a custom tagline content which overrides the *default* page excerpt.
tags:
- edge case
- image
- layout
title: 'Layout: Header Image Overlay with Custom Tagline'
---

This post should display a **header with an overlay image** and **custom tagline**, if the theme supports it.

Non-square images can provide some unique styling issues.

This post tests overlay header images with custom `page.tagline`.

```yaml
tagline: "This is a custom tagline content which overrides the default page excerpt."
header:
  overlay_image: /assets/images/unsplash-image-1.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
```