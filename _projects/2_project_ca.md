---
layout: page
title: project 2
description: sort
img: assets/img/12.jpg
# redirect: ../
importance: 2
category: cc
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