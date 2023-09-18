---
layout: page
title: Regular Sequences and Polarization
description: 
img: assets/img/3.jpg
redirect: ../assets/pdf/cc_proj1.pdf
importance: 1
category: Commutative Algebra
related_publications: 
# related_publications: wei:s, wei:sd

---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/sort.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}