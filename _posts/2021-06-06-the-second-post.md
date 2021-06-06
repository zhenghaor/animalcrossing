---
title: "Post: Gallery"
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

These are gallery tests for image wrapped in `<figure>` elements.

To place a gallery add the necessary YAML Front Matter:


And then drop-in the gallery include --- gallery `caption` is optional.

```liquid
{% raw %}{% include gallery id="gallery" caption="This is a sample gallery with **Markdown support**." %}{% endraw %}
```

{% include gallery caption="This is a sample gallery with **Markdown support**." %}


[![image1](https://animalcrossing.design/assets/images/image1.jpg)](https://www.bilibili.com)

