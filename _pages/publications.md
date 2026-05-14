---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 1
---

<div class="pub-header">
  <p>
    My research has been published at top-tier NLP and IR venues including <strong>ACL, EMNLP, NAACL, AAAI, SIGIR, CIKM, WWW</strong>, and <strong>ECIR</strong>.
    See my <a href="https://scholar.google.com/citations?user=nFmvLQgAAAAJ&hl=en" target="_blank">Google Scholar</a> profile for the full citation record.
  </p>
  <div class="pub-stats">
    <span><i class="fas fa-quote-right"></i>&nbsp; 1,000+ citations</span>
    <span><i class="fas fa-chart-bar"></i>&nbsp; h-index: 16</span>
    <span><i class="fas fa-list-ol"></i>&nbsp; i10-index: 22</span>
  </div>
  <p class="pub-note"><sup>*</sup> denotes equal contribution.</p>
</div>

<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} %}
</div>
