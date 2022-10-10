---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
(Equal contribution <sup> # </sup>, Corresponsding authors*.)
{% for post in site.publications reversed %}
  {% include archive-single1.html %}
{% endfor %}

Preprints
======
{% include base_path %}

{% for post in site.Preprints reversed %}
  {% include archive-single1.html %}
{% endfor %}
