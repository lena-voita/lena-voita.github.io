---
layout: photolist
title: Teaching & Supervising
description: Information about the students I supervised and the courses I teach. 
menu: no
order: 4
---

## <span style="color:darkblue"> Students & Interns </span>
While working at Yandex Research, I supervised undergraduate/master students in the scope of
[Yandex Academic Supervision Program](https://yandex.ru/jobs/vacancies/research/scientific_leadership_prog/), 
and NLP research interns at [Yandex Research]({{site.yandex_research_main}}).


The team:
* Dmitrii Emelianenko: [NeurIPS 2019](https://arxiv.org/abs/1911.00176), [ACL 2020 (BPE-dropout)](https://arxiv.org/abs/1910.13267)
* Ivan Provilkov: [ACL 2020 (BPE-dropout)](https://arxiv.org/abs/1910.13267)
* Maksim Ryabinin: a very cool paper which will be here soon :)
* Fedor Moiseev: [ACL 2019 paper](https://www.aclweb.org/anthology/P19-1580/)



## <span style="color:darkblue"> Courses </span>
{% assign courses = (site.data.courses | where: "selected", "y") %}
{% for course in courses %}
{% include course.html course=course %}
{% endfor %}

