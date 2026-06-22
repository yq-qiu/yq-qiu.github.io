---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-page">
  <h1>Yuqing Qiu, Ph.D.</h1>
  <p class="cv-lede">Assistant Professor, Department of Physics, University of Tennessee, Knoxville</p>

  <h2>Appointments</h2>
  <ul class="cv-list">
    <li><span class="cv-date">Jan. 2025 -</span><span>Assistant Professor, Physics, University of Tennessee, Knoxville</span></li>
    <li><span class="cv-date">Aug. 2024 - Dec. 2024</span><span>Miller Postdoctoral Fellow, Physics, Johns Hopkins University</span></li>
    <li><span class="cv-date">Jan. 2019 - Jun. 2024</span><span>Yen Postdoctoral Fellow, Chemistry, University of Chicago</span></li>
  </ul>

  <h2>Education</h2>
  <ul class="cv-list">
    <li><span class="cv-date">2018</span><span>Ph.D. in Chemistry, University of Utah</span></li>
    <li><span class="cv-date">2012</span><span>B.S. in Chemistry, Zhejiang University</span></li>
  </ul>

  <h2>Awards and Fellowships</h2>
  <ul class="cv-list">
    <li><span class="cv-date">2024</span><span>Miller Postdoctoral Fellowship, Department of Physics, Johns Hopkins University</span></li>
    <li><span class="cv-date">2024</span><span>Contributed talk selected for the DBIO Early Career Prize Session, APS March Meeting</span></li>
    <li><span class="cv-date">2023</span><span>Postdoc and Senior Researcher Award, Department of Chemistry, University of Chicago</span></li>
    <li><span class="cv-date">2019</span><span>Yen Postdoctoral Fellowship, Institute for Biophysical Dynamics, University of Chicago</span></li>
    <li><span class="cv-date">2019</span><span>Cheves T. Walling Award for Ph.D. dissertation, Department of Chemistry, University of Utah</span></li>
    <li><span class="cv-date">2017</span><span>Chinese Government Award for Outstanding Self-Financed Student Abroad</span></li>
    <li><span class="cv-date">2017</span><span>Ronald and Eileen Ragsdale Curie Club Graduate Research Award, University of Utah</span></li>
    <li><span class="cv-date">2016</span><span>Best Poster Award, Water and Aqueous Solutions Gordon Research Conference</span></li>
  </ul>
</div>

<style>
  .cv-page h1 {
    margin-bottom: 0.2rem;
  }

  .cv-lede {
    margin-top: 0;
    color: #555;
    font-size: 1rem;
  }

  .cv-page h2 {
    margin-top: 2rem;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid #e5e5e5;
    font-size: 1.25rem;
  }

  .cv-list {
    list-style: none;
    padding-left: 0;
    margin-left: 0;
  }

  .cv-list li {
    display: grid;
    grid-template-columns: 9.5rem minmax(0, 1fr);
    gap: 1rem;
    margin: 0.75rem 0;
    line-height: 1.45;
  }

  .cv-date {
    color: #666;
    font-weight: 600;
  }

  @media (max-width: 600px) {
    .cv-list li {
      display: block;
    }

    .cv-date {
      display: block;
      margin-bottom: 0.15rem;
    }
  }
</style>

<!--  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
