---
title:  "The Adventures Begin"
mathjax: true
layout: post
categories: 
 -github
 -website
---


## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Pied Stilts](/assets/PiedStilts.jpg)

[Pied Stilts](https://photos.app.goo.gl/ai8YS5PCgENsw16HA) by MG

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
