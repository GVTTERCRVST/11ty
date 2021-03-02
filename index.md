---
layout: template.html
title: Eleventy Project
tags: page  

---
# This is my {{ title }}!
Some Macs I have in my collection:

<ul>
    {% for mac in macs -%}
        <li>{{ mac }}</li>
    {% endfor -%}
</ul>
