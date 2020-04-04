### BibTeX Key Format

```
author_title_year
```

each item in 1 word, contracted, downcase

where:

- **only letters and underscores** `[a-z, _]`
- **`author`** = last name of first author
- **`title`** = first word of title EXCEPT articles in any language (e.g. _a, an, the_ for English)
- **year** if a book was published in multiple volumes, `_volumenumber` is appended to the `year`

#### Examples:

- **`author`**

```
author = {Biasi, Pierre-Marc de} 
> biasi
```
```
author = {Deppman, Jed and Ferrer, Daniel and Groden, Michael}
> deppman
```
```
author = {D’Iorio, Paolo}, 
> `diorio`
```
```
author = {Bellemin-Noël, Jean}
> belleminnoel
```
- **`title`**

```
title = {A {New} {Dictionary} of the {English} {Language}} 
> new
```
```
title = {Introduction: {Textual} {Criticism} and {Theory} in {Modern} {German} {Editing}} 
> introduction
```
```
title = {Les manuscrits. {Nouvelle} édition revue.} 
> manuscrits
```
```
title = {Qu’est-ce qu’une édition génétique numérique?}
> questce
```
- **`year`**

```
title = {Digitale {Editionsformen}-{Teil} 2: {Befunde}, {Theorie} und {Methodik}}
author = {Sahle, Patrick},
year = {2013}
volume = {2}
> sahle_digitale_2013_2
```




