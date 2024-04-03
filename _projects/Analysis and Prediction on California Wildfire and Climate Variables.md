---
layout: page
title: Analysis and Prediction on California Wildfire and Climate Variables
description: 
img: assets/img/wildfire.jpeg
importance: 3
date: 2021-02-26 11:01:00 +0800
category: Project
github: https://github.com/vikizzz/Analysis-on-the-Scale-of-Wildfire-Incident-in-California
---

{::nomarkdown}
{% assign jupyter_path = "assets/quarto/wildfire.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/quarto/wildfire.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}