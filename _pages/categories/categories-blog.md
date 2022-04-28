---
layout: archive
permalink: categories/blog/
author_profile: true
---

# 일상생활이나 프로젝트를 하면서 느낀 생각을 적는 곳입니다.

{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}