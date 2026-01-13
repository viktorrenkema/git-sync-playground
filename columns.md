---
description: >-
  Page with columns
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: true
  pagination:
    visible: true
---

# Top-level H1

## Top-level H2

### Top-level H3

<details>

<summary>Expandable title</summary>

# Expandable H1

Expandable body

## Expandable H2

Expandable details

</details>

{% columns %}
{% column %}

# Column H1

Column body

## Column H2

Column details
{% endcolumn %}

{% column %}

# Second column H1

Second column body
{% endcolumn %}
{% endcolumns %}
