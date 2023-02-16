---
title: Home
---

# The Second Conference on System and Service Quality - QualIta, 19-20  June 2023, Florence, Italy.

*Supported by the CINI WG on SSQ.*
  
{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}

## Overview

The second Italian Conference on System and Service Quality (QualIta 2023) is the annual event of the CINI System and Service Quality Working Group. Its main goal is to put together Italian researchers, practitioners and professionals from academia, industry and public administration interested in qualities of computing systems such as performance, dependability, trustworthiness, efficiency, resilience, sustainability, and others. The conference will be structured into different research tracks, selected keynote speeches and some panels on related topics.
QualIta 2023  (QI23) aims to highlight quality aspects, considering the complex, heterogeneous, multidisciplinary environment in which modern computing systems operate, together with their application domains, characterized by an increasing demand of resilient and sustainable solutions that should also meet efficiency as well as time-constrained requirements. 
Technologies such as Cloud computing, IoT, 5G networks, Big Data and AI have started becoming mature enough, turning the peak of inflated expectations and disillusionment towards effective solutions into enlightenment. To move further towards the plateau of productivity, the focus switches from functional to non-functional aspects, from mechanisms to qualities and policies for their enforcement, and from a proof of concept or prototype to a product or service. Therefore, techniques and tools to deal with quality aspects in the design, implementation and assessment of computing systems become essential to support such process. QI23 will explore methodological and practical aspects of qualities, ranging from modelling and design techniques to evaluation tools and case studies. It will also investigate related domains such as cloud, edge, IoT, intelligent systems, cyber-physical systems, high-performance computing, blockchain, and similar.

## Call for Contributions

[List of open calls](https://qualitawg.github.io/0-Calls.html)

## Organizers

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by University of Florence,  within the 37th International Conference on Modelling and Simulation, [ECMS23](https://scs-europe.net/conf/ecms2023/).
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
