---
layout: archive
permalink: categories/project/
author_profile: true
sidebar_main: true
---

현재 개발중인 프로젝트를 알리는 곳입니다.

{% assign posts = site.categories.project %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}