---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---

This is some text.

## Organizers

{% for p in site.data.organizers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}

This is some more text over here. 

## Invited Speakers

{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}