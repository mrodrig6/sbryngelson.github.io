---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---

## About 


{% for member in site.data.pi %}

<div class="row">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h3>{{ member.name }}</h3>
  <i style="font-size:20px">{{ member.info }}</i><br>

  {% if member.website %}<a href="{{ member.website }}" target="_blank"><i class="fa fa-home fa-3x"></i></a> {% endif %}
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  {% if member.number_educ == 6 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  <li> {{ member.education6 }} </li>
  {% endif %}

  </ul>
</div>

{% endfor %}

## Sketch

Mauro Rodriguez Jr. research aims to understand, model and manipulate flows via numerical simulation of multi-component flows with non-linear deformations. 
He is currently a Postdoctoral Scholar Research Associate at the California Institute of Technology, mentored by Professor Tim Colonius. 
He holds a Ph.D. in Mechanical Engineering from the University of Michigan, supervised by Professor Eric Johnsen.

{% if site.data.awards %}
## Awards

{% for award in site.data.awards %}
* {{ award.name }}
{% endfor %}

{% endif %}

{% if site.data.grants %}
## Grants

{% for grant in site.data.grants %}
* {{ grant.name }}
{% endfor %}

{% endif %}

## Collaborators

* <a href="http://colonius.caltech.edu/" target="_blank">Professor Tim Colonius (Computational Flow Physics, Caltech)</a>
* <a href="http://www-personal.umich.edu/~ejohnsen/" target="_blank">Professor Eric Johnsen (Mechanical Engineering, University of Michigan)</a>
* <a href="https://histotripsy.umich.edu/" target="_blank">Professor Zhen Xu (Xu Lab, University of Michigan)</a>
* <a href="https://www.franck.engr.wisc.edu/" target="_blank">Professor Christian Franck (Franck Lab, University of Wisconsin)</a>
* <a href="https://aero.engin.umich.edu/people/kenneth-powell/" target="_blank">Professor Ken Powell (University of Michigan)</a>
* <a href="https://bryngelson-research.com/" target="_blank">Dr. Spencer Bryngelson (Computational Flow Physics, Caltech)</a>
* <a href="https://kevinschmidmayer.github.io/overview/" target="_blank">Dr. Kevin Schmidmayer (Sopra Steria, France)</a>
* <a href="https://marchdf.github.io/" target="_blank">Dr. Marc Henry de Frahan (National Renewable Energy Lab)</a>


