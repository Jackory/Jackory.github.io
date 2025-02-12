---
layout: page
permalink: /more/
title: Details
description: Some information about me
years: [2022, 2023, 2024, 2025]
nav: true
---
<!-- _pages/more.md -->
<br>
## Education

##### Nanjing University

- Major in Automation
- 2018.9 - 2022.09

##### Tsinghua University
- PhD in Department of Automation
- 2022.9 - Presents

<br>
<br>
## Adwards
- 2021.10 Hengfang Scholarship
- 2020.10 National Scholarship 

<br>
<br>
## Publications
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>



