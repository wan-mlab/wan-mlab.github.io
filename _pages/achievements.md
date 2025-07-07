---
title: "Wan Lab - Achievements"
layout: textlay
sitemap: false
permalink: /achievements/
---

# Achievements of Lab Trainees

<p>This page highlights awards, scholarships, poster presentations, and recognitions received by current and former lab trainees, as reported in lab news.</p>

{% assign trainee_keywords = "award,scholarship,poster,present,congratulations,defend,accepted,selected,recipient,recognition,first place,successfully" | split: "," %}
{% for article in site.data.news %}
  {% assign headline_lc = article.headline | downcase %}
  {% assign is_trainee = false %}
  {% for kw in trainee_keywords %}
    {% if headline_lc contains kw %}
      {% unless headline_lc contains 'shibiao' %}
        {% assign is_trainee = true %}
      {% endunless %}
    {% endif %}
  {% endfor %}
  {% if is_trainee %}
    <p><b>{{ article.date }}</b><br>
    <em>{{ article.headline | markdownify }}</em></p>
  {% endif %}
{% endfor %} 