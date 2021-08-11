---
title: Standards
slug: index
type: index
---
{% assign standards = site.pages | where:'type','standard' | sort:"name" %}

{% for standard in standards %}
{{ standard.title }}
--------------------
Sub-categories
: {% for subcategory in standard.sub_categories %} {{ subcategory }}{% endfor %}

Started
: {{ standard.started }}

Founded by
: {{ standard.founded_by }}

Current URL
: {{ standard.current_url }}

Goals
: {{ standard.goals }}

Status
: {{ standard.status}}
 
{% endfor %}
