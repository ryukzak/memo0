---
layout: default
---
## Bio

Most of the time, I mix research (analysis, representation, and experiment), development (programming and management), and teaching (lectures, consulting, and mentoring) in the area of computer engineering. My bio's most important milestones are developing the electricity measuring system for small towns with certification, the Ph.D. thesis about multi-level computer systems organization, and CAD for application-specific processors.

Current research and development topics:

- Computer and Cyber-Physical Systems Design
- Computational Process Organization, Tools
- Quality Software Management
- Verification of Software Systems
- Application-Specific Instruction Set Processor (ASIP)
- Theory and Practice of Functional Programming

<!-- Third Person Bio: Aleksandr Penskoi, Ph.D., is working as Associate Professor at Software Engineering and Computer Systems Faculty at ITMO University with a specialization in computational process modeling and computer system design. The primal research topics are multi-level computer systems, hard real-time reconfigurable application-specific processors (NITTA), and verification. He has experience in real-world development as an architect and software engineer, e.g., electricity measuring system for small towns with certification. -->

---

Большую часть времени я совмещаю исследования (анализ и эксперименты), разработку (программирование и организацию работ) и преподавание (чтение курсов, консультации и дипломники) в области компьютерной инженерии. Моими наиболее важными результатами являются система измерения потребления электроэнергии в многоквартирных домах (включая сертификацию); кандидатская диссертация о том, что такое многоуровневые системы; и САПР для специализированных вычислителей (текущий проект).

Текущая область интересов:

- Проектирование компьютерных и киберфизических систем.
- Организация вычислительного процесса, инструментальные средства.
- Управление качеством программного обеспечения.
- Верификация программных систем.
- Проблемно-ориентированные процессора (ASIP).
- Теория и практика функционального программирования.

## Projects / Проекты

<ul>
{% assign sorted = site.projects | sort: 'title'  %}
{% for post in sorted %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}
    <br/>
    <small> {{ post.description }} </small></a>
  </li>
{% endfor %}
</ul>

## Courses / Курсы

<ul>
{% assign sorted = site.courses | sort: 'title'  %}
{% for post in sorted %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}
    <br/>
    <small>{{post.description}}</small></a>
  </li>
{% endfor %}
</ul>

## Blog / Блог

<ul>
{% assign sorted = site.posts | sort: 'date' | reverse  %}
{% for post in sorted %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}
    <br/>
    <small><tt> // {{ post.date | date_to_long_string }}</tt></small> </a>
  </li>
{% endfor %}
</ul>

## Social / Контакты

- GitHub: [ryukzak](https://github.com/ryukzak)
- Twitter: [@ryukzak](https://twitter.com/ryukzak)
- Telegram: [@aleksandr_penskoi](https://t.me/aleksandr_penskoi)
- LinkedIn: [Aleksandr Penskoi](https://www.linkedin.com/in/aleksandr-penskoi/)
