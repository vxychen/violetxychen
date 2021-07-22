---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

Under development

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

### Conference Proceedings

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

