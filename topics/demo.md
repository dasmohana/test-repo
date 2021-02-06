---
layout: layout
release: 2020
version: 1.0
---

# Demo File

This is a demo file.

The {{page.version}} version of this document was released in {{page.release}}.

Demo: {{ site.when }}

Data file contents

{% for item in site.data.demo %}

The country on {{ item.name }} was created in {{ item.date }}. Flag is {{ item.flag }}.

{% endfor %}



