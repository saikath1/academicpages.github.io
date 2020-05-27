---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Hello world
<li>
<a class="url"><span class="title"></span></a></br>
<span class="author"></span></br>
<span class="booktitle"></span>
<span class="if publisher">
<span class="publisher"></span>.
</span>
<span class="if pages">
  p. <span class="pages"></span>.
</span>
<span class="if year">
<span class="year"></span></span>
</br>
<a class="bibtexCodeLink">
  [bibtex]
</a>
</br></br>
</li>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=D2nEigIAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
