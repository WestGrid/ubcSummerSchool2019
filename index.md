---
layout: default
---

{% include figure.html file="allLogos.png" alt="intro image here" width="95%" %}

# Research computing summer school

## Monday June 24<sup>th</sup> to Thursday June 27<sup>th</sup>, 2019

<!-- This June, [WestGrid](https://www.westgrid.ca) is bringing its four-day Research Computing Summer School -->
<!-- to the University of British Columbia. -->

Back by popular demand, the 3rd Annual Research Computing Summer School, co-hosted by <a
href="https://www.westgrid.ca" target="_blank">WestGrid</a> and the University of British Columbia, is
taking place from June 24<sup>th</sup> to 27<sup>th</sup>, 2019 at UBC Vancouver campus. Courses will
explore introductory and advanced topics in high performance computing and parallel programming, machine
learning, research computing with Python / MATLAB / Chapel, next-generation sequencing, using databases
on Compute Canada clusters, and scientific visualization. The Summer School is open to anyone with an
interest in these areas.

For full course details, please check [the program]({{ site.baseurl }}/1-program.html). We encourage
anyone interested in building knowledge and skills for computational research to attend the
school. Researchers in all disciplines and skill levels are welcome to register.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | prepend: site.url }}){% endif %}
{% endfor %}
</div>
