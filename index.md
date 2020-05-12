---
title: Home
---

{% assign languages = "" | split: "" %}
{% for definition in site.definitions %}
{% assign languages = definition.language | concat: languages %}
{% endfor %}
{% assign languages = languages | uniq | sort_natural %}

{% assign contributors = "" | split: "" %}
{% for definition in site.definitions %}
{% assign contributors = definition.contributor | concat: contributors %}
{% endfor %}
{% assign contributors = contributors | uniq | sort_natural %}

This [Github](https://github.com)-hosted [Jekyll](https://jekyllrb.com) version of the Lexicon of Scholarly Editing currently covers **{{ site.lexicon | size }} lemmas**, aggregating a total of **{{ site.definitions | size }} definitions** in **{{ languages | size }} languages** ({{languages | join: ", "}}), contributed by **{{ contributors | size }} contributors** ({{contributors | join: ", "}}).


## Search the Lexicon:

{% include searchbar.html %}
