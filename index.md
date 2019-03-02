---
layout: default
---

{% include figure.html file="allLogos.png" alt="intro image here" width="95%" %}

# Research computing summer school

## Monday June 24th to Thursday June 27th, 2019

This June, [WestGrid](https://www.westgrid.ca) is bringing its four-day Research Computing Summer School
to the University of British Columbia. Courses will explore introductory and advanced topics in high
performance computing and parallel programming, machine leaning, research computing with Python / R /
MATLAB / C / C++ / Chapel, and scientific visualization.

For full course details, please check [the program]({{ site.baseurl }}/1-program.html). We encourage
anyone interested in building knowledge and skills for computational research to attend the
school. Researchers in all disciplines and skill levels are welcome to register.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>
