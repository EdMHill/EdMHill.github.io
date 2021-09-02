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

PUBLICATIONS TO BE UPDATED

<sup>*</sup> indicates that authors made equal contributions

# Peer-reviewed papers

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# Preprints

{% for post in site.preprints reversed %}
  {% include archive-single.html %}
{% endfor %}

# Book chapters

**Edward M. Hill**, Thomas House. (2019). &quot;Modelling the spread of mood.&quot; In: Breidenbach, Birgit and Docherty, Thomas, (eds.) Mood: Interdisciplinary Perspectives, New Theories. Routledge, pp. 87-108. ISBN 9780429535116 <br/>
<a href="https://doi.org/10.4324/9780429259432" target="_blank"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a>

# PhD thesis

**Edward M. Hill** (2017). &quot;Mathematical modelling approaches for spreading processes : zoonotic influenza and social contagion.&quot; PhD thesis, University of Warwick. <br/>
<a href="http://wrap.warwick.ac.uk/91483/" target="_blank"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a>
<a href="http://wrap.warwick.ac.uk/91483/1/WRAP_Theses_Hill_2017.pdf" target="_blank"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
