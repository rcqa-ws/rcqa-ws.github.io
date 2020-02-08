---
layout: page
title: RCQA@AAAI
subtitle: Reasoning for Complex QA Workshop 2020
---

# Invited Speakers


<div class="container">
  <div class="row">

{% for p in site.data.speakers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include speakeranchor.html p=p %} {% endfor %}

</div>
</div>

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