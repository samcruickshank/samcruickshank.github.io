---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  If you have difficulties accessing any of these papers, feel free to send a quick email to me at sam.cruickshank [at] wsl.ch and I will be more than happy to send you a copy. 
  

  You can also find my articles on <u><a href="https://scholar.google.ch/citations?user=ht6_3YQAAAAJ&hl=en">my Google Scholar profile</a>.</u>
 


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
