---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

工作与教育经历
------

<div class="table-wrapper-about-work-experience">
  <table>
    <thead>
      <tr>
        <th>起止年月</th>
        <th>工作单位</th>
        <th>部门</th>
        <th>职位</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2025-06至今</td>
        <td><a href="https://www.jxufe.edu.cn" target="_blank" rel="noopener">江西财经大学</a></td>
        <td>信息管理与数学学院</td>
        <td>讲师</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="table-wrapper-cv-education">
  <table>
    <thead>
      <tr>
        <th>起止年月</th>
        <th>毕业高校</th>
        <th>专业</th>
        <th>师从导师</th>
        <th>学位</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2021-09至2024-12</td>
        <td><a href="https://www.ncu.edu.cn" target="_blank" rel="noopener">南昌大学</a></td>
        <td>信息管理与信息系统</td>
        <td><a href="https://smcs.ncu.edu.cn/szdw/jsml/2e0cf032bb4c475c8f0767ecd4800043.htm" target="_blank" rel="noopener">闵卫东教授</a>（国家级人才）</td>
        <td>工学博士</td>
      </tr>
      <tr>
        <td>2018-09至2021-06</td>
        <td>南昌大学</td>
        <td>计算机科学与技术</td>
        <td>闵卫东教授</td>
        <td>工学硕士</td>
      </tr>
      <tr>
        <td>2014-09至2018-06</td>
        <td>南昌大学</td>
        <td>计算机科学与技术</td>
        <td>无</td>
        <td>工学学士</td>
      </tr>
    </tbody>
  </table>
</div>


论文等
------

（* 表示通讯作者,<sup>#</sup> 表示共同第一作者。）

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

学术交流
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

教学
------
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
## 服务与领导力
