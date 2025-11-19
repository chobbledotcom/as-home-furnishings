---
layout: services.html
title: Services | A & S Home Furnishings
description: House clearances, removals and Brand new furniture in Barton-Upon-Humber
nav_item: true
nav_title: Services
order: 3
---
# Services

A & S Home Furnishings offers a range of services including:

{% assign services = collections.service | sort: "data.order" %}

{% for service in services -%}*   [{{ service.data.nav\_title }}]({{ service.url }}#content)
{%- endfor %}

For all enquiries, call Andy on **[07719 519 745](tel:07719519745)**