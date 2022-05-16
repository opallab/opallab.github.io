---
title: "OpAL Lab - Team"
layout: gridlay
excerpt: "OpAL Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

<!-- **We are  looking for new PhD students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**-->

[//]: #  Jump to [graduate](#graduate), [undergraduate](#undergraduate-students), [former](#alumni) members.

## Principal Investigator
{% assign number_printed = 0 %}
{% for member in site.data.pi %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
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

## Graduate Members
{% assign number_printed = 0 %}
{% for member in site.data.graduate_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>Duration: {{ member.duration }} <br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
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

<!--## Undergraduate Members-->
<!---->
<!--{% assign number_printed = 0 %}-->
<!--{% for member in site.data.undergraduate_members %}-->
<!---->
<!--{% assign even_odd = number_printed | modulo: 2 %}-->
<!---->
<!--{% if even_odd == 0 %}-->
<!--<div class="row">-->
<!--{% endif %}-->
<!---->
<!--<div class="col-sm-6 clearfix">-->
<!--  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />-->
<!--  <h4>{{ member.name }}</h4>-->
<!--  <i>{{ member.info }}<br>Duration: {{ member.duration }} <br>email: <{{ member.email }}></i>-->
<!--  <ul style="overflow: hidden">-->
<!---->
<!--  {% if member.number_educ == 1 %}-->
<!--  <li> {{ member.education1 }} </li>-->
<!--  {% endif %}-->
<!---->
<!--  {% if member.number_educ == 2 %}-->
<!--  <li> {{ member.education1 }} </li>-->
<!--  <li> {{ member.education2 }} </li>-->
<!--  {% endif %}-->
<!---->
<!--  {% if member.number_educ == 3 %}-->
<!--  <li> {{ member.education1 }} </li>-->
<!--  <li> {{ member.education2 }} </li>-->
<!--  <li> {{ member.education3 }} </li>-->
<!--  {% endif %}-->
<!---->
<!--  {% if member.number_educ == 4 %}-->
<!--  <li> {{ member.education1 }} </li>-->
<!--  <li> {{ member.education2 }} </li>-->
<!--  <li> {{ member.education3 }} </li>-->
<!--  <li> {{ member.education4 }} </li>-->
<!--  {% endif %}-->
<!---->
<!--  {% if member.number_educ == 5 %}-->
<!--  <li> {{ member.education1 }} </li>-->
<!--  <li> {{ member.education2 }} </li>-->
<!--  <li> {{ member.education3 }} </li>-->
<!--  <li> {{ member.education4 }} </li>-->
<!--  <li> {{ member.education5 }} </li>-->
<!--  {% endif %}-->
<!---->
<!--  </ul>-->
<!--</div>-->
<!---->
<!--{% assign number_printed = number_printed | plus: 1 %}-->
<!---->
<!--{% if even_odd == 1 %}-->
<!--</div>-->
<!--{% endif %}-->
<!---->
<!--{% endfor %}-->
<!---->
<!--{% assign even_odd = number_printed | modulo: 2 %}-->
<!--{% if even_odd == 1 %}-->
<!--</div>-->
<!--{% endif %}-->

## Former Members

{% assign number_printed = 0 %}
{% for member in site.data.former_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
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


[//]: #  ## Former students
[//]: #  <div class="row">

[//]: # <div class="col-sm-4 clearfix">
[//]: # <h4>Visitors</h4>
[//]: # {% for member in site.data.alumni_visitors %}
[//]: # {{ member.name }}
[//]: # {% endfor %}
[//]: # </div>

[//]: #  <div class="col-sm-4 clearfix">
[//]: #  <h4>Master students</h4>
[//]: #  {% for member in site.data.alumni_msc %}
[//]: #  {{ member.name }}
[//]: #  {% endfor %}
[//]: #  </div>

[//]: # <div class="col-sm-4 clearfix">
[//]: # <h4>Bachelor Students</h4>
[//]: # {% for member in site.data.alumni_bsc %}
[//]: # {{ member.name }}
[//]: # {% endfor %}
[//]: # </div>

[//]: #  </div>
