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
  * MPI/OpenMP (advanced)
  * Python (advanced)
  * Julia, serial & parallel (advanced)
  * Maltab (intermediate)
  * Git & CI/CD (advanced)
  * Linux/UNIX (advanced)
  * High Performance Computing (expert)
  * Cloud Computing (advanced)
* Languages
  * English (fluent)
  * French (fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  * PRCR 2023 (Pacific Rim Conference in Rheology), Vancouver, Canada, May 2023.
  * SCAIM seminar (Scientific Computing for Applied Industrial Mathematics), Vancouver, Canada, March 2023.
  * Mathematical Modeling and Computational Physics, Vancouver, Canada, February 2023.
  * Basilisk Monthly Meeting, Sorbonne Université, Paris, France, December 2022.
  * IUTAM Symposium 2022, Toulouse, France, August 2022.
  * APS Division of Fluid Dynamics annual meeting, Seattle, WA, November 2019.
  * Fluid Seminars Series, Vancouver, Canada, August 2019.

Awards
======
  {% for post in site.awards reversed %}
* **{{post.title}}** -- {{post.description}}.
  {% endfor %}


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
  * Organize the annual IAM Retreat: a one-day event where 90+ student and faculty IAM members share their research and build community.

* President of Physics club  
  * Co-founded and led a student Physics club (20+ members)
  * Organized conferences with world class speakers (e.g. Cédric Villani, laurate of the Fields Medal) and science popularization events for underprivileged children.
