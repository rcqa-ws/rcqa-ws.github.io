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

<!-- # Questions

Please use the following link to [ask speaker questions](https://docs.google.com/presentation/d/e/2QANgcCBGtg9oOugqkYHuthxzUBc8z08eOLMnVAQAH8YJNlwIOsB6G_cvTZx0_StSKMv0pHQxHUx-OLn1qEw/askquestion?seriesId=7362e393-747f-470c-be17-070388e53f4b).
 -->
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