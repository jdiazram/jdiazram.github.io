---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

 <script src="https://bibbase.org/service/mendeley/74c52b30-dfe0-36a7-acfb-14950def9662/group/02975d02-91a7-304a-858e-a812d33a313a?jsonp=1"></script> 
 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
