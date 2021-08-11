---
title: Standards
slug: index
type: index
---
{% assign standards = site.pages | where:'type','standard' | sort:"name" %}

=========

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
: <{{ standard.current_url }}>

Goals
: {{ standard.goals }}

Status
: {{ standard.status}}
 
{% endfor %}Standards


Additional Standards with a Rights Entity
-----------------------------------------

* Categories for the Description of Works of Art (CDWA) Lite
* CopyrightMD, Extension for use with the Metadata Encoding and Transmission Standard (METS)
* Dublin Core
* Learning Object Metadata (LOM)
* Metadata Object Description Schema (MODS)
* Preservation Metadata: Implementation Strategies (Premis)
* Public Broadcasting Metadata Dictionary (PBCore)
* Visual Resources Association (VRA) Core