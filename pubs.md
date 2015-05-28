---
layout: page
title: Publications
header: Publications
tagline: <a href="#Books">Books</a>, <a href="#Papers">Papers</a>, <a href="#Proofs">Proofs</a>, <a href="#Reports">Reports</a>, <a href="#Manuals">Manuals</a>, <a href="#Theses">Theses</a>
group: navigation
---

<a name="Books"></a>Books
-----
{% bibliography --query @book %}

<a name="Papers"></a>Papers
--------
{% bibliography --query @article @inproceedings %}

<a name="Proofs"></a>Proofs
------
{% bibliography --query @incollection %}

<a name="Reports"></a>Reports
-------
{% bibliography --query @techreport %}

<a name="Manuals"></a>Manuals
-------
{% bibliography --query @manual %}

<a name="Theses"></a>Theses
------
{% bibliography --query @mastersthesis @phdthesis %}
