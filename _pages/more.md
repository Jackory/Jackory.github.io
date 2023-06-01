---
layout: page
permalink: /more/
title: More
description: Some information about me
years: [2022, 2023]
nav: true
---
<!-- _pages/more.md -->
<br>
## Education

##### Nanjing University

- School of Management and Engineering
- Major in Automation
- 2018.9 - Now

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



