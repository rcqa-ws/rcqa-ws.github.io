---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---

# Invited Speakers

The following is the invited talks program for RCQA-20: 

<div class="container">
  <div class="row">
    <table class="table">
  	<tr>
{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include speakerinfo.html p=p %} {% endfor %}
	</tr>
  </table>
</div>
</div>

<!-- </div>
</div> -->

<!-- {% for p in site.data.speakers %}

{% capture id %}{{ p[0] }}{% endcapture %}

- {{% include p[1].name %}}

{% endfor %} -->


<!-- ## Ray Mooney

## Nasrin Mostafazadeh

## Dan Roth

## Sameer Singh

## Robyn Speer

## Bishan Yang -->