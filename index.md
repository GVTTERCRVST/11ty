---
layout: template.html
title: Eleventy Project
tags: page  

---
# This is my {{ title }}!
Some good cat names:

<ul>
    {% for cat in cats -%}
        <li>{{ cat }}</li>
    {% endfor -%}
</ul>
