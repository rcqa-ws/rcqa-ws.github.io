
# Organizers

{{% for p in site.data.organizers %} {% capture id %}{{ p[0] }}{% endcapture %} {% include profile.html p=p %} {% endfor %}}