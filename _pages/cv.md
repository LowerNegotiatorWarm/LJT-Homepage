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
* Ph.D. in Computer Science (2024–Present), Hong Kong University of Science and Technology
* B.Eng. (2020–2024), Shanghai Jiao Tong University

Research Experience
======
* Research Intern, MINIMAX (February 2025–Present)
* Research Intern, Tencent WXG (June 2024–September 2024)
* Research Intern, Shanghai AI Lab (June 2023–December 2023)

Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Research Interests
======
* Natural Language Processing and Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Publications
======
  &lt;ul&gt;{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}&lt;/ul&gt;
  
Talks
======
  &lt;ul&gt;{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}&lt;/ul&gt;
  
Teaching
======
  &lt;ul&gt;{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}&lt;/ul&gt;
