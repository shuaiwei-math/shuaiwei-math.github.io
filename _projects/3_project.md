---
layout: page
title: Trees and Graphs
description: 
img: assets/img/3.jpg
importance: 3
category: Data Structures
giscus_comments: true
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/treegr.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}