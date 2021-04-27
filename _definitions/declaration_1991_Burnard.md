---

lemma: declaration
source: burnard_what_2014
page: 5.1
locator: §
language: English
contributor: wout
last_updated_by: wout

---

Here, for example, is a part of the formal [DTD](DTD.html) for the register example given informally above.

`<!ELEMENT register - - (entry+)>`
                `<!ELEMENT entry - o (name, trade, relation?)>`
                `<!ELEMENT name - - (#PCDATA)>`


These three lines are examples of [SGML](SGML.html) _declarations_: each defines or declares a name for an [element](element.html) and what its content should be. The details of the syntax need not detain us; note only that each declaration (like everything else in SGML) is explicitly delimited, in this case by a symbol marking the start of a declaration (the "[`<!]")
