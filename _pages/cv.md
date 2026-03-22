---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
<!--
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012
-->

* Institute of Software, Chinese Academy of Sciences, 2017
<br>
Ph.D. in Computer Application Technology 
<br>
**Adviser:** Zhenfeng Zhang

* University of Electronic Science and Technology of China, 2011
<br>
B.S. in Information and Computing Science

Work experience
======
<div class="cv-item">
  <div class="cv-row">
    <div class="cv-left">2025 - Now</div>
    <div class="cv-right">Professor</div>
  </div>
  <div class="cv-desc">State Key Laboratory of Cryptology, Beijing, China</div>
</div>

<div class="cv-item">
  <div class="cv-row">
    <div class="cv-left">2021 - 2025</div>
    <div class="cv-right">Associated Professor</div>
  </div>
  <div class="cv-desc">State Key Laboratory of Cryptology, Beijing, China</div>
</div>

<div class="cv-item">
  <div class="cv-row">
    <div class="cv-left">2017 - 2021</div>
    <div class="cv-right">Assistent Professor</div>
  </div>
  <div class="cv-desc">State Key Laboratory of Cryptology, Beijing, China</div>
</div>

<style>
.cv-item {
  margin-bottom: 18px;
}
.cv-row {
  display: flex;
  align-items: baseline;
  gap: 16px;
}
.cv-left {
  min-width: 180px;
  font-weight: 500;
  white-space: nowrap;
}
.cv-right {
  font-weight: 600;
}
.cv-desc {
  padding-left: 196px;
  line-height: 1.5;
}
</style>
  
Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<!--  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
