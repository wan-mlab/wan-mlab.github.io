---
title: "Wan Lab - Achievements"
layout: textlay
sitemap: false
permalink: /achievements/
---

# Achievements of Lab Trainees
<br>
#### This page highlights the outstanding accomplishments of trainees at the Wan Lab, including publications, awards and scholarships!

---

## Graduate Students

### Mengtao Sun
- #### Highlights:
  - UNMC graduate fellowship (2025)
- #### Publications:
  - **Journal Articles**
{% for person in "M. Sun" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "M. Sun" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### Lusheng Li
- #### Publications:
  - **Journal Articles**
{% for person in "L. Li" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "L. Li" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### Xinchao Wu
- #### Publications:
  - **Journal Articles**
{% for person in "X. Wu" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "X. Wu" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### Nicholas Peterson
- #### Publications:
  - **Journal Articles**
{% for person in "N. Peterson" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "N. Peterson" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### Min-jeong Baek
- #### Publications:
  - **Journal Articles**
{% for person in "M. Baek" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "M. Baek" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

## Intern Students

### Cece Zhang
- #### Publications:
  - **Journal Articles**
{% for person in "C. Zhang" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "C. Zhang" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

---

### Xuehuan Zhu
- #### Publications:
  - **Journal Articles**
{% for person in "X. Zhu" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

  - **Conference Abstracts**
{% for person in "X. Zhu" %}
  {% assign found = false %}
  {% assign person_lc = person | downcase %}
  {% capture pubs %}
    {% for publi in site.data.publist_Abstracts %}
      {% assign authors_lc = publi.authors | downcase %}
      {% if authors_lc contains person_lc %}
        {% assign found = true %}
        <li>
          <strong>{{ publi.title | remove_first: '1. '}}</strong><br />
          <em>{{ publi.authors }}</em><br />
          <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
        </li>
      {% endif %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <ul>
      {{ pubs | strip }}
    </ul>
  {% endif %}
{% endfor %}

