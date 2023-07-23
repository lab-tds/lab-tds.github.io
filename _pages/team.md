---
layout: gridlay
permalink: /team/
title: team
description:
nav: true
nav_order: 0
sitemap: false
---

## Group Members

Jump to [reseachers](#Reseachers),[colaborators](#colaborators), [scientific-initiation students](#scientific-initiation), [specialization students](#specialization-students), [master students](#master), [doctoral students](#doctoral), [postdoctoral students](#postdoctoral-students), [alumni](#alumni).
<hr>

## Reseachers

<div class="row team-card">
  {% for member in site.data.team_members %}
 <div class="col-sm-6 clearfix">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4>
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
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
  </ul>

  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>

  </div>
  {% endfor %}
</div>

<hr>

## Colaborators

<div class="row team-card">
  {% for member in site.data.colaborators %}
    <div class="col-sm-6 clearfix">
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
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
  </ul>

  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>

    </div>
  {% endfor %}
</div>

<hr>
<h1 class="mt-6 text-center">Staff</h1>

## Scientific Initiation

<div class="row team-card">
  {% for member in site.data.students_SI %}
    <div class="col-sm-6 clearfix">
     <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
    
  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>
    
    </div>
  {% endfor %}
</div>

<hr>

## Specialization Students

<div class="row team-card">
  {% for member in site.data.students_spc %}
    <div class="col-sm-6 clearfix">
     <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
  
  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>
    </div>
  {% endfor %}
</div>


<hr>

## Master

<div class="row team-card">
  {% for member in site.data.students_master %}
    <div class="col-sm-6 cleafix">
     <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
    
  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>    
    </div>
  {% endfor %}
</div>

<hr>

## Doctoral

<div class="row team-card">
  {% for member in site.data.students_doctoral %}
    <div class="col-sm-6 clearfix">
     <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>

  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>  
    </div>
  {% endfor %}
</div>

<hr>

## Postdoctoral

<div class="row team-card">
  {% for member in site.data.students_posdoc %}
    <div class="col-sm-6 clearfix">
     <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
      <h4>{{ member.name }} <span class="fi fi-{{member.nationality}}"></span></h4> 
     <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> --></i>
  
  <!-- Link Icons -->
   <div class="icons team-icons mb-4" style="falign-content: center">
    {% if member.lattes %}
       <a href="{{ member.lattes }}" target="_blank"><i class="ai ai-lattes"></i></a>
    {% endif %}
   {% if member.github %}
      <a href="{{ member.github }}" target="_blank"><i class="fab fa-github"></i></a>
   {% endif %}
   {% if member.orcid %}
      <a href="{{ member.orcid }}" target="_blank"><i class="fab fa-orcid"></i></a>
   {% endif %}
   {% if member.gscholar %}
     <a href="{{ member.gscholar }}" target="_blank"><i class="fab fa-google"></i></a>
   {% endif %}
   </div>  
    </div>
  {% endfor %}
</div>

<hr>

## Alumni

<div class="row">

<div class="col-sm-6 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}<br>
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Master Students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}<br>
{% endfor %}
</div>

</div>

<div class="row">

<div class="col-sm-6 clearfix">
<h4>Doctoral and Postdoctoral Students</h4>
{% for member in site.data.alumni_doc %}
{{ member.name }}<br>
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Specialization Students</h4>
{% for member in site.data.alumni_spc %}
{{ member.name }} <br>
{% endfor %}
</div>

</div>
