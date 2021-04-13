---

lemma: schema
source: burnard_what_2014
page: 15-16
language: English
contributor: caroline
last_updated_by: caroline

---

A schema specifies a set of [element](element.html) names, the names and datatypes of any [attributes](attribute.html) associated with them, and rules about the contexts in which they may legally appear.A schema for our simple example above will say that elements named <doc>, <p>, <placeName> etc exist. It may also specify that <p> elements may appear within <doc> elements, that <placeName> s may appear within <p> s, that the attribute @n must have a numeric value etc. Note however that an [XML](XML.html) schema still has no way of specifying that the tag <placeName> indicates the name of a place, or what we mean by “a place”: such additional semantic constraints must be specified elsewhere, for example by documentation such as that provided by the [TEI](TEI.html) Guidelines.
