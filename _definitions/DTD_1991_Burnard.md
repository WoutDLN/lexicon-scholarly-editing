---

lemma: DTD
source: burnard_what_2014
page: §5.1
language: English
contributor: wout
last_updated_by: wout
last_update: 06-04-2020

---

A DTD performs a function analogous to that of a grammar: it formally defines what are the legal productions of a given [markup](markup.html) language. Of course, DTDs can be as lax or as restrictive as any other kind of grammar: the designer of  a DTD generally has to trade off generality of use with accuracy of error detection. The simplest kind of DTD would be one which did no more than specify a set of [tag](tag.html) names, requiring only that every [element](element.html) tagged in a document use one of them. Such a DTD would of course be unable to detect errors such as **`<name>`**s occurring within **`<name>`**s or within **`<date>`**s, nor to prohibit such errors as register entries appearing other than inside registers. Creating correctly encoded [texts](text.html) with such a DTD would be rather like trying to speak a foreign language with the aid of a lexicon of the language, but no idea of its syntax.
