# Contribute

This is the quick-reference cheat sheet for adding definitions to the Lexicon in four simple steps. For a more elaborate walk through these steps, check out our [wiki](https://github.com/WoutDLN/lexicon-scholarly-editing/wiki).

## Step 1: add contributors
### 1.1 create contributor file
If this is your first contribution, add a `.md` file to `_contributors` so we can aggregate your contributions. For the filename, use:
```
username.md
```

### 1.2 add front matter
Inside the `.md` file, complete the following variables: `username` (lower case first name), `name` (full name, capitalized), `position` (usually `contributor`), `joined` (today's date).

### 1.3 add short bio
Below the front matter, write a few lines about yourself, using markdown formatting.

### 1.4 complete example of contributor file
```
---
username: elli
name: Elli Bleeker
position: contributor
joined: 2015-01-26
---
DiXiT fellow who is based at the [Centre for Manuscript Genetics](https://www.uantwerpen.be/en/rg/centre-for-manuscript-genetics/) at the University of Antwerp, Belgium.
```

## Step 2: add reference
Add a BibTeX entry for the source you're quoting to the `lexicon.bib` file inside the `_bibliography` directory.

## Step 3: add lemma
### 3.1 create lemma file
If the lemma of your definition is not in the Lexicon yet a `.md` file to `_lexicon`. For the filename, use:
```
lemmaName.md
```

### 3.2 add front matter
The lemma needs at least a `name` variable in the front matter. Just write it as you would like it to appear in the Lexicon's list of concepts. If your lemma has diacritics(such as letters with accents), write the lemma **without** diacritics in `name`, and a version **with** diacritics in a `name_diacritics` variable. You can also add [lists] of tags or categories.

### 3.3 complete example of lemma file
```
---

 name: ecriture a processus
 name_diacritics: écriture à processus
 categories: [Genetic Criticism]
 tags: [processus-programme]

---
```

## Step 4: add definition
### 4.1 create definition file
Add a `.md` file to the `_definitions` directory. For the filename, use: `lemmaFilename_year_lastNameFirstAuthor`. E.g.: `avantTexte_2004_Deppman.md`.

### 4.2 add front matter
Inside the `.md` file, complete the following variables:
- `lemma` (value of corresponding lemma's `name` variable),
- `source` (`@key` of corresponding BibTeX source in `lexicon.bib`),
- `page` (page number, page range, other locator, or n.p. for 'no page'),
- `language` (English full name of the definition's language),
- `contributor` (`username` of whoever initially added the definition to the Lexicon), and
- `last_updated_by` (`username` of whoever last updated/corrected the definition).

### 4.3 add definition
Below the front matter, write out the full definition, using markdown formatting. Try to be as true to the original as possible. If possible, add links to other definitions in the lexicon, using `[linked text](lemmaFileName.html)`.

### 4.4 complete example of a definition file
```
---

lemma: écriture à processus
source: gresillon_elments_1994
page: 243
language: French
contributor: wout
last_updated_by: wout

---

**Ecriture à processus:** type d'[écriture](writingProcess.html) sans phase préparatoire, sans plan, toujours déjà textualisant; exemple: Proust.
```
