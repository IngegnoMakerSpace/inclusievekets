---
title: Lesinhouden
layout: default
bodyClass: page-testimonials-list
permalink: /deelnemers
---

<div class="intro intro-med">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <h1>Lesinhouden</h1>
      </div>
    </div>
  </div>
</div>

 <div class="container">
    <div class="row">
      <div class="col-12">
        <p>Op 8 juli studeren de eerste studenten af van het FabZero trajct. Ben je benieuwd en wil je er ook bij zijn? Schrijf je in door te mailen naar amy@decreatievestem.be</p>
          <img src="{{site.baseurl}}/assets/images/fabzero1.jpg" alt="fabzero1" style="width:auto;height:600px;" text-align="center">
      </div>
    </div>
  </div>

 <div class="container">
    <div class="row">
      <div class="col-12">
          <p>Interesse in dit traject? Bekijk <a href="https://docs.google.com/document/d/1DucMCjWVHR8D1l0FuArCIeSvFnDv3c6iqvw0pisUhcM/edit?usp=sharing"> hier de lesinhouden</a></p>
         
      </div>
    </div>
  </div>


<div class="container pb-6">
  <div class="row">
    {% assign sorted_lessons = site.lesinhouden | sort: 'title' %}
    {% for les in sorted_lessons %}
    {% if les.show == nil or les.show %}
    <div class="col-12 col-md-6 mb-2 ">
      <div class="testimonials testimonials-summary">
        <div class="testimonials-meta">
          <h2 class="testimonials-title">{{ les.title }}</h2>
          <p class="testimonials-name">{{ les.name }}</p>
          <p class="testimonials-jobtitle">{{ les.jobtitle }}</p>
        </div>
        {% if les.only_excerpt == true %}
        <div class="testimonials-content">{{ les.excerpt }}</div>
        {% else %}
        <div class="testimonials-content">{{ les.content }}</div>
        {% endif %}
      </div>
    </div>
    {% endif %}
    {% endfor %}
  </div>
</div>
