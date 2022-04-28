---
layout: archive
permalink: categories/coding/
author_profile: true
---
<img src="https://github.com/INMD1/blog-site/blob/main/_pages/categories/img/codeing.jpg?raw=true" 
style=" width: 100vw; height: 30vh; 
        object-fit: cover;
        ">
<h2>개발을 하면서 유용한 정보를 올리는 곳입니다.</h2>
<hr>
{% assign posts = site.categories.coding %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}