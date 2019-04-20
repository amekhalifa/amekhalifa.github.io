---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Thesis

> **M.Sc.**: *Novel Quadrotor Manipulation System* [[PDF]](https://arxiv.org/abs/1904.05090){:target="_blank"}

> **Ph.D.**: *Controller Design and Implementation of a New Quadrotor Manipulation System* [[PDF]](https://arxiv.org/pdf/1904.08498){:target="_blank"}

{% include base_path %}

## Preprint

{% for post in site.preprint reversed %}
  {% include archive-single.html %}
{% endfor %} 

## Journal

{% for post in site.journal reversed %}
  {% include archive-single.html %}
{% endfor %}

## Conference

{% for post in site.conference reversed %}
  {% include archive-single.html %}
{% endfor %}

