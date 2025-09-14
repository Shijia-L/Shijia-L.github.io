---
title: Go Back to Hometown👋
summary: Hi! Miss you so much!
date: 2022-10-02
authors:
  - admin
tags:
  - Travelling
  - Hometown
image:
  caption: 'photo in Shaoxing'
  
module:
  imports:
    - path: github.com/marcpabst/hugo-maps

params:
  hugo-maps:
    default:
        tileJSON: https://www.google.com/maps
    my_map:
        center: [0, 0]
        zoom: 2
---


"Bright is the Moon over My Home Village."

 {{< video src="2022.mp4" >}}

{{< map name="my_map" >}}