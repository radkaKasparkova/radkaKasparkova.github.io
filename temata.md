---
layout: page
title: Témata
permalink: /temata/
---

V IT projektech se pořád opakují stejné situace.

Nejsou to náhodné chyby.  
Jsou to **vzorce**.

Níže je několik typů problémů, které se v praxi objevují nejčastěji.

---

## 🎯 Nejasný problém

Projekt řeší **řešení místo problému**.

{% assign posts = site.tags["nejasny-problem"] %}
{% if posts %}
<ul>
{% assign posts = posts | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<em>Zatím bez článků.</em>
{% endif %}

---

## 🪟 Falešná shoda

Lidé si myslí, že se shodli.  
Ve skutečnosti si každý představuje něco jiného.

{% assign posts = site.tags["falesna-shoda"] %}
{% if posts %}
<ul>
{% assign posts = posts | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<em>Zatím bez článků.</em>
{% endif %}

---

## 🧊 Iluze jednoduchosti

Něco vypadá jako malá změna.  
Ale systém je mnohem komplexnější.

{% assign posts = site.tags["iluze-jednoduchosti"] %}
{% if posts %}
<ul>
{% assign posts = posts | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<em>Zatím bez článků.</em>
{% endif %}

---

## 🧩 Proces zadání

Problémy vznikají v tom, **jak se zadání tvoří**.

{% assign posts = site.tags["proces-zadani"] %}
{% if posts %}
<ul>
{% assign posts = posts | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<em>Zatím bez článků.</em>
{% endif %}

---

## 🧭 Rozhodovací chaos

Projekt nemá jasné rozhodování.

{% assign posts = site.tags["rozhodovaci-chaos"] %}
{% if posts %}
<ul>
{% assign posts = posts | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
{% else %}
<em>Zatím bez článků.</em>
{% endif %}
