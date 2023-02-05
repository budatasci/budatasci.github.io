---
layout: page
title: Organizers
description: A listing of all the BUDSA e-board members.
---

# E-Board

{% assign eboard = site.staffers %}
{% for eboard in eboard %}
{{ eboard }}
{% endfor %}

