---
layout: archive
permalink: categories/project/
author_profile: true
sidebar_main: true
---
<img src="https://github.com/INMD1/blog-site/blob/main/assets/image/project.jpg?raw=true" 
style=" width: 100vw; height: 30vh; 
        object-fit: cover;
        ">
<h2>현재 개발중인 프로젝트를 알리는 곳입니다.</h2>
<hr>
{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}