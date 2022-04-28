---
layout: archive
permalink: categories/blog/
author_profile: true
---
<img src="./img/codeing.jpg" style=" width: 100vw; height: 30vh; object-fit: cover">
<h2>일상생활이나 프로젝트를 하면서 느낀 생각을 적는 곳입니다.</h2>
<hr>
{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}