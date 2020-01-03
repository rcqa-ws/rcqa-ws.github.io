---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---

This is some text.

## Organizers

<div class="container">
  <div class="row">

{% for p in site.data.organizers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}

</div>
</div>


## Invited Speakers

<div class="container">
  <div class="row">

{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}

</div>
</div>