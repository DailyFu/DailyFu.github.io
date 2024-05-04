  
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育经历
======
* 青岛大学, 经济学学士,2018
* 南京审计大学，统计学硕士,2021
* 南京大学,理论经济学,2021.9 至今
  
专业技能
======
* DSGE 宏观经济建模
* 应用计量分析
  * 面板数据分析
  * 时间序列（应用宏观）
  * 机器学习经典算法（基本）
* 计算机语言:
  * Python(熟练),R(熟练)
* 掌握的软件:
  * MATLAB,R,Jupyter,Stata,SPSS,SAS,Mathematica,\LATEX

研究
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
会议与演讲
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

