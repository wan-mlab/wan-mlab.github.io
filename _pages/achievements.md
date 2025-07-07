---
title: "Wan Lab - Achievements"
layout: textlay
sitemap: false
permalink: /achievements/
---

# Achievements of Lab Trainees

<p>This page highlights awards, scholarships, poster presentations, and recognitions received by current and former lab trainees, as reported in lab news. Achievements are grouped by individual.</p>

{% assign trainee_names = "Lusheng, Hanyu, Mengtao, Xinchao, Nick, Nicholas, Cece, Xuehuan, Grace, Jiaqi, Ouyang, Anulika, Sili, Xingmin, Junxi, Cong, Yijin, Wenhao, Simar, Eswar, Weiqi, Saiyi, Neil, Navya, Min-jeong, Charlie, Kah Meng, Bryant, Ramos, Raheem, Richard, Yanan, Andy" | split: ", " %}
{% assign achievements_by_person = {} %}

{% for article in site.data.news %}
  {% assign headline_lc = article.headline | downcase %}
  {% unless headline_lc contains 'shibiao' %}
    {% for name in trainee_names %}
      {% assign name_lc = name | downcase %}
      {% if headline_lc contains name_lc %}
        {% assign person = name %}
        {% assign achievements = achievements_by_person[person] | default: "" %}
        {% assign new_achievement = "<li>" | append: article.date | append: ": " | append: article.headline | append: "</li>" %}
        {% assign achievements = achievements | append: new_achievement %}
        {% assign achievements_by_person = achievements_by_person | merge: {{ person | jsonify }}: achievements %}
      {% endif %}
    {% endfor %}
  {% endunless %}
{% endfor %}

{% for name in trainee_names %}
  {% assign achievements = achievements_by_person[name] %}
  {% if achievements %}
  <h3>{{ name }}</h3>
  <ul>
    {{ achievements | raw }}
  </ul>
  {% endif %}
{% endfor %} 