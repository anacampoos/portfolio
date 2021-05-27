---
layout: allprojects
title: Work
---

<h1>{{ page.title }}</h1>

<ul>
    {% for project in site.allprojects %}
        <hr>
        <li>
            <a href= "{{ project.link }}" title="{{project.title }}"> 
            {{ project.title }}
            <figure>
                <img src="{{ project.image-src }}" alt="{{ project.image-alt }}">
            </figure>
            </a>
        </li>
    {% endfor %}