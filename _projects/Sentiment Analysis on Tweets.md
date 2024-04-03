---
layout: page
title: Sentiment Analysis on Tweets
description:  This project is inspired and led by "How to analyze the sentiment of your own Tweets" by Jessica Garson
img: assets/img/Sentiment-analysis-of-Twitter-Social.png
importance: 2
date: 2021-08-16 11:01:00 +0800
category: Project
---

{::nomarkdown}
{% assign jupyter_path = "assets/quarto/Search_Tweets.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/quarto/Search_Tweets.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}