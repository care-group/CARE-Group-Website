---
layout: default
title: Vacancies
---

<ul class="news list-unstyled">
{% for post in site.posts %}
    {% if post.type == "vacancy" %}
        {% include vacancy-item.html item=post %}
    {% endif %}
{% endfor %}
</ul>