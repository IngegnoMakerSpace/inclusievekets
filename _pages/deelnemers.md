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
        <h1>Lesrooster September - November 2020</h1>
      </div>
    </div>
  </div>
</div>

<div class="container">
<div class="row">
<div class="col-12">
<p>Interesse in dit traject? Bekijk <a href="https://docs.google.com/document/d/1DucMCjWVHR8D1l0FuArCIeSvFnDv3c6iqvw0pisUhcM/edit?usp=sharing"> hier het lesrooster</a></p>
<p>FabZero is een intensief opleidingstraject over 3 maanden waarbij je meester wordt in de digitale productie technieken. Elke week overlopen we een nieuw onderwerp. Op het einde toon je de nieuw aangeleerde skills in een eindproject. Een ideale kennismaking met de makerswereld, alsook een ideale voorbereiding voor wie eventueel <a href="{{ site.baseurl}}/fabacademy">FabAcademy</a> wenst te volgen.</p>
         
</div>
</div>
</div>

<!-- link om in te schrijven -->
<div class="container pt-2">
<div class="call">
<div class="call-box-top">
<div class="call-phone"><strong>Interesse in het FabZero traject? </strong>  </div>  
</div>
<div class="call-box-bottom">
<a href="https://forms.gle/o5JxSYZLGWUzDiJZ8" class="button">Schrijf je hier in!</a>
</div>
</div>
</div>

<div class="container pt-3">
<div class="call">
<div class="call-box-top">
<div class="call-phone"><strong>Inschrijven voor losse FabZero modules? </strong>  </div>
</div>
<div class="call-box-bottom">
<a href="https://forms.gle/3Tgr9H4MXWxfjyFk9" class="button">Schrijf je hier in!</a>
</div>
</div>
</div>


<div class="container">
<div class="row">
<div class="col-12">
<p>Beschrijving van de verschillende modules vind je hieronder:</p>         
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



https://bit.ly/FabZero