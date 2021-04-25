---

lemma: JITM
source: eggert_text_2005
page: 431
language: English
contributor: caroline
last_updated_by: caroline

---

Just In Time Markup (JITM). The logic of it is quite simple: see Fig. 1. JITM uses stand-off [markup](markup.html) stored in any number of external tagsets. The user chooses which of them will present or interpret the base [transcription](transcription.html) file. The chosen tagsets are inserted into the transcription file upon the user’s call (‘Just In Time’). The base transcription file consists _only_ of the verbal [text](text.html) contained within uniquely identified text [element](element.html) [tags](tag.html). JITM automatically authenticates the content of these text elements against a stored hash value prior to and after the embedding of the markup into the text. The practical effect of this authentication is that JITM allows a base transcription file to be annotated or augmented with analytical or structural markup, in parallel and continuously, while retaining its textual integrity. Different or conflicting structural markups can be applied to the same base file in separate passes because they are in different stand-off files and can be applied to the base file selectively. In all of this, the base transcription file remains as simple as possible (thereby greatly easing its portability into future systems) and the authentication mechanism remains non-invasive. Because JITM separates the textual transcription from the markup, [copyright](copyright.html) is also simplified. Since the markup is necessarily interpretative, a copyright in it can be clearly attributed, even if the work itself is out of copyright.
