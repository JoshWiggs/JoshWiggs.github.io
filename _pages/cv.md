---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2018- **PhD. Physics**, Plasma Transport at Jupiter, _Lancaster University, Bailrigg_.
* 2013-17 **Master of Physics (Hons) Physics with Astrophysics**, _Northumbria University, Newcastle Upon Tyne. First Class._
* -2013 **UK educated up to A levels**, Specialising in Physics, Maths and IT, _Lincoln, UK_

Professional Roles
* 2022- **Scientific Software Engineer**, _Met Office, Exeter_
  Responsibilities include the provision of operational quality Linux server stacks and the deployment of post-processing applications & pipelines into these environments. Additionally, I support the development of a range of these applications & pipelines (mostly in Python & Bash) as well as providing technical & scientific advise to other members of these teams.  

* 2017-18 **Ecommerce Manager**, _UrbanMoto Ltd, Lincoln_

  I was responsible for the development and operation of ecommerce activities across all platforms. This was achieved by leading and coordinating ecommerce development projects with both internal and external agencies, ensuring the general health of all ecommerce related systems and the management of staff who operate these systems. I successfully launched new product lines, redeveloped existing ecommerce platforms and integrated new systems into the existing ecosystem to improve staff productivity, sales revenue and customer satisfaction.

Research Projects
======
<ul>{% for post in site.projects %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Personal and Technical Skills
======
* **Programming**: Python, C++, Bash, IDL, MATLAB, Javascript, CSS3 and HTML5.
* **Libraries**: Numpy, Matplotlib, Pandas, Xarray, Iris, Scipy, Eigen3, Ceral
* **Software**: LaTeX, MPI, Cylc, Simulink, Microsoft Office Suite and Adobe Creative Suite.
* **General Skills and Attributes**: Work well independently and as part of a team, strong mathematical skills, good oral and written communication skills, scientific report production, excellent time management and organisational skills, good interpersonal skills, experienced presenter to a range of audiences.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Presentations
======
<ul>{% for post in site.talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
