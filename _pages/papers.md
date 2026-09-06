---
permalink: /papers/
title: "Publications"
excerpt: ""
author_profile: true
---

<span class='anchor' id='papers-index'></span>
<h2 class="section-title">📝 Publications</h2>
<p style="margin-top:-0.35rem; margin-bottom:1.2rem; color:#64748b; font-size:0.92rem;">First-author and co-first-author papers. Click any title for details, abstract, and BibTeX.</p>

<div class="papers-index">
  {% for p in site.papers %}
    <a class="pi-card" href="{{ p.url | relative_url }}">
      <div class="pi-main">
        {% if p.venue %}<span class="pi-badge">{{ p.venue }}{% if p.venue_note %} · {{ p.venue_note }}{% endif %}</span>{% endif %}
        <div class="pi-title">{{ p.title }}</div>
        <div class="pi-authors">
          {% for a in p.authors %}
            <span class="{% if a.note == 'first' or a.note == 'co-first' %}pi-me{% endif %}">{{ a.name }}{% if a.note == 'first' or a.note == 'co-first' %}*{% endif %}</span>{% unless forloop.last %}, {% endunless %}
          {% endfor %}
        </div>
        {% if p.tldr %}<div class="pi-tldr">{{ p.tldr }}</div>{% endif %}
      </div>
      {% if p.image %}<div class="pi-thumb"><img src="{{ p.image | relative_url }}" alt="{{ p.title }}" /></div>{% endif %}
    </a>
  {% endfor %}
</div>

<style>
  .papers-index { display: flex; flex-direction: column; gap: 1rem; }
  .pi-card { display: flex; gap: 1.2rem; align-items: center; padding: 1.1rem 1.3rem; border: 1px solid #e2e8f0; border-radius: 14px; background: #fff; text-decoration: none; transition: box-shadow 0.18s, transform 0.18s, border-color 0.18s; }
  .pi-card:hover { box-shadow: 0 8px 28px rgba(15,23,42,0.10); transform: translateY(-2px); border-color: #c7d2fe; }
  .pi-main { flex: 1 1 auto; min-width: 0; }
  .pi-badge { display: inline-block; padding: 0.18rem 0.6rem; border-radius: 999px; background: #eef2ff; color: #4f46e5; font-weight: 700; font-size: 0.76rem; margin-bottom: 0.5rem; }
  .pi-title { font-size: 1.02rem; font-weight: 700; color: #0f172a; line-height: 1.4; }
  .pi-authors { margin-top: 0.4rem; font-size: 0.86rem; color: #64748b; line-height: 1.5; }
  .pi-me { color: #1d4ed8; font-weight: 700; }
  .pi-tldr { margin-top: 0.5rem; font-size: 0.84rem; color: #475569; line-height: 1.5; }
  .pi-thumb { flex: 0 0 auto; width: 130px; }
  .pi-thumb img { width: 100%; border-radius: 8px; display: block; }
  @media (max-width: 640px) { .pi-thumb { display: none; } }
</style>
