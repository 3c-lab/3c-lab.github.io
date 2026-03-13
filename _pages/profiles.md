---
layout: profiles
permalink: /people/
title: people
description: members of the lab
nav: true
nav_order: 7
---

## Principal Investigator

{% include profiles.liquid profiles=page.profiles | where: "group", "pi" %}

## Postdoctoral Scholars

{% include profiles.liquid profiles=page.profiles | where: "group", "postdoc" %}

## Graduate Students

{% include profiles.liquid profiles=page.profiles | where: "group", "grad" %}

## Undergraduate Researchers

{% include profiles.liquid profiles=page.profiles | where: "undergrad" %}

## alumni

{% include profiles.liquid profiles=page.profiles | where: "alumni" %}

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - name: Lieselot Carrette
    group: pi
    align: right
    image: lieselot_portrait.jpg
    content: about_lieselot.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>Principal Investigator</p>
      <p>Department of Psychiatry</p>
      <p>UC San Diego</p>
      <p><a href="mailto:lcarrette@ucsd.edu">lcarrette@ucsd.edu</a></p>

  - name: Lieselot Carrette
    group: pi
    align: right
    image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>

---
