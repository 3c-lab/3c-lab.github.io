---
layout: profiles
permalink: /people/
title: people
description: members of the lab
nav: true
nav_order: 7


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
        <p><a href="mailto:lcarrette@health.ucsd.edu">lcarrette@health.ucsd.edu</a></p>

    - name: Daria Kouzminova 
      group: undergrad
      align: right
      image: Daria_portrait.jpg
      content: 
      image_circular: false # crops the image to make it circular
      more_info: >
        <p><a href="mailto:dkouzminova@ucsd.edu">dkouzminova@ucsd.edu</a></p>

    - name: Selin Boyaci 
      group: undergrad
      align: right
      image: Selin_portrait.jpg
      content: 
      image_circular: false # crops the image to make it circular
      more_info: >
        <p><a href="mailto:sboyaci@ucsd.edu">sboyaci@ucsd.edu</a></p>

    - name: Simone Werner
      group: visit
      align: right
      image: Simone_portrait.jpg
      content: 
      image_circular: false # crops the image to make it circular
      more_info: >
        <p><a href="mailto:24IMC11220@imc.ac.at">24IMC11220@imc.ac.a</a></p>

    - name: Selene Bonnet 
      group: visit
      align: right
      image: Selene_portrait.jpg
      content: 
      image_circular: false # crops the image to make it circular
      more_info: >
        <p><a href="mailto:sbonnetzahedi@health.ucsd.edu">sbonnetzahedi@health.ucsd.edu</a></p>

    - name: Joseph Mosquera 
      group: alumni
      align: right
      image: Joseph_portrait.jpg
      content: 
      image_circular: false # crops the image to make it circular
    
      

---

## Principal Investigator

{% include profiles.liquid profiles=page.profiles | where: "group", "pi" %}

## Postdoctoral Scholars

{% include profiles.liquid profiles=page.profiles | where: "group", "postdoc" %}

## Graduate Students

{% include profiles.liquid profiles=page.profiles | where: "group", "grad" %}

## Visiting Student

{% include profiles.liquid profiles=page.profiles | where: "group", "visit" %}

## Undergraduate Researchers

{% include profiles.liquid profiles=page.profiles | where: "group", "undergrad" %}

## alumni

{% include profiles.liquid profiles=page.profiles | where: "group", "alumni" %}


