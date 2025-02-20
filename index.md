---
layout: splash
header:
  overlay_filter: linear-gradient(rgba(0, 146, 202, 0.1), rgba(0, 146, 202, 0.5))
  overlay_filter: "0.2"
  overlay_image: /assets/images/0.png
  actions:
  - label: "Learn More"
    url: "/about/"
intro: 
  - excerpt: 'Agile Minds Leading Revolution'
feature_row:
  - image_path: assets/images/1.jpg
    alt: "Figure failed to load"
    title: "About"
    excerpt: "**about us**"
    url: "/about/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/2.jpg
    alt: "Figure failed to load"
    title: "Projects"
    excerpt: "**our projects**"
    url: "/Projects/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/3.jpg
    alt: "Figure failed to load"
    title: "Publications"
    excerpt: "**our publications**"
    url: "/categories/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}