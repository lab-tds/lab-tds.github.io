---
layout: page
permalink: /teaching/
title: teaching
subtitle: Teaching
description: Courses developed and sponsored by the Lab
nav: true
nav_order: 5
---

<!-- For now, this page is assumed to be a static description of your courses. You can convert it to a collection similar to `_projects/` so that you can have a dedicated page for each course.

Organize your courses by years, topics, or universities, however you like! -->


<div class="container mt-4 text-center">
     {% if site.data.courses %}
    <div class="row">
      {% for course in site.data.courses %}
      {% if course.show %}
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="card card-teaching">
                <a class="img-card" href="{{ course.link }}">
                <img src="{{ site.url }}{{ site.baseurl }}/assets/img/{{ course.img }}" class="card-img-top" alt="{{ course.title }}"> </a>
                <div class="card-content">
                <h4 class="card-title">
                <a href="{{ course.link }}"> {{ course.title }}</a>
                </h4>
                <p class="card-text">{{ course.description }}</p>
                <p class="card-text">{{ course.workload }}</p>
                </div>
                    <div class="card-read-more">
                        <a href="{{ course.link }}" class="btn btn-link btn-block"> View</a>
                    </div>
            </div>
        </div>
      {% else %}
       <!-- To do: 'show = false' design card -->  
      {% endif %}
      {% endfor %}
    </div>
    {% else %}
    <div class="row">
        <div class="col-lg-4 col-md-6 mb-4">
            <div class="card card-teaching">
                <img src="{{ site.baseurl }}/assets/img/under_construction_board.png" class="card-img-top" alt="{{ course.title }}">
                <div class="card-content text-center">
                <h4 class="card-title"> New courses coming soon </h4>
                <p class="card-text"> We are working on it!</p>
                </div>
            </div>
        </div>
    </div>
           <br><br><br><br>
     {% endif %}
  </div>

  
