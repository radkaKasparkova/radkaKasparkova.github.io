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

<ul>
{% assign posts = site.tags["nejasny-problem"] | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🪟 Falešná shoda

Lidé si myslí, že se shodli.  
Ve skutečnosti si každý představuje něco jiného.

<ul>
{% assign posts = site.tags["falesna-shoda"] | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🧊 Iluze jednoduchosti

Něco vypadá jako malá změna.  
Ale systém je mnohem komplexnější.

<ul>
{% assign posts = site.tags["iluze-jednoduchosti"] | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🧩 Proces zadání

Problémy vznikají v tom, **jak se zadání tvoří**.

<ul>
{% assign posts = site.tags["proces-zadani"] | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🧭 Rozhodovací chaos

Projekt nemá jasné rozhodování.

<ul>
{% assign posts = site.tags["rozhodovaci-chaos"] | sort: "date" | reverse %}
{% for post in posts %}
<li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
