---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Each article title will direct you to the article abstract, permanent journal link, and direct PDF download. You can also find all my articles, including conference proceedings, on <u><a href="https://scholar.google.com/citations?user=VpA3ozAAAAAJ&hl=enm">my Google Scholar profile</a></u>.
  
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
