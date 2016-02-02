---
title: History
process:
    markdown: false
    twig: true
---

Hawks Football has a long and storied history, including the individual histories of both Rib Lake and Prentice High School football. Enjoy this unique look at our historical records and, if you're on the team, we hope to find your name one day amongst some of the legends listed here.

<ul>
{% for p in page.find('/history').children if p != page %}
<li><a href='{{ p.url }}'>{{ p.title }}</a></li>
{% endfor %}
</ul>