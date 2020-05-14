---
title: Home
description: "homepage"
---
{% include variables/languages.html %}
{% include variables/contributors.html %}
{% include variables/sources.html %}

This [Github](https://github.com)-hosted [Jekyll](https://jekyllrb.com) version of the Lexicon of Scholarly Editing currently covers **{{ site.lexicon | size }} lemmas**, aggregating a total of **{{ site.definitions | size }} definitions** from **{{ sources | size }} sources** in **{{ languages | size }} languages** ({{languages | join: ", "}}), contributed by **{{ contributors | size }} contributors** ({{contributors | join: ", "}}).

{% include search/searchbar.html %}
