---
layout: layout
release: 2020
version: 1.0
---

# Demo File

This is a demo file.

The {{page.version}} version of this document was released in {{page.release}}.

Demo: {{ site.when }}

## Data file Test

{% for item in site.data.demo %}

The country on {{ item.name }} was created in {{ item.date }}. Flag is {{ item.flag }}.

{% endfor %}

## Table

|Column 1 | Column 2 |
|---------|----------|
|row 1    |row 1     |
|row 2    |row 2     |


# Inline Code

This is some inline code: `select 23`

## Code Block

```
for x in y:
	do this
```

## Checkboxes

-[ ] Vanilla 
-[x] Chocolate





