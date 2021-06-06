---
title: "Post: Gallery"
date: 2021-06-06T17:00:00-08:00
toc: true
toc_label: "Unique Title"
toc_icon: "heart"  # corresponding Font Awesome icon name (without fa prefix)
toc_sticky: true
categories:
  - blog
tags:
  - gallery
gallery:
  - url: /assets/images/image1.jpg
    image_path: /assets/images/image1.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
---

### Chapter 1

### Chapter 2

These are gallery tests for image wrapped in `<figure>` elements.

To place a gallery add the necessary YAML Front Matter:


And then drop-in the gallery include --- gallery `caption` is optional.

```liquid
{% raw %}{% include gallery id="gallery" caption="This is a sample gallery with **Markdown support**." %}{% endraw %}
```

{% include gallery caption="This is a sample gallery with **Markdown support**." %}


### Chapter 3

[![image1](https://animalcrossing.design/assets/images/image1.jpg)](https://www.bilibili.com)

