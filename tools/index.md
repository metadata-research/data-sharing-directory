---
title: Tools
slug: index
type: index
---
{% assign tools = site.pages | where:'type','tool' | sort:"name" %}

Tools
=========

{% for tool in tools %}
{{ tool.title }}
--------------------
Sub-categories
: {% for subcategory in tool.sub_categories %} {{ subcategory }}{% endfor %}

Started
: {{ tool.started }}

Founded by
: {{ tool.founded_by }}

Current URL
: <{{ tool.current_url }}>

Goals
: {{ tool.goals }}

Status
: {{ tool.status}}
 
{% endfor %}