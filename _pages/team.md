---
title: Team
layout: default
bodyClass: page-team-list
permalink: /team
---

<!-- Wat is een fablab?-->
{::options parse_block_html="true" /}
<div class="intro">
<div class="container pt-8 pt-md-1">
<div class="row">
<div class="col-12 ">
# Wat is een FabLab?

Maar wat is nu eigenlijk een FabLab? Wat zijn de waarden en normen? En wat kun je er nu eigenlijk doen?

</div>
</div>
</div>
</div>

{::options parse_block_html="true" /}
<div class="intro-med container pt-10 pt-md-5">
<div class="row">
<div class="col-12 col-md-10">

Een <strong>fab lab</strong> (afkorting van het Engelse fabrication laboratory), is een coöperatieve werkplaats waar uitvinders en ontwikkelaars gebruik kunnen maken van een collectieve infrastructuur. Hier staan onder meer computers, 3D-printers, lasersnijders en frezen.

Om de naam fab lab te mogen dragen, moet deze werkplaats voldoen aan het Fab Lab Charter. Het is gebruikelijk op ontwikkelde producten geen patenten te nemen omdat het verdedigen van een patent dat in een Fab Lab is ontwikkeld vrij moeilijk is (er zijn meer dan 1500 labs wereldwijd; hun output te monitoren is onmogelijk voor een Fab Lab uitvinder) en omdat Fab Labs in de geest van open source werken.

Bij veel fab labs zoals onder andere bij De Creatieve STEM worden ook opleidingen in de vorm van cursussen en workshops gekoppeld aan de digitale werkplaats. Hierdoor ontstaan langzaamaan totaalconcepten waarin het complete traject van leren, maken, verspreiden en presenteren in de fab labs terug te vinden is.

#### Het FabLab Charter

**Missie:**
een fablab faciliteert uitvindingen en innovatie door computergestuurde gereedschappen binnen het bereik van individuen te brengen

**Open toegang:**
iedereen mag het fablab gebruiken om (bijna) alles te maken (zolang dat niemand schade berokkent); je moet zelf uitvinden hoe je het doet en je moet het fablab delen met anderen

**Kennis:** in het fablab leer je van anderen en door het uitvoeren van projecten; je wordt geacht om opgedane kennis weer over te dragen aan anderen, en bij te dragen aan de beschikbare documentatie en gebruiksaanwijzingen

**Verantwoordelijkheid:** je bent verantwoordelijk voor:

* veiligheid: veilig werken met de gereedschappen en machines
* opruimen: het fablab in een schonere staat verlaten dan dat je het aantrof
* bedrijfsvoering: helpen met voorraadbeheer, onderhouds- en reparatiewerkzaamheden, en het melden van incidenten
* Geheimhouding: alle ontwerpen en processen die ontwikkeld worden in een fablab komen vrij beschikbaar voor persoonlijk gebruik, hoewel intellectueel eigendom naar keuze beschermd kan worden

**Commercie:** commercieel gebruik van het fablab wordt niet uitgesloten, voor zover dat een vrije toegang tot het lab niet in de weg staat; commerciële activiteiten die in het lab ontkiemen worden geacht het fablab op zeker moment te ontgroeien en, eenmaal tot wasdom gekomen, ook tot voordeel te strekken van de uitvinders, het lab en netwerken die tot hun succes leidden.

</div>
</div>
</div>

<!-- Wat is kets -->
<div class="intro intro-med">
<div class="container pt-8 pt-md-1">
<div class="row">
<div class="col-12 ">
  
# Wat is KET's?

KET's is een project gesponsord door Digital Skill Fund België (DBSF)
</div>
</div>
</div>
</div>

<div class="intro-med container pt-10 pt-md-10">
<div class="row">
<div class="col-12 col-md-10">

Met Inclusive KETs bouwen we de hefbomen beschikbaar binnen De Creatieve STEM vzw uit om
(kwetsbare) jongvolwassenen te bereiken, en Key Enabling Technologies (KETs) aan te brengen.
Dit doen we via faciliteren, opleiden en uitstralen met aandacht voor diversiteit op vlak van rolmodellen
en gendering of making. Inspiratiebronnen hierbij zijn Fab Academy, Fabricademy, De Waag
Amsterdam, en Wahallab Nederland. Jongvolwassenen worden aangespoord, begeleid en
ondersteund in hun zoektocht in het verwerven van kerncompetenties, en dit via oplossen van
problematieken die hun na aan het hart liggen.
</div>
</div>
</div>

<!-- WIE ZIJN WIJ -->
<div class="intro intro-med">
<div class="container pt-8 pt-md-1">
<div class="row">
<div class="col-12 ">
# Wie zijn wij?

