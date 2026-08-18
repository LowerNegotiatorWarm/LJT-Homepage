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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–Present
* B.Eng., Shanghai Jiao Tong University, 2020–2024

Research Experience
======
* Research Intern, MINIMAX, Feb 2025–Present
* Research Intern, Tencent WXG, Jun 2024–Sep 2024
* Research Intern, Shanghai AI Lab, Jun 2023–Dec 2024

Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University, 2024

Research Interests
======
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability
* Natural Language Processing and Machine Learning

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
  
Service and leadership
======
* Active contributor to open-source NLP research
