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
        <th>时间</th>
        <th>机构</th>
        <th>院系</th>
        <th>职位</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2025.06-Present</td>
        <td><a href="https://www.jxufe.edu.cn" target="_blank" rel="noopener">Jiangxi University of Finance and Economics</a></td>
        <td>School of Information Management and Mathematics</td>
        <td>Lecturer</td>
      </tr>
    </tbody>
  </table>
</div>
<div class="table-wrapper-cv-education">
  <table>
    <thead>
      <tr>
        <th>时间</th>
        <th>毕业院校</th>
        <th>专业</th>
        <th>导师</th>
        <th>学位</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>2021.09-2024.12</td>
        <td><a href="https://www.ncu.edu.cn" target="_blank" rel="noopener">Nanchang University</a></td>
        <td>Information Management and Information Systems</td>
        <td><a href="https://smcs.ncu.edu.cn/szdw/jsml/2e0cf032bb4c475c8f0767ecd4800043.htm" target="_blank" rel="noopener">Prof. Weidong Min</a></td>
        <td>Ph.D.</td>
      </tr>
      <tr>
        <td>2018.09-2021.06</td>
        <td>Nanchang University</td>
        <td>Computer Science and Technology</td>
        <td>Prof. Weidong Min</td>
        <td>M.E.</td>
      </tr>
      <tr>
        <td>2014.09-2018.06</td>
        <td>Nanchang University</td>
        <td>Computer Science and Technology</td>
        <td>N/A</td>
        <td>B.E.</td>
      </tr>
    </tbody>
  </table>
</div>


发表物
------

（* 表示通讯作者,<sup>#</sup> 表示共同第一作者。）

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

访谈
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
