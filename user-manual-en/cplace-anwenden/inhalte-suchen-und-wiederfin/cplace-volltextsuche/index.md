:::::: {.col-12 .col-md-8 .col-lg-8 .col-xl-7 .py-md-3 .pl-md-4 .bd-content role="main"}
::: {.col-lg-12 .col-md-12 .p-0 .breadcrumbs}
[]{.fa .fa-bars .text-color}

[](https://docs.cplace.io/){aria-label="Knowledge Base Home"}  [User
Manual](/user-manual-en/){.docs-space-page} / [Using
cplace](/user-manual-en/cplace-anwenden/){.docs-subtopic-page} /
[Searching for and retrieving
content](/user-manual-en/cplace-anwenden/inhalte-suchen-und-wiederfin/){.docs-subsubtopic-page}
/ [The full-text search in cplace]{.docs-current-page} [
Edit](https://github.com/collaborationfactory/cplace-doc-user-enu/blob/release/25.2/cplace-anwenden/inhalte-suchen-und-wiederfin/cplace-volltextsuche.md){.edit-btn
.float-end}
:::

# The full-text search in cplace

The full-text search is a search function based on the Elasticsearch
search engine. This section describes a number of criteria in which the
full-text search deviates from the standard behavior of Elasticsearch or
extends the functionality of this search engine.

## Case sensitivity

Case sensitivity (upper and lower case) is not taken into account during
the search.

## Search terms

The search query is divided up into individual terms. Every character
that is not a letter or a number is regarded as a separator and is
ignored during the search. All terms except the last term are searched
for as exact words. The last term of the search query is regarded as a
prefix, i.e., both identical matches and character strings which begin
with the prefix are found. If you insert a separator after the last
term, it is treated as a single term and no longer as a prefix.

For the respective last term of a query the search is started in the
background already while the entry is being made.

The individual terms of a search are linked with AND.

If the entire query is enclosed in double quotation marks, it is
regarded as a single term. This allows you to search for exactly one
word or a group of words.

### Special features in the case of search entries in Chinese characters

If you enter several Chinese characters, the search will return results
for these characters in the order entered. You can separate single words
or characters with a space. This allows you to get hits for the
characters in a different order or find phrases that only contain the
related characters entered.

::: {.note .note-example .with-title}
**Examples for searching with Chinese characters**

- If you enter 大学, you will not get a hit for 学大, as the order of
  non-separated characters is taken into account.
- If you enter 香港理工 大学 (space between 香港理工 and 大学), you will
  receive hits for both 香港理工大学 and 大学香港理工. As a result of
  the space between 香港理工 and 大学 you will get hits for results with
  different sequences of characters.
- If you enter 香港大学, you will not get a hit for 香港理工大学 because
  理工 is missing from the search entry.
- If you enter 香港 大学 (space between 香港 and 大学), you will get a
  hit for 香港理工大学, as 香港 and 大学 are separated by a space.\\
:::

### Special features in the case of search entries in Japanese characters

Japanese words and word groups are searched for as connected phrases
provided they are not separated by punctuation marks (space, Japanese
space, comma, etc.). Changing the script, i.e., the writing system, does
not interrupt the phrase.

Entering words in one of the writing systems, e.g., in hiragana, will
not return results of the same word in katakana or kanji.

::: {.note .note-example .with-title}
**Example for the search with Japanese characters**

- If you enter さくら (hiragana), you will not get a hit for 桜 (kanji)
  or サクラ (katakana).
:::

## Searched elements, results, and weighting

The following elements on a page are searched:

- Title
- Tags
- Content

The content is an amalgamation of all text fields on a page. If
documents are attached in a text format on a page, these are also taken
into account during the search.

The results of a search are weighted differently depending on the type
of the field. If a result is found in a field of the type "Name", this
field receives a boost value of 15, in other words, it is multiplied by
a factor of 15. A hit in a field of the type "Tag" has the boost value
5, a hit in the content has the boost value 1.

The "Title", "Tags" and "Content" fields are linked with OR, i.e a
result is returned if a search term is found in at least one of these
fields.

## Permissions

During every search, the permissions of the user carrying out the search
are checked. Only those pages for which the user possesses a read
permission are searched. If there are hits for which the user does not
have read permission, the user is not informed of them.
::::::
