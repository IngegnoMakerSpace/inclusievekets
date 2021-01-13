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
        <h1>FABZERO 2021</h1>
      </div>
    </div>
  </div>
</div>

<div class="container">
<div class="row">
<div class="col-12">
<p> A journey at the intersection between digital fabrication, electronics, textiles and prototyping.
<!--Bekijk <a href="https://docs.google.com/document/d/1j6l5XAXaJyxChYeGSWn2q6vYan0AWbrq2lXoJ-7O8h4/edit?usp=sharing"> hier het lesrooster</a> -->
</p>
  &nbsp;
<p>FabZero is een intensief multidisciplinair opleidingstraject waarbij je meester wordt in de digitale technieken die eigen zijn aan de expert maker. Het is gebaseerd op het basisprincipe: <b> leren + maken + delen.</b> </p>
<p> Het programma is gestructureerd in twee fasen: </p>
  <ul>
 <p> &#8226; 4 maanden <b> intensief leren </b>: 12 modules over 16 weken met wekelijkse online lessen (live streaming) door experts en wekelijkse openlabs  om de opdrachten te maken begeleid door de lokale instructeurs en makers gemeenschap.</p>
 <p> &#8226; 3 maanden <b> projectontwikkeling </b>: ruime tijd om op eigen tempo je eigen geïntegreerd eindproject (GIP) te maken, geadviseerd door de expert lesgevers en de lokale instructeurs.</p>
   </ul>
<p> We sluiten af met een <b>Expo</b> van de afstudeerprojecten en <b> diploma uitreiking </b>. </p>
  &nbsp;
 <p> FabZero ontvouwt zich <b> modulair </b> over <b> 4 specialisaties </b> en niveaus. De modules kunnen gecombineerd worden tot een gepersonaliseerd traject. </p>
  &nbsp;
<p> We bieden <b> 3 trajecten </b> aan: <b>FabZero makers, FabZero IT, FabZero mix & match </b>. Elk traject bestaat uit minstens <b>45 contacturen</b> plus <b>40 uur zelfstandig werk </b>. </p>
 <p> Het <b>GIP </b> voorziet minstens <b>6 contacturen</b> plus minstens <b>18 uur zelfstandig werk</b>. </p>
&nbsp;
 <p> De trajecten zijn opgebouwd rond deze 4 lijnen: </p>
  <ul>
 <p> &#8226; Digitaal Maken voor makers: 2d en 3d digitaal ontwerpen, lasersnijden, 3d printen, snijplotten, cnc frezen, digitaal borduren, digitale kledij ontwerp. </p>
  <p> &#8226; Materialen & prototyping voor makers: materialen en eigenschappen, smart materials, prototyping principes, prototyping technieken, productpresentatie voor makers. </p>
  <p> &#8226; Elektronica voor makers: basis elektronica, micro-elektronica via Arduino, programmeren van Arduino met sensoren en actuatoren, smart textiles, PCB’s maken. </p>
 <p> &#8226; IT voor makers: Git en GitHub/GitLab, Python, IOT, gevorderde Arduino, Raspberry Pi, AI en Machine Learning. </p>
 </ul>
 &nbsp;
<p> In het traject FabZero makers maak je dan ook een keuze tussen drie specialisaties afhankelijk van je interesse en niveau. </p>
  &nbsp;
<p> De wekelijkse les (contacturen) wordt gecombineerd met 1 dag open lab om de taken uit te voeren en de machines te leren gebruiken. 
Elke module bestaat uit één of meerdere sessies. Alle sessies zijn georganiseerd in slots van 3 uur. Het doel is een gedegen digitale opleiding die zal leiden tot permanente kennisverankering. </p>
 &nbsp;
<p>De lesmomenten zijn online te volgen via Zoom, daarnaast kan je wekelijks terecht in de open labs in één van de participerende makerspace. Kan je niet naar de Ingegno MakerSpace te Drongen? Kies dan een FabLab/MakerSpace in je buurt, of een van de aangesloten labs: </p>
<ul>
<li><strong>Ingegno Maker Space</strong>, Antoon Catriestraat, 6 Drongen; </li>
<li><strong>Masala</strong>, Meibloemstraat 18, Gent; </li>
<li><strong>MaM</strong>, Rijselstraat 1, 8200 Brugge; </li>
<li><strong>Buda::Lab</strong>, Dam 2, 8500 Kortrijk; </li>
<li><strong>ULB</strong> Fritz Toussaintstraat 8, 1050 Elsene.</li>
</ul>
</div>
</div>
</div>

<!-- link om in te schrijven -->
<!--div class="container pt-2">
<div class="call">
<div class="call-box-top">
<div class="call-phone"><strong>Interesse in het FabZero traject? </strong>  </div>  
</div>
<div class="call-box-bottom">
<a href="https://forms.gle/o5JxSYZLGWUzDiJZ8" class="button">Schrijf je hier in!</a>
</div>
</div>
</div-->

<!--div class="container pt-3">
<div class="call">
<div class="call-box-top">
<div class="call-phone"><strong>Inschrijven voor losse FabZero modules? </strong>  </div>
</div>
<div class="call-box-bottom">
<a href="https://forms.gle/3Tgr9H4MXWxfjyFk9" class="button">Schrijf je hier in!</a>
</div>
</div>
</div-->


<div class="container">
<div class="row">
<div class="col-12">
<p><br>
Deelname is <strong>gratis</strong>, maar we vragen wel een serieus engagement van de deelnemers.</p>
<p>Meer informatie nodig? Neem contact op met de lokale verantwoordelijke, of het team van De Creatieve STEM (<a href="mailto:jill@decreatievestem.be;jill@decreatievestem.be"> jill@decreatievestem.be en cristina@decreatievestem.be</a>) </p>
<p>Beschrijving van de verschillende modules komt binnenkort.</p>         
</div>
</div>
</div>


<div class="container pb-6">
<div class="row">
{% assign sorted_lessons = site.lesinhouden | sort: 'title' %}

{% assign sorted_lessons = nil %}

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

