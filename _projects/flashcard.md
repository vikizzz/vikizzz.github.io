---
layout: page
title: Flashcard
description:  simple python project that was inspired by Quizlet
img: assets/img/flashcard.jpeg
importance: 1
date: 2021-06-06 11:01:00 +0800
category: Fun
github: https://github.com/vikizzz/Flashcard
---
{::nomarkdown}
{% assign jupyter_path = "assets/quarto/flashcard.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/quarto/flashcard.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}