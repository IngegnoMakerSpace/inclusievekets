---
title: Contact
layout: default
bodyClass: page-contact
permalink: /contact
---

<div class="intro intro-small">
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
        <li>
            <strong>Tel: </strong>{{ site.data.contact.phone }}</li>
        <li><strong>Email: </strong><a href="mailto:{{ site.data.contact.email }}">
            {{ site.data.contact.email }}</a></li>
        {% if site.data.contact.address %}
        <li><strong>Adres: </strong>{{ site.data.contact.address }}</li>
        {% endif %}
      </ul>
     <h3>Voor info over contracten en financiën</h3>
        <p>Contacteer Louise</p>
      <ul>
        <li>
            <strong>Tel: </strong>{{ site.data.contact.phone2 }}</li>
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
          <td class="opens">afwezig</td>
           <td></td>
          <td class="closes"></td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Dinsdag</td>
          <td class="opens">9:00am</td>
          <td>-</td>
          <td class="closes">17:30pm</td>
        </tr>
        <tr>
          <td class="day font-weight-bold">Woensdag</td>
          <td class="opens">9:00am</td>
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