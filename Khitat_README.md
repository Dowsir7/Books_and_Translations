# al-Maqrizi, *Description topographique et historique de l'Égypte* (Bouriant) — English translation

An English translation of **Urbain Bouriant's French edition** of the opening
volume of al-Maqrizi's *Khitat* — Parts 1 and 2, covering the Introduction and
the topographical/historical survey of Egypt from cosmology and the Nile through
the towns of the Delta, the Said, Nubia, the oases, and the Fayoum.

> **Read this first — what this is and isn't.**
> This is a **machine translation of a secondary source**, produced with a large
> language model and lightly normalized by hand. It is *not* a scholarly edition
> and has not been checked against Maqrizi's original Arabic. Treat it as a
> reading aid for the curious, not as a citable text. See *Caveats* below.

## Source

- **Author:** Taqi al-Din Ahmad ibn 'Ali al-Maqrizi (1364–1442)
- **French translator:** Urbain Bouriant (1849–1903)
- **Edition translated here:** *Description topographique et historique de
  l'Égypte, 1re et 2e partie*, traduite en français par U. Bouriant. Paris:
  E. Leroux, 1895–1900. (Mémoires publiés par les membres de la Mission
  archéologique française au Caire, t. 17.)
- **Scope of the French edition:** a translation of vol. 1, pp. 1–397 of the
  Bulaq edition of 1270 AH (1853) — i.e. the first volume's worth of the
  *Khitat*. Bouriant published no more; Parts 3–4 were later translated
  separately into French by Paul Casanova.
- **Digitized original (public domain):** Gallica / Bibliothèque nationale de
  France — https://gallica.bnf.fr/ark:/12148/bpt6k5828537q

The underlying French edition is in the public domain (published 1895–1900;
translator died 1903).

## Contents of this repository

- **`bouriant_complete_en_normalized_2026-06-09.txt`** — the full translation,
  ~21,000 lines. Inline `[PDF p. N]` markers refer to page numbers of the
  digitized Bouriant PDF. This is the normalized master (consistent chapter
  numbering and transliteration); see *Normalization* below.
- **`bouriant_chapter_summaries_2026-06-09.txt`** — a brief summary of each of
  the 131 chapters, as a companion / table of contents.
- (Optionally) the original `bouriant_complete_en.txt` and a dated full snapshot,
  kept as pre-normalization backups.

## How it was made

The Bouriant PDF was processed page by page; each page's French text was
extracted and translated into English, then assembled into a single file. Editorial
conventions used throughout:

- Inline page markers in the form `[PDF p. N]`.
- Bouriant's own transliterations of names are kept (e.g. *Masr*, *Fostat*,
  *Boulaq*, *Moqattam*, *El Maqoqos*).
- Hijri dates carry Bouriant's Western equivalents inline in brackets.
- Garbled OCR was reconstructed where unambiguous, otherwise flagged with
  `[illegible]`, `(?)`, or a bracketed note.
- Untranslatable inline Arabic (grammatical discussions, etc.) is bracketed.

## Normalization

A light pass was applied to the master file, changing **120 lines only** (no prose
was altered):

- First-Part chapter headings converted from words ("CHAPTER ONE") to roman
  numerals ("CHAPTER I"), to match the Second Part. The two parts each number
  their chapters independently (First I–XLVI, Second I–LXXXV), separated by a
  "SECOND PART" banner, faithful to Bouriant.
- The four highest-frequency transliteration variants were standardized
  (Qaftorim→Qaftarim, Beisar→Beïsar, the stray Maqauqos→Maqoqos). Other minor
  OCR-inherited spelling inconsistencies in Bouriant's text may remain.

## Caveats

- **Translation of a translation.** This is English from Bouriant's French, which
  is itself one remove from Maqrizi's Arabic. Two layers of interpretation sit
  between this text and the original.
- **Machine-generated and unverified.** It has not been collated against the
  Arabic or against Bouriant line by line. Errors of sense, omission, and
  transliteration are possible.
- **OCR artifacts.** The source was read by OCR; some passages were reconstructed
  or marked uncertain.
- **Not for citation.** For scholarly purposes use the Arabic, Bouriant's French,
  or a proper scholarly translation (below).

## Existing scholarly translations (for the rigorous reader)

No *complete* published English translation of the *Khitat* exists. The principal
scholarly effort is the late **Karl Stowasser's** annotated translation, which
covers a bit more than the first half of vol. 1 of the Bulaq edition (ending
around p. 285) — overlapping the same ground as this file. It is available
open-access (eds. Frédéric Bauden & Clopper Almon, Liège, 2022; handle
`2268/237608`). A new critical edition with English translation is in progress
in Brill's *Bibliotheca Maqriziana* series. Anyone needing accuracy should go
there.

## License / use

The underlying Bouriant edition is public domain. This machine-generated English
text is offered freely for any use. Given how it was produced, its own copyright
status is uncertain; treat it as public-domain-equivalent. No warranty as to
accuracy.
