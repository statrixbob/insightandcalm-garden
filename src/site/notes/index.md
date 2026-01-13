---
{"dg-publish":true,"permalink":"/index-md/","title":"Insight & Calm","tags":["gardenEntry"]}
---

{% set notes = collections.notes | reverse %}
<ul>
  {% for note in notes %}
    <li><a href="{{ note.url }}">{{ note.data.title }}</a></li>
  {% endfor %}
</ul>

