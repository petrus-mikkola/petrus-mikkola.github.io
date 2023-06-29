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
* Doctor of Science (Machine Learning), Aalto University, Machine Learning, 2019 – 2023 (expected)
* Master of Science (Mathematics/Stochastics), University of Helsinki, 2016 – 2020, GPA: 4.8/5
* Master of Social Sciences (Economics), University of Helsinki, 2015 – 2018, GPA: 4.7/5
* Bachelor of Social Sciences (Economics), University of Helsinki, 2013 – 2015, GPA: 4.9/5

Research
======
My research focuses on probabilistic methods for human-in-the-loop machine learning and multi-information source optimization.<br> 
<u>Research topics</u>: Bayesian optimization, elicitation (knowledge elicitation, prior elicitation, and preference learning), human-AI teaming<br>

Publications
======
  {% include_relative publications.md %}

  {% capture my_include %}{% include publications.md %}{% endcapture %}
{{ my_include | markdownify }}
  
# Talks
# ======
#  <ul>{% for post in site.talks %}
#    {% include archive-single-talk-cv.html %}
#  {% endfor %}</ul>
  
Teaching
======
 {% include_relative teaching.md %}

Community involvement
======
I have acted as a reviewer for IEEE TPAMI and AISTATS (awarded top-10% reviewer in 2023).
  

