---
title: "Wan Lab - Achievements"
layout: textlay
sitemap: false
permalink: /achievements/
---

# Achievements of Lab Trainees
<br>
#### This page highlights the outstanding accomplishments of trainees at the Wan Lab, including publications, presentations, awards and scholarships!

---

## Graduate Students

### Mengtao Sun
- **Highlights**:
  - Presented at Wan Lab Meeting (Aug 22, 2025)
  - Contributed key methods to antimicrobial prediction model
- **Publications**:

{% for person in "M. Sun" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          {% assign clean_title = publi.title | remove_first: '1. ' %}
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <h3>{{ person }}</h3>
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### **Xinchao Wu**
