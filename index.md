---
title: "TRiLOGy"
layout: splash
permalink: /
author_profile: true
author: breno
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/back-ams.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
excerpt: "Sustainable Transportation and Logistics Over Water: <br/>Electrification, Automation, and Optimization"
intro: 
  - excerpt: 'TRiLOGy will unlock the potential of transportation and logistics in urban waterways with electric and autonomous vessels by enabling safer, more sustainable and efficient operations.'
feature_row:
  - image_path: /assets/images/fleet_management.png
    alt: "placeholder image 1"
    title: "Fleet management"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/automation.jpeg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Automation"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/automation.jpeg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/automation.jpeg
    alt: "placeholder image 2"
    title: "Automation"
    excerpt: 'This module aims to develop autonomy tools for navigation in inland waterways, among other manned and unmanned vessels. The main challenges to ensure safe and efficient navigation of autonomous vessels in urban waters is that of generating safe trajectories that (i) take into account the goals expressed by the high-level integrated strategy, (ii) take into account the complex dynamics of the vessel and (iii) coordinate with other traffic participants.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/fleet_management.png
    alt: "Fleet management module"
    title: "Fleet management"
    excerpt: 'This module aims for strategic and operational level fleet management methodologies. These two levels need to interact: operational level needs to use the long-term decisions from the strategic level as an input and strategic level needs time and cost estimations from the operational level to represent the share of water transportation among other modes.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

# Partners

<div class="grid__wrapper" itemscope itemtype="http://schema.org/Organization">
    {% for partner_hash in site.data.partners %}
    {% assign partner = partner_hash[1] %}
    <div class="grid__item">
        <a style="padding:10px; margin:5px; justify-content: center; align-items: center; display: flex; vertical-align: middle; width:300px; height: 300px;" itemprop="url" href="{{ partner.url }}">   
            <img style="" itemprop="logo" src="{{ partner.logo }}" alt="{{ partner.name }}">
        </a>
    </div>
    {% endfor %}
</div>