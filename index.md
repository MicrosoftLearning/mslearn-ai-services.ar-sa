---
title: تمارين خدمات الذكاء الاصطناعي في Azure
permalink: index.html
layout: home
---

# تمارين خدمات الذكاء الاصطناعي في Azure

تم تصميم التدريبات التالية لدعم الوحدات النمطية على Microsoft Learn.


{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Exercises'" %} {% for activity in labs  %} {% unless activity.url contains 'ai-foundry' %}
- [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) {% endunless %} {% endfor %}
