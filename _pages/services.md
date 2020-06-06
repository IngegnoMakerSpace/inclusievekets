---
title: Voor partners
layout: default
bodyClass: page-services-list
permalink: /services
---


{::options parse_block_html="true" /}

<!-- Wat betekenen voor jullie werking?-->
<div class="intro">
<div class="container">
<div class="row">
<div class="col-12">

# Wat kunnen wij betekenen voor jou werking?

Dit project draagt zich natuurlijk niet alleen, en daarom hebben wij jou nodig! Ben je een middenvelds organisatie? Kom je in contact met jongvolwassenen tussen de 16 en de 35 die tot een kansengroep behoren? Heb je jongeren in de werking die geschikt zouden kunnen zijn voor deze opleiding? Stuur ze dan zeker door! 
</div>
</div>
</div>
</div>

<div class="intro-med">
<div class="container pb-6">
<div class="row">
{% for service in site.services %}
<div class="col-12 col-md-4 mb-1">
<div class="service service-summary">
<div class="service-content">
<h2 class="service-title">
<a href="{{site.baseurl}}{{ service.url }}">{{ service.title }}</a>
</h2>
{{ service.content | markdownify | strip_html | truncate: 100 }}
</div>
</div>
</div>
{% endfor %}
</div>
</div>
</div>

<!-- Wie zoeken we?-->
<div class="intro intro-med">
<div class="container pt-6 pt-md-1">
<div class="row">
<div class="col-12 col-md-10">
# Wie is onze doelgroep?
</div>
</div>
</div>
</div>

<div class="container pt-3 pt-md-3">
<div class="row">
<div class="col-12 col-md-10">

### Smaakmakers
De smaakmaker workshops zijn open voor **iedereen** en zijn bedoeld om nieuwe technologieën zoals 3D printen en (basis) elektronica naar een brede basis van geïnteresseerden te brengen.  
Zoek je een activiteit voor jouw organisatie, een teambuilding of heb je gewoon interesse in een van onze workshops, contacteer ons dan zeker.  
Onder <a href="https://ingegnomakerspace.github.io/inclusievekets/services/smaakmakers/">smaakmakers</a> vind je de volledige lijst van mogelijke workshops terug.

          
### Open Lab's

We helpen partner organisaties bij de opstart van hun eigen Open FabLab. Heb je een vraag, zit je vast, zoek je voor 1 week een machine die wij hebben? Wil je een workshop geven maar weet je niet goed hoe? Dan kunnen we jullie uit de nood helpen.   
We komen enkele keren helpen tijdens de het project om jullie open lab te begeleiden. Of we geven opleiding op een van de typische fablab machines: lasnijder, 3D printer, CNC frees, vinylsnijder of basis elektronica.
          
De Open Lab momenten zijn momenten waarbij de machines vrij toegankelijk zijn voor iedereen die weet hoe hij of zij ermee moet werken. Deelnemers van het FabZero traject (zie hieronder) worden aangemoedigd om hun aangeleerde kennis te delen met de rest van de community. 
          
### FabZero

De FabZero, het voortgezet traject uit de smaakmakers, zoekt deelnemers met het volgende profiel:

* De deelnemer behoort tot een kansengroep. 
* De deelnemer is tussen de 16 en 35 jaar 
* De deelnemer kan zich op **woensdagavon** en **een deel van de zaterdag** vrij maken om lessen te volgen of een kleine opdracht te maken. Met andere woorden: je kan je minstens op woensdag en zaterdag vrijmaken om les te volgen of aan projecten te werken.
* De deelnemer heeft kennis van computers. Je kan een browser opstarten, weet hoe je met een muis werkt, hoe je een mapje aanmaakt en bestanden versleept. 
* Je spreekt en verstaat voldoende **Nederlands**.Daarnaast heb je een basis van het Engels. Veel documentatie is in het Engels online te vinden.
* De deelnemer is **gemotiveerd**
* De deelnemer heeft affiniteit met technologie, computers en dingen bedenken
* De deelnemer kan **zelfstandig werken**

Ken je mensen die naar jou organisatie komen en die misschien interesse hebben in het traject? Download dan <a href="../assets/images/flyers/FabZero2.pdf">hier</a> de flyer!

### FabZero Bootcamp

Vanuit verschillende partners kwam de vraag of er ook een mogelijkheid is om een bootcamp te organiseren. Tijdens zo'n bootcamp gaan we in op slechts enkele onderwerpen van het FabZero traject.         

In deze bootcamps ga je aan de slag met een select deel van de lessen uit het FabZero pakket. Om zo dicht mogelijk bij de noden te komen van de partnerorganisatie kunnen jullie zelf kiezen welke topics aan bod komen.

Daarnaast kun je ook zelf over de duurtijd van het bootcamp beslissen. Soms gaan deze enkel in de voormiddag door, soms over een volle week met extra werkmomenten in de weken nadien. Of soms gewoon 2 weken “vollenbak” maken, uitvinden en prototypen.
Ken je mensen die naar jou organisatie komen en die misschien interesse hebben in het traject? Download dan alle flyers.

* <a href="../assets/images/flyers/begeleiders.pdf">Bootcamp voor begeleiders</a>
* <a href="../assets/images/flyers/Brussel.pdf">Bootcamp in Brussel</a>
* <a href="../assets/images/flyers/Herfstbootcamp.pdf">Bootcamp in de herfstvakantie</a>

</div>
</div>
</div>

<!-- Interesse, contacteer ons-->
<div class="intro-med">
<div class="container pt-6 pt-md-1">
<div class="row">
<div class="col-12 ">

# Interesse in dit project, maar je hebt nog vragen?

<div class="call-box-bottom">
<a href="mailto:{{ site.data.contact.email }}" class="button">Contacteer ons!</a>   
</div>
</div>
</div>
</div>
</div>

<!--Onze partners voorstellen<-->
    
<div class="intro-med">
<div class="container pt-2 pb-2 pt-md-2 pb-md-2">
<div class="row justify-content-center">
<div class="col-12">
<div class="intro intro-med">
# Onze partners
</div>

We staat natuurlijk niet alleen in dit project. Hieronder vind je onze partners terug! 

{% include partner_boxes.html %}

</div>
</div>
</div>
</div>
