```yaml
---
title: "Detail in Typography – Distilled Rules"
source: "Jost Hochuli, *Detail in Typography* (Eng. tr. 1996)"
date: "2025-06-28"
version: "0.2-complete"
description: |
  Expanded notes on Hochuli's prescriptions from the book's main chapters.
  I exclude anecdotes, bibliography, and image plates, and all that good stuff.
---
```
# Preface

Typography exists to *serve reading*.  Every decision that improves legibility,
comprehension, and reading rhythm is valuable; anything that merely decorates
must never impede those goals.

---

# Contents

1. Basics
2. The Reading Process
3. The Letter
4. The Word
5. The Line
6. Linespacing & the Column
7. The Qualities of Type
8. Punctuation & Symbols
9. Numerals & Abbreviations
10. Notes (Production & Proofing)

---

# 1 Basics

* **Form follows function & medium.**  Size and layout stem from binding, trim
  size, reading distance, and purpose.
* **Economy of means.**

  * Use *one* type family for text & headings when possible.
  * Let contrast arise from size, weight, white space, not ornamental faces.
* **Whitespace is punctuation.**  Margins, line endings, and inter‑paragraph
  space guide the eye as surely as marks on paper.

---

# 2 The Reading Process

* **Line length governs comfort** → *ideal*: **50–65 characters** including
  spaces for books; ≤ 75 chars for magazines; ≤ 40 chars for narrow columns.
* **Saccadic eye movement** prefers predictable jumps; ragged right edges and
  wildly variable word spacing break rhythm.
* **Lead‑in characters** (quotation marks, bullets) must align optically with
  text, not indent the whole line—a job for hanging punctuation.
* **Paragraph indicators**: *choose one method only*

  * **Indented first line** (≈ 1 em) with no extra vertical gap, *or*
  * **Vertical whitespace** (≥ ½ line) with flush-left first line.

---

# 3 The Letter

* **Choose robust typefaces.**  Large x‑height, open counters, restrained
  stroke contrast suit sustained reading.
* **No letterspacing in lowercase.**  Kern display caps or small caps only.
* **Ligatures**: enable standard (*fi*, *fl*, *ff*) in text; discretionary ligs
  (st, ct) only if the face's design demands them.
* **Accents & diacritics** must sit optically centered and leave cap height
  untouched—avoid fonts with weak accents.

---

# 4 The Word

* **Word spacing ≈ thickness of "i" stem** (~1/4 em at 10 pt).
  Tighten rather than loosen in justified setting; allow hyphenation.
* **Hyphenation rules**

  1. Break only on syllable boundaries.
  2. Never leave fewer than 2 letters before or after break.
  3. Limit consecutive hyphenated lines to 3.
  4. Avoid hyphenating the last word of a paragraph.
* **Capitalisation**: reserve FULL CAPS for abbreviations; prefer Small Caps in
  text.

---

# 5 The Line

* **Leading** = 120 – 145 % of type size.  Start at 133 % (e.g., 10/13 pt).
* **Ragged‑right vs justification**

  * *Ragged*: create a "soft rag" by letting lines vary 5–10 chars and avoiding
    deep indents.
  * *Justified*: enable hyphenation; allow ±2 % glyph scaling if the engine
    supports optical justification.
* **Widows & orphans**

  * Prevent a single word (or ≤ 7 chars) on its own line.
  * Require ≥ 2 lines at top or bottom of page.

---

# 6 Linespacing & the Column

* **Column width dictates leading.**  Wider measure → more leading.
* **Baseline grid** ensures headings, text, and captions align vertically.
* **Vertical rhythm**: keep line‑space increments consistent across
  hierarchies; do not insert arbitrary extra lead before headings—use
  multiples of grid increment.

---

# 7 The Qualities of Type

* **Contrast through relation, not novelty.**  Mix roman/italic/bold within one
  family first; introduce a second face only for a separate voice (quotes,
  side‑notes).
* **Italic for emphasis, not bold.**  Use bold sparingly for labels and
  run‑in headings.
* **Small Caps**: employ true drawn small caps.  Apply *slightly* increased
  tracking (+5 units at 1000‑U scale) for colour parity.
* **Numerals**

  * Text: old‑style numerals align with lowercase rhythm.
  * Tables: lining figures, tabular‐width.

---

# 8 Punctuation & Symbols

* **Hyphen‑minus (‑)** joins compounds (*well‑known*).
* **En dash (–)** for ranges (*1950–60*) and parenthetical thoughts—like this.
* **Em dash (—)** rare in European practice; prefer spaced en dash.
* **Quotation marks**

  * German: „…"
  * English: "…"
  * French: « … » (with thin spaces).
    Use *language‑appropriate* glyphs, not inch/foot primes.
* **Space rules**

  * Single word‑space after sentence‑ending punctuation.
  * Thin (hair) space before en dash used parenthetically.
  * Non‑breaking space between figure & unit (*50 kg*).

---

# 9 Numerals & Abbreviations

* **Units & symbols**: set roman, space‑separated, never italic (*70 km*).
* **Percent sign**: close up (*15 %*), not *15%*.
* **Abbr. with full stops** align to baseline; no extra spacing (*e.g., i.e.*).
* **Currency**: prefer ISO (*EUR 100*) or symbol with thin space (*€ 100*).

---

# 10 Notes – Production & Proofing

* **Optical margin alignment** for punctuation improves block edge.
* **Proof stages**

  1. *Galley*: check content & hierarchy.
  2. *Page proofs*: adjust widows/orphans, colour, baseline grid.
* **Press‑ready PDF** must embed fonts, include 3 mm bleed, and use
  CMYK/Greyscale only—never RGB.

---

# Complete Checklist (tear‑off)

> Verify each item before sign‑off.

| Area          | Rule                        | ✓ |
| ------------- | --------------------------- | - |
| Measure       | 50–65 chars (books)         |   |
| Leading       | 120–145 % size              |   |
| Word spacing  | ≈ "i" stem width            |   |
| Hyphenation   | ≤ 3 consec. lines           |   |
| Paragraphs    | indent **or** space‑between |   |
| Typefaces     | ≤ 2 families                |   |
| Small caps    | true, tracked               |   |
| Numerals      | OSF in text                 |   |
| Dashes        | en for ranges, spaced       |   |
| Widow/orphan  | none                        |   |
| Baseline grid | locked                      |   |

---

# Change Log

* **0.2-complete** – Added sections on punctuation, numerals, production; expanded examples; tabled master checklist.
* **0.1-draft** – Initial.
