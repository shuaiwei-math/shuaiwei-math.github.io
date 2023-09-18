---
layout: page
title: project 5
description: priority queue
img: assets/img/1.jpg
importance: 3
category: ds
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/prioq.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}