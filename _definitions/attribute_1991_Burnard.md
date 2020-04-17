---

lemma: attribute
source: burnard_what_2014
page: §4.3
language: English
contributor: wout
last_updated_by: wout

---

Like "[entity](entity.html)", the word "attribute" has a specific technical sense when used in the [SGML](SGML.html) context, which differs somewhat from its sense when used in the database design context. An SGML attribute is a category of information associated with a particular type of [element](element.html), but not contained within it. Attributes are associated with particular element occurrences by including their name and value within the start-[tag](tag.html) for the element concerned. For example:

Call me `<name type="Biblical">`Ishmael`</name>`.

Here "type" is the name of an attribute associated with any occurrence of the **`<name>`** element, "Biblical" is the value defined for this attribute in the case of the example **`<name>`** above.

Attributes are used for two related purposes: they enable an identifying number or name to be associated with a particular element occurrence within a [text](text.html) (which might otherwise be missing), and they enable additional information missing from a text to be added to it without violating its integrity.
