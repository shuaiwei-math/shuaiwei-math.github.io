---
layout: page
title: project 6
description: binary trees
img:
importance: 6
category: ds
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/binat.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/blog.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}