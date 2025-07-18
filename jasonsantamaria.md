---
title: "On Web Typography"
source: "Jason Santa Maria, *On Web Typography* (A Book Apart, 2014)"
date: "2025-01-18"
version: "1.0"
description: |
  Notes from Jason Santa Maria's beautiful book on web typography. This work
  explores the fundamentals of reading, type evaluation, and typographic systems.
---

# On Web Typography

## How We Read

**Insights & Ideas**

* Reading on screen happens in saccades and fixations—our eyes jump, then pause long enough to recognise word shapes.
* Fluency, context and typography combine to determine readability ("Do I want to keep reading?") rather than mere legibility.
* Good typography "stacks the deck" by making perception effortless across devices, lighting and attention states.
* Word shapes, not individual letters, are the primary recognition unit, so consistent rhythm matters.
* Cognitive load rises when line length, contrast or type choice fight those natural eye movements.

**5 Actions You Can Take**

1. Keep line length ≈ 45–75 characters to minimise eye-strain.
2. Raise `line-height` (1.4–1.6) to give fixations breathing room.
3. Avoid ALL-CAPS in running text; word shapes disappear.
4. Boost colour/brightness contrast to preserve letterforms in low-light.
5. Use familiar, well-hinted faces for body copy so readers recognise patterns instantly.

---

## How Type Works

**Insights & Ideas**

* "There are no absolute rules in typography—only conventions and consequences."
* Distinguish typeface (design) from font (file/container); the nuances matter in collaboration.
* Screen typography succeeded when `@font-face` made custom fonts reliable, but performance still matters.
* Knowing basic anatomy (`x-height`, ascenders, counters) lets you discuss choices with engineers and stakeholders.
* Responsive contexts demand flexible weights, optical sizes and fall-backs.

**5 Actions You Can Take**

1. Load only the weights/styles you use to limit font-file payload.
2. Set `text-rendering` & `font-smoothing` in CSS for crisper display on macOS/Windows.
3. Define a unicode-range subset (WOFF2) for critical-path latin text.
4. Document type anatomy terms in team style-guides so conversations stay precise.
5. Audit contrast & hinting on low-DPI devices before shipping.

---

## Evaluating Typefaces

**Insights & Ideas**

* Basic classification buckets (serif, sans, slab, script, monospace, decorative) filter the vast catalogue.
* Physical traits—`x-height`, contrast, apertures—drive apparent size and tone.
* Licensing, character-set depth and optical sizes are as crucial as looks.
* "Classic" faces save time but can feel dated if they don't suit the medium.
* Revivals vary wildly; evaluate in context, not nostalgia.

**5 Actions You Can Take**

1. Create a short-list of "go-to" faces that you know perform well on screen.
2. Check for multiple numeral sets & small caps when typesetting data-heavy UI.
3. Test at `14px` and `48px`—good faces hold up both for body and display.
4. Read the EULA; ensure web-embedding and page-view limits fit your traffic.
5. Compare `x-height` parity when considering alternatives (helps vertical rhythm).

---

## Choosing & Pairing Typefaces

**Insights & Ideas**

* Start with an "anchor" face that voices the brand; add contrast, not conflict.
* Word-association and research reveal cultural baggage before you commit.
* Ready-made novelty fonts are typographic TV dinners—avoid them.
* Shared proportions or complementary texture often out-perform strict historical mixes.
* Maintain hierarchy with size, weight and colour, not endless font families.

**5 Actions You Can Take**

1. List 3 adjectives for the project, then shortlist faces that embody them.
2. Limit palettes to 2–3 typefaces, using super-families for breadth.
3. Pair by contrast in classification or stroke modulation, not both.
4. Prototype pairings in a real article view, not a specimen sheet.
5. Define alternate stacks for variable fonts in case browsers fall back.

---

## Typographic Systems

**Insights & Ideas**

* Hierarchy expresses structure; choose one variable at a time—size, weight, colour—to signal level.
* Consistency breeds rhythm; systems beat single-page tweaks.
* Scale ratios (e.g., major third) unify headings, body, captions.
* Space (margins, padding, leading) is the silent partner of size.
* Establishing a shared system frees designers to focus on content.

**5 Actions You Can Take**

1. Define a modular scale (e.g., 1.25) and apply it to all font-sizes.
2. Create utility classes/tokens for spacing so vertical rhythm survives refactors.
3. Document heading levels with examples in your component library.
4. Audit colour use—reserve chromatic variation for links or alerts.
5. Version-control your typographic tokens alongside code to track changes.

---

## Composition

**Insights & Ideas**

* Composition is macro-typography: grids, alignment and white-space shape meaning.
* Baseline grids keep multi-column layouts coherent.
* Responsive design demands fluid measures and breakpoints for type as well as layout.
* Whitespace is an active design element—"the pauses between notes."
* Real-world testing (devices, orientations) surfaces micro-adjustments `line-height` math can't.

**5 Actions You Can Take**

1. Lock a `4pt` baseline grid and snap `line-height`, margin and padding to it.
2. Use `ch` units for responsive line-length—e.g., `max-width: 70ch`.
3. Adjust `letter-spacing` (tracking) on headings as they scale.
4. Set media-query bumps for `font-size`, not just layout (e.g., `+2px` at ≥ `1024px`).
5. Print a page and view on e-ink—if it reads well there, it will read well anywhere.

---

## Conclusion & Next Steps

Typography on the web is a conversation between reader, content and device. Mastering it means:

1. Keep learning the language of type—terminology unlocks collaboration.
2. Collect live examples (Fonts In Use, codepens) and annotate what works.
3. Critique your own work aloud to sharpen intent.
4. Iterate with performance budgets so beauty never blocks content.
5. Revisit these chapters periodically; each project reveals deeper nuance.

Use this outline as both a roadmap for study and a checklist for practice—your pages (and readers) will thank you.

## Change Log

* **1.0** (2025-01-18) – Initial complete version cleaned and formatted
