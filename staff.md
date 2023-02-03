---
layout: page
title: BUDSA E-Board Members
description: A listing of all the BUDSA members.
---

# E-Board

{% assign eboard = site.staffers %}
{% for eboard in eboard %}
{{ eboard }}
{% endfor %}

