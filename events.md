---
layout: default
title: Events
---

<ul class="news list-unstyled">
{% for post in site.posts %}
    {% if post.type == "event" %}
        {% include event-item.html item=post %}
    {% endif %}
{% endfor %}
</ul>