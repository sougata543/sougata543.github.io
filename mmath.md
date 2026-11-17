---
title: Archive
photo: images/FMAB.jpg
---

## PhD

Exam papers from my PhD coursework.
{% assign phd_base = '/Archive/PhD/sem1/' %}
{% assign phd_courses = 'Representation Theory|Lie Groups and Lie Algebras' | split: '|' %}
<details class="sem">
<summary>Semester 1 (2026)</summary>
<table class="subject-table"><tbody>
{%- for course in phd_courses %}{% assign dir = phd_base | append: course %}
<tr><td>{{ course }}</td><td><div class="doc-links">
<a href="{{ dir | append: '/midsem_26.pdf' | relative_url | uri_escape }}">midsem</a>
<a href="{{ dir | append: '/endsem_26.pdf' | relative_url | uri_escape }}">endsem</a>
</div></td></tr>
{%- endfor %}
</tbody></table>
</details>

## MMath

Exam papers from my master's coursework at ISI Kolkata.
{% for sem in site.data.archive %}{% assign base = '/Archive/MMath/' | append: sem.path | append: '/' %}
<details class="sem">
<summary>{{ sem.label }}</summary>
<table class="subject-table"><tbody>
{%- for course in sem.courses %}{% assign dir = base | append: course %}
<tr><td>{{ course }}</td><td><div class="doc-links">
<a href="{{ dir | append: '/midsem_' | append: sem.year | append: '.pdf' | relative_url | uri_escape }}">midsem</a>
<a href="{{ dir | append: '/endsem_' | append: sem.year | append: '.pdf' | relative_url | uri_escape }}">endsem</a>
</div></td></tr>
{%- endfor %}
</tbody></table>
</details>
{% endfor %}
