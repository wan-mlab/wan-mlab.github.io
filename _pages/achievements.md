---
title: "Wan Lab - Achievements"
layout: textlay
sitemap: false
permalink: /achievements/
---

# Achievements of Lab Trainees

<p>This page highlights awards, scholarships, poster presentations, and recognitions received by current and former lab trainees, as reported in lab news. Achievements are grouped by individual.</p>

{% assign trainee_names = "Lusheng, Hanyu, Mengtao, Xinchao, Nick, Nicholas, Cece, Xuehuan, Grace, Jiaqi, Ouyang, Anulika, Sili, Xingmin, Junxi, Cong, Yijin, Wenhao, Simar, Eswar, Weiqi, Saiyi, Neil, Navya, Min-jeong, Charlie, Kah Meng, Bryant, Ramos, Raheem, Richard, Yanan, Andy" | split: ", " %}

{% for name in trainee_names %}
  {% assign found = false %}
  {% capture achievements %}
    {% for article in site.data.news %}
      {% assign headline_lc = article.headline | downcase %}
      {% unless headline_lc contains 'shibiao' %}
        {% if headline_lc contains name | downcase %}
          {% assign found = true %}
          <li>{{ article.date }}: {{ article.headline | markdownify }}</li>
        {% endif %}
      {% endunless %}
    {% endfor %}
  {% endcapture %}
  {% if found %}
    <h3>{{ name }}</h3>
    <ul>
      {{ achievements | strip }}
    </ul>
  {% endif %}
{% endfor %} 