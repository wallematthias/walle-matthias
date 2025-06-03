---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


## Research Highlights

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}
<br>
<script src="https://bibbase.org/show?bib=https%3A%2F%2Fbibbase.org%2Fnetwork%2Ffiles%2FFBFpAc9d9fpCyd3Rk&noBootstrap=1&jsonp=1"></script>
