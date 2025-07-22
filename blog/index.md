---
layout: page
title: 知識專欄｜永續與能源管理實務
permalink: /blog/
description: 台灣智綠分享淨零建築、能源管理、碳盤查、IFRS S1/S2、NILM 與智慧製造等專業觀點與案例解析。
keywords: 淨零建築,能源管理,ISO 50001,碳盤查,NILM,IFRS S1,SBTi,智慧製造
---

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span>（{{ post.date | date: "%Y-%m-%d" }}）</span><br/>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>
