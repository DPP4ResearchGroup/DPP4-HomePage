---
title: "DPP4 Research Lab"
excerpt: "We are a group of enthusiastic scientists and our researches focus on better understanding DPP4."
layout: splash-1
permalink: /authors-list/
date: 2022-01-09T11:48:41+09:30
last_modified_at: 2022-01-10T09:40:41+09:30
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/avatar/avatar-DPP4.png
  actions:
    - label: "Terms and Conditions"
      url: "/terms/"
  caption: "Photo credit: [**R.QIAO**](https://dpp4research.page.link/home)"
intro: 
  - excerpt: 'We are a group of enthusiastic scientists and our researches focus on better understanding DPP4, here are some of us.'
authors_current:
  - robqiao
authors_past:
  - robqiao
---


{% include feature_row id="intro" type="center" %}

{{ page.title | liquify }}
{{ site.author.bio}}

{% for author in page.authors_current %}
     -- {{ site.data.authors[author].name }}
{% endfor %}

{% include author-profile.html type="right" %}

{% include authors_row id="authors_current" type="left" %}

{% include authors_row id="authors_past" %}
