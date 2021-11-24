---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
{% assign sorted_degrees = site.data.education | sort: "start_date" | reverse %}
{% for degree in sorted_degrees %}
  {% include education-item-cv.md %}
{% endfor %}

Work experience
======
{% assign sorted_jobs = site.data.jobs | sort: "start_date" | reverse %}
{% for job in sorted_jobs %}
  {% include job-item-cv.md %}
{% endfor %}

Skills
======
* Programming
  * C/C++ (expert)
  * Python (expert)
  * MPI/OpenMP (expert)
  * Maltab (expert)
  * Git (expert)
  * Linux/UNIX (confirmed)
* Languages
  * English (fluent)
  * French (fluent)
  * Spanish (notions)

A work day of my life
======
<img src="/images/workday.png" alt="Diagram of a typical workday of my life" width="60%"/>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed%}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
* Mathematics instructor, Fall 2020
  * Teaching a diﬀerential calculus course to 145 ﬁrst year university students.
  * Implementation of several active learning techniques: flipped classroom environment, problem solving group sessions, continuous feedback.

* Graduate teaching assistant in mathematics, 2019 -- persent
  * Leading workshops for first-year students. Topic: differential calculus.
  * Leading MATLAB computer labs for second-year engineering students. Topic: solutions to systems of Ordinary Differential Equations (ODEs)
  * Grading and giving office hours to various first- and second-year courses. Topics include: linear algebra, differential calculus, laplace transforms, etc.

Service and leadership
======
* Active member of the student committee of the [Institute of Applied Mathematics](https://www.iam.ubc.ca/)  
  * Foster sense of community among students conducting interdisciplinary research related to mathematics.
  * Organize workshops by and for IAM students
  * Organize the annual IAM Retreat: a one-day event where 50+ student and faculty IAM members share their research and build community.

* President of Physics club  
  * Co-founded and led a student Physics club (20+ members)
  * Organized conferences with world class speakers (e.g. Cédric Villani, laurate of the Fields Medal) and science popularization events for underprivileged children.
