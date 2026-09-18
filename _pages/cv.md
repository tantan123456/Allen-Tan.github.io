---
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

* **【起止年月】**　桂林电子科技大学，【专业】，博士研究生
* **【起止年月】**　【学校名称】，【专业】，【学位】

科研经历
======

* **【起止年月】**　【课题组 / 实验室】，【角色，如：博士研究生】
  * 主要工作：【一句话描述，例如：负责 XX 系统的算法设计与实验验证】
  * 指导老师：【导师姓名】

* **【起止年月】**　【课题组 / 实验室】，【角色，如：研究助理】
  * 主要工作：【一句话描述】

专业技能
======

* 编程：【Python、MATLAB、C++ …】
* 工具与平台：【PyTorch、Git、LaTeX、Linux …】
* 语言：中文（母语）、英语（【CET-6 / 雅思 X.X】）

论文
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

学术报告
======

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

教学
======

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

荣誉与奖励
======

* **【年月】**　【奖项名称，如：研究生学业奖学金一等奖】
* **【年月】**　【竞赛 / 荣誉】
