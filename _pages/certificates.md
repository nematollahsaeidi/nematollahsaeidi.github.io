---
layout: page
permalink: /certificates/
title: certificates
description: Courses, schools and professional training.
nav: true
nav_order: 4
---

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:1.5rem;">
{% for c in site.data.certificates %}
  <div style="border:1px solid var(--global-divider-color,#ddd);border-radius:8px;overflow:hidden;">
    {% if c.url %}<a href="{{ c.url }}" target="_blank" rel="noopener">{% endif %}
    <img src="{{ c.image | relative_url }}" alt="{{ c.name }}" style="width:100%;height:180px;object-fit:cover;" onerror="this.style.display='none'">
    {% if c.url %}</a>{% endif %}
    <div style="padding:0.75rem 1rem;">
      <strong>{{ c.name }}</strong><br>
      {{ c.issuer }}<br>
      <small>Issued {{ c.date }}{% if c.credential_id %} &middot; ID {{ c.credential_id }}{% endif %}</small>
      {% if c.url %}<br><small><a href="{{ c.url }}" target="_blank" rel="noopener">Show credential</a></small>{% endif %}
    </div>
  </div>
{% endfor %}
</div>
