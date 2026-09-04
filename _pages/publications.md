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

***
<small>(* denotes equal contribution)</small>
{% for group in site.data.publications %}
## {{ group.section }}
{% for pub in group.papers -%}
- [{{ pub.title }}]({{ pub.url }})  
  <small>{{ pub.authors | replace: '%ME%', '__Min-Jae Hwang__' }}</small>{% if pub.venue %}  
  <small>{{ pub.status | default: 'Published in' }}{% if pub.venue_prefix %} {{ pub.venue_prefix }}{% endif %} [{{ pub.venue }}]({{ pub.venue_url }}){% if pub.venue_note %} {{ pub.venue_note }}{% endif %}{% if pub.extra %} {{ pub.extra }}{% endif %}</small>{% endif %}

{% endfor %}{% if group.hr_after %}***{% endif %}{% endfor %}
