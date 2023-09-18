---
layout: page
title: Priority Queues
description: 
img: assets/img/12.jpg
importance: 5
category: Data Structures
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