---

lemma: LMNL
source: derose_markup_2004
page: 8
language: English
contributor: jesse
last_updated_by: jesse

---
LMNL (the Layered [Markup](markup.html) and Annotation Language […]) overcomes the limitations of marking up non-hierarchies in [XML](xml.html), except that it steps entirely outside the XML paradigm to do so. It can represent unlimited [overlap](overlap.html) of all kinds. In principle LMNL is a data model, not a syntax with an implied data model as [SGML](SGML.html) was, and as XML was until DOM and the Infoset added models.
LMNL does provide a syntax, which is similar to MECS in that it does not require pure nesting like well-formed XML. Components are allowed to overlap arbitrarily, except that self-overlap requires co-indexing (as seems inherantly [sic] necessary for a flat syntax to support structures such as overlap and DAGs, that unlike trees cannot be traversed with merely a stack).
