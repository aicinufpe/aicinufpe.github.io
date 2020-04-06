---
title: "CIn AI - Team"
layout: gridlay
excerpt: "CIn AI: Team members"
sitemap: false
permalink: /team/
---

# Group Members


### Staff
---

{% assign number_printed = 0 %}
{% for member in site.staff_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4><a href="{{ staff_member.url }}"> {{ member.title }}</a></h4>
  <i>{{ member.position }}<br>email: <{{ member.email }}></i><br>
  {{ member.education }}<br>
  {{ member.educ_instituition }}
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}
