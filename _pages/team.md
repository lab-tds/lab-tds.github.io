---
layout: gridlay
permalink: /team/
title: team
subtitle: Team
description:
nav: true
nav_order: 0
sitemap: false
---

Go to [Reseachers](#Reseachers), [Colaborators](#colaborators), [Undergraduate Students](#undergraduate-students), [Specialization Students](#specialization-students), [Master Students](#master), [Doctoral Students](#doctoral), [Postdoctoral Students](#postdoctoral-students), [Alumni](#alumni).
<hr>

## Reseachers

<div class="row team-card">
  {% for member in site.data.team.team_members %}
 <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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
  {% for member in site.data.team.colaborators %}
    <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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

## Undergraduate Students

<div class="row team-card">
  {% for member in site.data.team.students_under %}
    <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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
  {% for member in site.data.team.students_spc %}
    <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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
  {% for member in site.data.team.students_master %}
    <div class="col-sm-6 cleafix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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
  {% for member in site.data.team.students_doctoral %}
    <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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
  {% for member in site.data.team.students_posdoc %}
    <div class="col-sm-6 clearfix">
  {% if member.photo %}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
   {%- else -%}
      <img src="{{ site.url }}{{ site.baseurl }}/assets/img/teampic/member.png" class="img-responsive" width="25%" style="float: left" />
   {% endif %}
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

<div class="col-sm-6 mt-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.team.alumni_bsc %}
{{ member.name }}<br>
{% endfor %}
</div>

<div class="col-sm-6 mt-4 clearfix">
<h4>Master Students</h4>
{% for member in site.data.team.alumni_msc %}
{{ member.name }}<br>
{% endfor %}
</div>

</div>

<div class="row">

<div class="col-sm-6 mt-4 clearfix">
<h4>Doctoral and Postdoctoral Students</h4>
{% for member in site.data.team.alumni_doc %}
{{ member.name }}<br>
{% endfor %}
</div>

<div class="col-sm-6 mt-4 clearfix">
<h4>Specialization Students</h4>
{% for member in site.data.team.alumni_spc %}
{{ member.name }} <br>
{% endfor %}
</div>

</div>
