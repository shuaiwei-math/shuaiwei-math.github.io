---
layout: page
title: project 4
description: grap plotting and spanning tress
img:
importance: 4
category: Data Structures
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/gpst.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}