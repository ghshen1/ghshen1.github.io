---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(Equal contribution <sup> # </sup>, Corresponsding authors*.)

{% include base_path %}
{% for post in site.publications reversed %}
  {% include archive-single1.html %}
{% endfor %}

- - -

{% for post in site.publications.preprints reversed %}
  {% include archive-single1.html %}
{% endfor %}

Service
======
Reviewer for
* Journal of the Royal Statistical Society: Series B
* Journal of the American Statistical Association
* Computational Statistics & Data Analysis
