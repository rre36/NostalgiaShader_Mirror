---
layout: post
title: Nostalgia Shader Dev 0.3
comments: false
tags: [release, dev]
bigimg: 
  - "/img/dev0.3.0.jpg"
---

This is more of an intermediate update due to some upcoming rewrites of large parts of this shader, so there are some broken things to be expected.

<h2> New Features and Additions </h2>

* volumetric vanilla style clouds
* user-friendly names for some settings
* added selectable different auto exposure modes

<h2> Improvements and Fixes </h2>

* reduced sun path rotation
* improved fog issue at high sample counts
* changed fog behavior a bit

<h2> Known Issues </h2>

* translucency in hand is broken
* beacon beam is broken
* water can be lit in an unintended way at sunrise/sunset
* (cloud) lighting transition at sunrise/sunset can look strange
* translucent objects above clouds can cause blending issues

Download: [Nostalgia Dev 0.3](https://github.com/rre36/glsl_nostalgia/releases/download/v0.3/Nostalgia_dev0.3.zip)