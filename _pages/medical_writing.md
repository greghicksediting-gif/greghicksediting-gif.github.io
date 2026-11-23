---
layout: page
title: medical
description: this is what advanced image components could look like
tags: portfolio medical_writing
permalink: /medical_writing/
categories: portfolios
nav: true
nav_order: 3
images:
  slider: true
---

## Image Slider

This is a simple image slider. It uses the [Swiper](https://swiperjs.com/) library. Check the [examples page](https://swiperjs.com/demos) for more information of what you can achieve with it.

<swiper-container keyboard="true" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true">
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide1.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide2.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide3.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide4.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide5.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
  <swiper-slide>{% include figure.liquid loading="eager" path="assets/img/surmount/Surmount_Slide6.JPG" class="img-fluid rounded z-depth-1" %}</swiper-slide>
</swiper-container>
