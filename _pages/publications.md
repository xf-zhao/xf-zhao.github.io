---
layout: page
permalink: /publications/
title: Publications
nav: true
nav_order: 2
sort_by: date
order: descending
type_order: [article, inbook, book, unpublished, misc, report, conference, incollections, inproceedings, proceedings]
type_names: {unpublished: working papers, report: reports, article: journal articles, 
      inproceedings: conference articles & others}
---

<!-- _pages/publications.md -->
<div class="publications">
<a href="https://scholar.google.com/citations?user=sLwQ22MAAAAJ"><b>Google Scholar Profile</b></a><br>

<em>in reversed chronological order / <b>*</b>equal contributions / <b><p style="background-image: linear-gradient(to right, rgba(255,0,0,0.01), rgba(255,0,0,.21));display:inline">featured works</p></b></em>

{% bibliography --template bib --group_by type,year --group_order ascending,descending %}


</div>