De Creatieve STEM heeft als educatief doel het bevorderen van de ontwikkeling van (talenten van) jongeren. De vereniging wenst een kader te creëren waarbinnen kinderen hun talenten in techniek, wetenschap en talen ontwikkelen. 
       
</div>
</div>
</div>
</div>

<div class="intro-med container pt-10 pt-md-10">
<div class="row">
<div class="col-12 col-md-10">

Met vrije inloopmomenten, cursussen, workshops, speciale vakantieprogramma’s en activiteiten voor scholen en groepen brengt de vereniging dit in de praktijk. De vereniging biedt toegang tot gereedschappen die men thuis niet heeft en tot minder bekende materialen en technieken. Doel is steeds weer het stimuleren van creativiteit, interesse, ontwikkeling en ondernemerschap, met aandacht voor gelijke kansen voor alle kinderen. 
</div>
</div>
</div>

<div class="container pt-5 pb-5 pt-md-7 pb-md-7">
<div class="row justify-content-center">
<div class="col-12">
<h4 class="title-3 text-dark mb-4">De Creatieve STEM pijlers</h4>
</div>

{% include feature_boxes.html %}

</div>
</div>

<div class="intro intro-med">
<div class="container">
<div class="row">
<div class="col-12">

# Van wie krijg je les?

Binnen de FabLab wereld staat kennis delen centraal. Daarom zochten we inhouse, maar ook daarbuiten de beste docenten per passend onderwerp. Hieronder leer je ons allemaal kennen! 
</div>
</div>
</div>
</div>
<!-- lijst van het team--> 
<div class="intro-med container pb-6">
<div class="row">
{% for team in site.team %}
{% unless team.dontshow %}
<div class="col-12 col-md-6 mb-1">
<div class="team team-summary">
{% if team.image %}
<div class="team-image">
<img alt="{{ team.title }} logo"
            class="img-fluid mb-2"
            src="{{site.baseurl}}{{ team.image }}"
          />
</div>
{% endif %}
<div class="team-meta">
<h2 class="team-name">{{ team.title }}</h2>
<p class="team-description">{{ team.jobtitle }}</p>
{% if team.linkedinurl %}
<a target="_blank" href="{{ team.linkedinurl }}">LinkedIn</a> 
{% endif %}
</div>
<div class="team-content">{{ team.content | markdownify }}</div>
</div>
</div>
{% endunless %}
{% endfor %}
</div>
</div>


<!-- CONTACT PAGE -->
<div class="intro intro-med">
<div class="container">
<div class="row">
<div class="col-12">
<h1>Contact</h1>
</div>
</div>
</div>
</div>
<div class="container">
<div class="row">
<div class="col-12 col-md-8">
<h3>Voor info over workshops en inhoud</h3>
<p>Contacteer Amy</p>
<ul>
<li><strong>Tel: </strong>{{ site.data.contact.phone }}</li>
<li><strong>Email: </strong><a href="mailto:{{ site.data.contact.email }}">
{{ site.data.contact.email }}</a></li>
{% if site.data.contact.address %}
<li><strong>Adres: </strong>{{ site.data.contact.address }}</li>
{% endif %}
</ul>
<h3>Voor info over contracten en financiën</h3>
<p>Contacteer Louise</p>
<ul>
<li><strong>Tel: </strong>{{ site.data.contact.phone2 }}</li>
<li><strong>Email: </strong><a href="mailto:{{ site.data.contact.email2 }}">
{{ site.data.contact.email2 }}</a></li>
{% if site.data.contact.address %}
<li><strong>Adres: </strong>{{ site.data.contact.address }}</li>
{% endif %}
</ul>
<h4 class="mt-4">Werkuren</h4>
<table class="table table-sm opening-hours-table">
<tr>
<td class="day font-weight-bold">Maandag</td>
<td class="opens">9:00am</td>
<td>-</td>
<td class="closes">17:30pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Dinsdag</td>
<td class="opens">9:00am</td>
<td>-</td>
<td class="closes">17:30pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Woensdag</td>
<td class="opens">13:00am</td>
<td>-</td>
<td class="closes">22:00pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Donderdag</td>
<td class="opens">9:00am</td>
<td>-</td>
<td class="closes">17:30pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Vrijdag</td>
<td class="opens">9:00am</td>
<td>-</td>
<td class="closes">17u30pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Zaterdag</td>
<td class="opens">10:00am</td>
<td>-</td>
<td class="closes">17:00pm</td>
</tr>
<tr>
<td class="day font-weight-bold">Zondag</td>
<td class="opens">Gesloten</td>
<td> </td>
<td class="closes"></td>
</tr>
</table>
</div>
</div>
</div>
