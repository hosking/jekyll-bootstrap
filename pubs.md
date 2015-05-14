---
layout: page
title: Publications
header: Publications
tagline: Books, Articles, Papers, Proofs, Reports, Manuals, Theses
group: navigation
---

Books
-----
{% bibliography --query @book %}

Articles & Papers
--------
{% bibliography --query @article --query @inproceedings %}

Proofs
------
{% bibliography --query @incollection %}

Reports
-------
{% bibliography --query @techreport %}

Manuals
-------
{% bibliography --query @manual %}

Dissertations
-------------
{% bibliography --query @phdthesis %}

Theses
------
{% bibliography --query @mastersthesis %}
