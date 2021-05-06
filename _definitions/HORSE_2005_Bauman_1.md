---

lemma: HORSE
source: bauman_tei_2005
page: 2
language: English
contributor: Wout
updated_by: Wout

---

In HORSE, a content object which is likely to [overlap](overlap.html) another [XML](XML.html) [element](element.html) is used normally whenever it **doesn't** cause an overlap problem, and is encoded using the same element type, but with an improved [version](version.html) of the typed segment-boundary delimiter method whenever it **does**. Thus:

```
<l>I found at a conference C M Sperberg-McQueen</l>
<l>Sang <q>closing, keynoting, I'm speaking</q></l>
<l>And I said to him, <q sID="q2"/>Superman, have you not seen,</l>
<l>The embarrassment havoc I'm wreaking?<q eID="q2"/></l>
```    

Here the existence of the sID= [attribute](attribute.html) indicates that the 2nd occurrence of the `<q>` element is actually a segment-boundary delimiter, the start of what would be a normal `<q>` element if it could.
