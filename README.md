# Draconic Language

A constructed Draconic language created for use in a **Pathfinder 2e** campaign. Its intended voice is **threatening, bestial, ancient, confident, and playable at the table**. It was designed to feel natural for dragons rather than for humans, favoring guttural resonance, hissing friction, hard consonantal endings, and low dependence on labial articulation.

This language was created for the campaign **_It began with the Goblin's red smoke_**, GM'ed by **YullyBear** in **Gamer's Plane**.

---

## Design Goals

The language follows a narrow and deliberate design space:

- **Dragon-native sound**: throat-driven, harsh, controlled, and old
- **Playable by humans**: alien in flavor, but still pronounceable and usable in play
- **Compact morphology**: stable roots, mostly suffixing, semantically transparent
- **Oracular tone**: especially suited to prophecy, warning, fate, memory, omen, and temporal ambiguity
- **Poetic but restrained syntax**: ritual and elevated speech without excessive grammatical complexity

---

## Current State

This repository currently defines the language’s foundational systems:

- phonology and orthography
- inflection and derivation
- syntax
- core lexicon

The present version is a **compact baseline** intended to support actual in-game speech, naming, invocations, warnings, prophecy, and short poetic or ritualized texts.

---

## Phonology and Orthography

The phonological system is intentionally restrictive and built around:

- rear articulation dominance
- fricative pressure
- hard word closure

Its approved inventory centers velar, uvular, glottal, and hissing sounds. Final vowels are rare and marked; consonant-final roots are preferred. The writing system uses a practical Latin orthography for usability during play while preserving an inhuman, draconic texture.

### Approved vowels

`a i u o`

### Sample orthographic values

- `q` = /q/
- `kh` = /x/
- `gh` = /ɣ/
- `qh` = /χ/
- `sh` = /ʃ/
- `ng` = /ŋ/
- `'` = /ʔ/

---

## Morphology

The language uses a **suffixing agglutinative** structure with **root compounding** as its primary derivational strategy. Bare lexical roots usually end in consonants, while derived and inflected forms may become more vowel-bearing to remain pronounceable.

### Nouns

Nominal inflection currently marks:

- **number**
- **case**

#### Number
- unmarked singular
- `-a` collective plural
- `-i` individuated plural

#### Case
- unmarked absolutive
- `-ash` genitive
- `-uq` locative
- `-ar` allative
- `-ikh` ablative
- `-uz` instrumental

### Verbs

Verbal inflection prioritizes:

- **aspect**
- **mood**
- **evidentiality**

Tense is not primary; time is expressed mainly through lexical items and oracle-oriented semantics. The basic template is:

`ROOT-ASPECT-MOOD-EVIDENTIALITY`

#### Aspect
- unmarked perfective
- `-a` imperfective
- `-i` habitual
- `-u` prospective

#### Mood
- unmarked indicative
- `-ak` imperative
- `-as` subjunctive
- `-ang` oath-bound / decree-bound

#### Evidentiality
- `-iq` directly witnessed
- `-ish` inferred
- `-uz` reported
- `-uqh` foreseen / prophetically known

### Negation

Negation is expressed by the separate preverbal particle:

`na`

---

## Syntax

The canonical clause order is **SOV**, with limited reordering allowed for emphasis, ritual tone, or poetic effect. Temporal fronting is especially characteristic, which helps give the language an oracular cadence.

### Main syntactic traits

- canonical **SOV**
- adjectives before nouns
- possessor in genitive before head noun
- adverbs generally preverbal
- temporal elements often clause-initial
- copula `'ar` may be omitted in brief nominal clauses
- question particle `sor` typically clause-final
- coordination uses `war` (“and”) and `nor` (“or”)

The result is a syntax that supports:
- ordinary direct speech
- ritual statements
- invocations
- warnings
- short poetic lines
- oracle speech with deliberate temporal ambiguity

---

## Lexicon

The lexicon is currently centered on domains especially useful in fantasy play and oracle characterization:

- time
- prophecy
- memory
- fate
- warning
- divinity
- dragons
- place
- combat
- ritual speech

### Sample words

| Draconic | Gloss |
|---|---|
| `zhaq` | future |
| `ghar` | past |
| `qhar` | prophecy |
| `ghosh` | vision |
| `shorq` | warning |
| `nakh` | to remember |
| `qhosh` | to foresee |
| `qhazr` | dragon |
| `qarsh` | path |
| `worq` | fire |  

### Example phrase kernels

- `nakh zhaq` — “remember the future”
- `shar 'ar nok nor shar 'ar qhar` — “are you now or are you then”
- `qalorng shiq sukh war zorq` — “the gods show ash and gold”
- `qhazr nakh` — “the dragon remembers”

---

## Repository Purpose

This repository exists to preserve and expand the language in a structured way. It is intended as both:

- a usable language resource for the campaign
- a design archive for future development steps

Future work may include:

- expanded grammar
- more derivational patterns
- naming conventions
- ritual formulae
- sample texts
- prayers, prophecies, threats, and battlefield speech
- possible script or stylistic orthographic variants

All future additions should preserve the established identity of the language: **severe, ancient, dragon-native, controlled, and playable**.

---

## Files

Suggested repository contents:

- `Phonology and Orthograpy Block.txt`
- `Inflection and Derivation.txt`
- `Syntax.txt`
- `Lexicon.txt`
- `Basic idea.txt`

These files define the current baseline and should be treated as the authoritative foundation for further expansions.

---

## Design and Implementation

This conlang was designed by me (Kos Kallah) by guiding GPT 5.4 through a subset of the process outlined by Mark Rosenfelder in his book [The Language Construction Kit](https://www.amazon.com/Language-Construction-Kit-Mark-Rosenfelder-ebook/dp/B005RX79Z4?ref_=ast_author_mpb)

---

## License

Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).