---
layout: default
title: Outreach
---

The CARE Group is actively committed to support outreach activities, especially by offering engaging experiences to young students and hosting both virtual and actual visits to our laboratories.

{% include image-gallery.html folder="img/outreach" %}

See below the details of our recent outreach activities. These were conducted in association with the [TAS Open Labs project](https://www.tas.ac.uk/current-research-projects/open-tas/), an exciting new project where members of the public were able to remotely control a robot in a university laboratory from their own computer or laptop. Young students were able to experience the inner workings of our lab through the ‘eyes’ and ‘ears’ of the robot that they were operating. 

Through this immersive experience, they had an understanding and appreciation of what happens inside university lab spaces. We want people to understand that university labs are open to everyone and by using simple technology at home or school, we can open up areas that may previously have seemed inaccessible.

## Acknowledgements

The virtual visit to our laboratories using tele-presence robots at all these events have been facilitated by researchers involved in the OpenTAS project using tele-presence software developed by [Cybserselves Universal Ltd.](https://www.cyberselves.com/) The project has created the infrastructure for access via web/VR interfaces and telepresence laboratories researching Trustworthy Autonomous Systems (TAS). This contributes to the TAS Hub commitment to promote responsible research and innovation, engaging openly with the wider public about research plans and activities in TAS.

The [Robotic Assisted Living Testbed (RALT)](https://ralt.hw.ac.uk/) at Heriot-Watt University is a ‘Living-Lab' home-like environment designed to facilitate user-driven design and testing of innovative ICT Robotic solutions for healthy ageing and independent living.

Further information on the robots used at these events can be found at the following links:
- [MiRO](https://www.miro-e.com/)
- [Sphero](https://sphero.com/)
- [Spot](https://www.bostondynamics.com/products/spot)
- [Cozmo](https://www.digitaldreamlabs.com/pages/cozmo) - discontinued

## Events

<ul class="news list-unstyled">
{% for post in site.posts %}
    {% if post.type == "outreach" %}
        {% include outreach-item.html item=post %}
    {% endif %}
{% endfor %}
</ul>