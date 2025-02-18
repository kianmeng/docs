# Exercism's Style Guide

This document acts as a Style Guide for the language and wording used in exercises.

## Application

These rules should be followed in all exercises.
Existing descriptions and test-cases can be updated to adhere to them without requiring "replacement" test cases.

### Consistency within an exercise

There are some terms that have multiple valid spellings (e.g. "lower case" vs "lowercase").
Where a consistent style has not been agreed within this document, these must be consistent within an exercise.

### Exceptions

Exercises may vary from these rules if there is general consensus across maintainers that this is reasonable.
For example, an exercise about converting between different units might choose not to use SI measurements.

## Language

All content should be written in US English, which differs from UK English in a [variety of ways](https://en.wikipedia.org/wiki/Comparison_of_American_and_British_English). In the future other translations may occur, but the "official" Exercism language is US English.

### Measurements

All units of measurement must be [SI](https://en.wikipedia.org/wiki/International_System_of_Units) or [SI-derived](https://en.wikipedia.org/wiki/SI_derived_unit) units.

### Abbreviations, acronyms and initialisms

Abbreviations, acronyms and initialisms are often more difficult to understand than other phrasing options, and can alienate people trying to learn.

Many abbreviations are jargon. Avoid jargon where possible by using alternative language. Don't use abbreviations unless either:

- The abbreviated term is better known than the unabbreviated term
- The text will be excessively verbose without abbreviation

When using abbreviations always explain what the term means on its first use. This will often, but not always, include expanding the abbreviation. It will rarely be sufficient to only expand the abbreviation.

Here are some example rules:

- Prefer "if I recall correctly" to "IIRC"
- Prefer "as far as I know" to "AFAIK"
- Prefer "queue" to "FIFO" and "stack" to "FILO"
- Instead of describing an interface as "RESTful", describe its specific properties
- If you must use "CRUD", explain that it stands for Create, Read, Update, Delete and that these are the basic actions in standard databases

An some examples of good usage:

- "HyperText Markup Language (HTML) is the language used to describe document structure and content on the web" _(expanded and explained)_
- "DNA, a set of chemical instructions that influence how our bodies are constructed" _(DNA is not expanded because "deoxyribonucleic acid" is unlikely to help explain what DNA is to our audience)_
- "NASA, the United States' space agency, launched the Mariner 2 space probe in..." _(NASA is not expanded because the "National Aerospace and Space Administration" is much better known by its acronym than by its expanded name)_
- "The Department of Motor Vehicles (DMV) is filled with sloths. That's why everything takes forever at the DMV" _(Define DMV the first time it is used)_

### Grammar

#### Oxford Comma

Use the "[Oxford Comma](https://en.wikipedia.org/wiki/Serial_comma)" (also known as the Serial Comma) in lists. For example, rather than "I love my parents, Lady Gaga and Humpty Dumpty", write "I love my parents, Lady Gaga, and Humpty Dumpty". You may also enjoy [this image as an explanation](https://conchapman.files.wordpress.com/2015/12/panda2.jpg).

#### Exceptions

Some abbreviations are considered common, useful, and non-technical enough that we have decided to permit them:

- `e.g.` or `eg`
- `i.e.` or `ie`
- `etc.` or `etc`
- `docs`

Contractions (e.g. "won't", "I'm", "that's") should be used sparingly if at all in exercise descriptions, but are not restricted in other language around the site (e.g. website copy, mentoring).

Many American English style guides state that the abbreviations "i.e." and "e.g." should be followed by a comma (see, e.g., this [StackExchange thread](https://english.stackexchange.com/questions/7946/use-of-e-g-are-parentheses-necessary/93658#93658)). This is permitted, but not required within text on Exercism.

## Choice of words

### Mathematical and jargon terms.

In any place that mathematical terms are used they should be explained or substituted out for terms that require less domain knowledge.

Examples:

- Rather than using "natural numbers", we should use "positive whole numbers".
- If we want to use the phrase "rational numbers", it must be explained in the introduction to the exercise.
- Rather than using the word range (which can have different meanings in different contexts) use "x < ? < y (greater than x and less than y)".
- Rather than using "esoteric terms", use the phrase "terms not understood by the majority of people".

## Code

All code should be consistently formatted using the style conventions of their track. When possible, these track-wide conventions should match the language's preferred style conventions.
