---
layout: layouts/base.njk
title: My meetup is amazing
---


## Not very amazing

Yes it is. Look at the different editions!


## Editions
<ul>
{% for edition in collections.editions | reverse %}
{% set item = edition %}
{% include "edition-details.njk" %}
{% endfor %}
</ul>


## Subscribe

Never miss out. You can subscribe to an [RSS feed](/feed.xml) of the meetups.
