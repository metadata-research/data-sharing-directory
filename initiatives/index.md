---
title: Community Initiatives
slug: index
type: index
---
{% assign initiatives = site.pages | where:'type','initiative' | sort:"name" %}

Community Initiatives
=========

{% for initiative in initiatives %}
{{ initiative.title }}
--------------------
Sub-categories
: {% for subcategory in initiative.sub_categories %} {{ subcategory }}  {% endfor %}

Started
: {{ initiative.started }}

Founded by
: {{ initiative.founded_by }}

Current URL
: <{{ initiative.current_url }}>

Goals
: {{ initiative.goals }}

{% if initiative.status %}
Status
: {{ initiative.status}}
{% endif %}
* * *
{% endfor %}