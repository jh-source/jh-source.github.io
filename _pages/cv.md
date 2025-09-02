---
layout: none
title: CV
permalink: /cv/
description: Curriculum Vitae of Jinhao Liang
nav: true
nav_order: 3
cv_pdf: CV_Jinhao.pdf
---

{% assign pdf_path = page.cv_pdf | prepend: 'assets/pdf/' | relative_url %}

<meta http-equiv="refresh" content="0; url={{ pdf_path }}">
<script>location.replace('{{ pdf_path }}');</script>
<!-- <p>正在跳转到简历 PDF，如未自动跳转，请<a href="{{ pdf_path }}">点击这里</a>。</p> -->
