---
layout: photolist
title: Teaching & Supervising
menu: yes
order: 3
---

## <span style="color:darkblue"> Students & Interns </span>
I supervise undergraduate/master students in the scope of
[Yandex Academic Supervision Program](https://yandex.ru/jobs/vacancies/research/scientific_leadership_prog/), 
and NLP research interns at [Yandex Research]({{site.yandex_research_main}}).



The team:
* Dmitriy Emelyanenko, <span style="color:gray">2019-current </span>
* Ivan Provilkov, <span style="color:gray">2019-current </span>
* Maksim Ryabinin, <span style="color:gray">2019-current </span>
* __you?__ Apply [here](https://yandex.com/jobs/vacancies/research/intern_researcher_eng) <span style="color:red"> UPD: currently I'm not taking any new students </span>

<span style="color:gray;font-size:0.9em">Past members: Fedor Moiseev (BS; afterwards MS at EPFL)</span>

## <span style="color:darkblue"> Courses </span>
{% assign courses = (site.data.courses | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}

