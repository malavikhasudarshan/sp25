---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 6
---

# Staff

<!-- Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`. -->

Jump to: [Instructors](#inst), [Lead Teaching Assistants](#leads), [UCS2s](#ucs2s), [UCS1s](#ucs1s).


## Course Staff Email
Contact course staff via Ed with any questions or concerns. For sensitive matters, the staff email address [data100.instructors@berkeley.edu](mailto:data100.instructors@berkeley.edu) is monitored by the instructors and a few lead TAs.

<a name = 'inst'></a>

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

<a name = 'leads'></a>

{% assign lead_ta = site.staffers | where: 'role', 'Lead TA' %}
{% assign num_lead_tas = lead_ta | size %}
{% if num_lead_tas != 0 %}
## Lead Teaching Assistants

{% for staffer in lead_ta %}
{{ staffer }}
{% endfor %}
{% endif %}

<a name = 'ucs2s'></a>

{% assign ucs2 = site.staffers | where: 'role', 'UCS2' %}
{% assign num_ucs2 = ucs2 | size %}
{% if num_ucs2 != 0 %}
## UCS2

{% for staffer in ucs2 %}
{{ staffer }}
{% endfor %}
{% endif %}

<a name = 'ucs1s'></a>

{% assign ucs1 = site.staffers | where: 'role', 'UCS1' %}
{% assign num_ucs1 = ucs1 | size %}
{% if num_ucs1 != 0 %}
## UCS1

{% for staffer in ucs1 %}
{{ staffer }}
{% endfor %}
{% endif %}

