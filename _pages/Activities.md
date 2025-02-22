---
title: "Research Team"
permalink: /Activities/
layout: single
classes: wide
---

{% assign team = site.data.team %}

## Team Leader

<div class="profile">
  <div class="profile__content">
    <div class="profile__avatar">
      {% include figure image_path="/assets/images/authors/Run-Zi Wang.jpg" alt="Run-Zi Wang" %}
    </div>
    <div class="profile__details">
      ### Run-Zi Wang
      **Tohoku University (Assistant Professor)**  
      Active lifetime design by integrating modelling-driven material strength with knowledge-reinforced structural integrity, enhancing creep-fatigue resistance and reliability towards carbon neutrality.

      <div class="social-icons">
        <a href="https://www.crc-ms.tohoku.ac.jp/en/result/newresearcher/runzi_index.html" target="_blank" rel="noopener noreferrer">
          <i class="fas fa-link"></i> Homepage
        </a>
        <a href="https://scholar.google.com/citations?user=gZ5NubYAAAAJ&hl" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-google"></i> Google Scholar
        </a>
        <a href="https://researchmap.jp/rzwang" target="_blank" rel="noopener noreferrer">
          <i class="fas fa-link"></i> ResearchMap
        </a>
        <a href="mailto:runzi.wang.a7@tohoku.ac.jp">
          <i class="fas fa-envelope"></i> Email
        </a>
      </div>
    </div>
  </div>
</div>

## Collaborative Researchers

{% for member in site.data.collaborators %}
<div class="profile">
  <div class="profile__content">
    <div class="profile__avatar">
      {% include figure image_path=member.avatar alt=member.name %}
    </div>
    <div class="profile__details">
      ### {{ member.name }}
      **{{ member.position }}**  
      {{ member.bio }}

      <div class="social-icons">
        {% for link in member.links %}
        <a href="{{ link.url }}" {% if link.external %}target="_blank" rel="noopener noreferrer"{% endif %}>
          <i class="{{ link.icon }}"></i> {{ link.label }}
        </a>
        {% endfor %}
      </div>
    </div>
  </div>
</div>
{% endfor %}