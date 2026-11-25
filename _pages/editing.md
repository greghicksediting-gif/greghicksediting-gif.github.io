---
layout: page
title: Editing
description: 
tags: portfolio editing
nav: true
nav_order: 4
permalink: /editing/
images:
  slider: true
toc:
  sidebar: left
scholar:
  bibliography_template
---
<style>
.testimonial_name {
  font-size: 12pt;
  font-weight: bold;
  font-family: Arial, Helvetica, sans-serif;
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 0:}

/*.testimonial_title {
  font-size: 8pt;
  font-style: italic;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  margin-top: 0;}*/

.testimonial_body {
  font-size: 10pt;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif; }

.swiper-slide {
  display: flex;
  flex-direction: column;
  justify-content: center; /* Centers vertically */
  align-items: center;     /* Centers horizontally */
  text-align: center;      /* Centers multi-line text */
}

.slider-wrapper {
margin-left: auto;
      margin-right: auto;
      width: 92%;
      /* make room for arrows */
      padding-left: 2em;
      padding-right: 2em;
   }

.custom-prev {
  left: 0;
}

.custom-next {
  right: 0;
}
</style>


<h2>About me</h2>
I'm an academic and technical editor that can offer fast turnaround with in-depth feedback. I specialize in education, biomedical sciences, and clinical studies, but I have edited successful publications across an eclectic range of topics: from Assyriology to computational mathematics, with several places in-between!

I specialize in academic and nonfiction writing, but am available for fiction and memoir projects if requested.

<h3>Guaranteed human</h3> 
I will never use AI to review your work or draft my feedback. I believe writing to be a fundamentally human act, and my approach to editing should respect that in turn. 

<h2>Services</h2>
<ul>
<li>Proofreading for APA, AMA, CMOS, and JAMA, as well as other styles on request</li>
<li>Developmental, style, and copy editing for any topic</li>
<li>Flexible hourly or fix-rate pricing based on needs</li>
</ul>

<h2>Testimonials</h2>
<div class="slider-wrapper">
<swiper-container slides-per-view="2.2" centeredSlides="true" keyboard="true" space-between="10" navigation="true" pagination="true" pagination-clickable="true" pagination-dynamic-bullets="true" rewind="true" loop="true" spaceBetween="20">
<swiper-slide>
<p class="testimonial_name">Dr. Stephanie Maier</p>
<p text-align="center">Executive Director, Cell Transplant Therapy Canada</p>
<p class="testimonial_body">I work for a medical professional association and we publish the abstracts from our scientific conference each year. For the past two years, we've been fortunate to work with Greg Hicks, who has edited the abstracts for grammar, readability, formatting, and standardization, and we could not be happier with the results! Greg has a keen attention to detail and would be an asset to anyone looking to polish their scientific writing prior to submission for publication. Thanks Greg!</p>
</swiper-slide>
<swiper-slide>
<p class="testimonial_name">Dr. Sam Gene</p>
<p text-align="center">Biology</p>
<p class="testimonial_body">Greg’s assistance has been fantastic. He gives thorough and constructive edits that have helped improve my manuscripts. I love that he has a background in science and approaches the work with care. His feedback really helps build confidence in your writing.</p>
</swiper-slide>
<swiper-slide>
<p class="testimonial_name">Dr. E.P.P.</p>
<p text-align="center">Classics</p>
<p class="testimonial_body">Greg produces excellent edition work with a very swift turnaround. His edits are always on point, and his comments are insightful without ever being overwhelming. He consistently improves the clarity of the text while also upgrading it with impeccable grammar and idiomatic language. Greg understands the typical issues that arise in English texts written by French native speakers particularly well. I would not hesitate to work with him again, as I fully trust him based on our previous.</p>
</swiper-slide>
<swiper-slide>
<p class="testimonial_name">Dr. B.L.</p>
<p text-align="center">Social Sciences</p>
<p class="testimonial_body">Greg provided the expertise I was looking for despite the highly technical nature of the paper, and the quality of his work exceeded expectations. He not only corrected all the errors common to non-native English speakers like me but, more importantly, my paper is now clearer and more streamlined thanks to him.</p>
</swiper-slide>
</swiper-container>
  <div class="swiper-button-prev custom-prev"></div>
  <div class="swiper-button-next custom-next"></div>
</div>

<h2>Recent Projects</h2>
{% raw %}{% bibliography --file edited %}{% endraw %}
