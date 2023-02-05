---
layout: page
title: Meet the E-Board
description: A listing of all the BUDSA e-board members.
---

# E-Board

{% assign eboard = site.staffers %}
{% for eboard in eboard %}
{{ eboard }}
{% endfor %}

