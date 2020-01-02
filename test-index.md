---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---

# Organizers

{% for p in site.data.organizers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}

# Invited Speakers

{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% unless p[0] == "tba" %} {% include profile.html p=p %} {% endunless %} {% endfor %}