---
layout: template.html
title: Cats
tags: page  

---
# Zach loves {{ title }}!
Some good cat names:

<ul>
    {% for cat in cats -%}
        <li>{{ cat }}</li>
    {% endfor -%}
</ul>
