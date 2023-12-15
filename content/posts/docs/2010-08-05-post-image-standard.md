---
categories:
- Post Formats
date: "2010-08-05T00:00:00Z"
tags:
- image
- Post Formats
title: 'Post: Image (Standard)'
---

The preferred way of using images is placing them in the `/assets/images/` directory and referencing them with an absolute path. Prepending the filename with `{{ site.url }}{{ site.baseurl }}/assets/images/` will make sure your images display properly in feeds and such.

Standard image with no width modifier classes applied.

**HTML:**

```html
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="">
```

**or Kramdown:**

```markdown
![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg)
```

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/unsplash-image-9.jpg)

Image that fills page content container by adding the `.full` class with:

**HTML:**

```html
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="" class="full">
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg)
{: .full}{% endraw %}
```

![Unsplash image 10]({{ site.url }}{{ site.baseurl }}/assets/images/unsplash-image-10.jpg)
{: .full}