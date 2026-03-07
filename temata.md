---
layout: page
title: Témata
permalink: /temata/
---

V IT projektech se pořád opakují stejné situace.
Níže je několik typů problémů, které se v praxi objevují nejčastěji.

---

## Nejasný problém

Situace, kdy projekt řeší řešení místo problému.

<ul>
{% assign posts = site.tags["nejasny-problem"] | sort: "date" | reverse %}
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

---

## Falešná shoda

Situace, kdy si lidé myslí, že se shodli,
ale každý si představuje něco jiného.

<ul>
{% assign posts = site.tags["falesna-shoda"] | sort: "date" | reverse %}
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

---

## Iluze jednoduchosti

Situace, kdy změna vypadá malá,
ale systém je mnohem komplexnější.

<ul>
{% assign posts = site.tags["iluze-jednoduchosti"] | sort: "date" | reverse %}
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

---

## Proces zadání

Problémy vznikající při tvorbě zadání.

<ul>
{% assign posts = site.tags["proces-zadani"] | sort: "date" | reverse %}
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

---

## Rozhodovací chaos

Situace, kdy projekt nemá jasné rozhodování.

<ul>
{% assign posts = site.tags["rozhodovaci-chaos"] | sort: "date" | reverse %}
{% for post in posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
