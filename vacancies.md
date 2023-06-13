---
layout: default
title: Vacancies
---

<ul class="news list-unstyled">
{% assign total = 0 %}
{% for post in site.posts %}
    {% if post.type == "vacancy" %}
        {% include vacancy-item.html item=post %}
        {% assign total = total | plus: 1 %}
    {% endif %}
{% endfor %}
{% if total == 0 %}
    <p>Sorry, there are currently no open vacancies. Please check back later.</p>
{% endif %}
</ul>