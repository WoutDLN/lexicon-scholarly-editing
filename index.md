---
title: Home
description: "homepage"
layout: homepage
---
{%- assign languages = site.definitions | map: "language" | uniq | sort_natural -%}
{%- assign sources = site.definitions | map: "source" | uniq | sort_natural -%}
{% include variables/contributors.html %}

This [Github](https://github.com)-hosted [Jekyll](https://jekyllrb.com) version of the Lexicon of Scholarly Editing currently covers **{{ site.lexicon | size }} lemmas**, aggregating a total of **{{ site.definitions | size }} definitions** from **{{ sources | size }} sources** in **{{ languages | size }} languages** ({{ languages | array_to_sentence_string }}), contributed by **{{ contributors_linked | size }} contributors** ({{ contributors_linked | array_to_sentence_string }}).

{% include search/searchbar.html %}
