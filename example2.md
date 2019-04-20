---
layout: photolist
title: ExamplePage2
menu: yes
---

You can also use yml data files using a simple scripting language. See the source at ./example2.md

See ./_data/example.yml for how yml files looks like, ./_includes/person.html for how to make templates.

{% assign people = (site.data.example | where: "selected", "y") %}
{% for person in people %}
{% include person.html person=person %}
{% endfor %}