---
title: Archive
---

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
