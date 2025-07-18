```yaml
---
title: "Practical Typography"
source: "Matthew Butterick's 'practicaltypography.com'"
date: "2025-06-28"
version: "0.1-complete"
description: |
  Expanded notes and points from Practical Typography, a style guide by Matthew Butterick.
---
```


# Practical Typography: Style Guide Notes

*Based on Matthew Butterick's "Practical Typography" - A comprehensive reference for typographic best practices in digital and print media*

## Quick Reference: Typography in 10 Minutes

**Core Principle:** The typographic quality of any document is determined largely by how the body text looks, because there's more body text than anything else. Start every project by making the body text look good, then worry about the rest.

### The 5 Essential Typography Rules

1. **Point Size**: 10-12 points in print, 15-25 pixels on web
2. **Line Spacing**: 120-145% of point size (never use default single-line spacing)
3. **Line Length**: 45-90 characters per line (roughly 2-3 lowercase alphabets)
4. **Font Choice**: Use professional fonts, avoid system fonts like Times New Roman and Arial
5. **Page Margins**: Larger than 1 inch in print, prevent text from flowing to browser edges on web

---

## Comprehensive Typography Rules

### BODY TEXT FUNDAMENTALS

**Point Size**
- Print: 10-12 points optimal for readability
- Web: 15-25 pixels (adjust based on font appearance)
- Rule: Not every font appears equally large at same point size - adjust as needed

**Line Spacing (Leading)**
- Target: 120-145% of point size
- Word processors: Use "Exact" line spacing option
- CSS: Use unitless line-height values (e.g., 1.3 instead of 130%)
- Avoid: Default single-line (too tight) and 1.5-line (too loose) options

**Line Length**
- Optimal: 45-90 characters per line (including spaces)
- Measurement: 2-3 lowercase alphabets (abcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyzabcd)
- Implementation: Requires proper page margins or container widths

**Font Selection Priority**
1. Professional fonts (best choice)
2. System fonts (acceptable if chosen wisely)
3. Free fonts (generally avoid)
4. Never: Times New Roman, Arial (marks of apathetic typography)

### CHARACTER AND PUNCTUATION RULES

**Quotation Marks**
- Always use curly quotes: " " and ' '
- Never use straight quotes: " and '
- Context: Applies to all quotation marks, not just dialogue

**Spacing Between Sentences**
- Rule: Exactly one space between sentences
- Never: Multiple spaces (typewriter habit)
- Never: Multiple word spaces or white-space characters in a row

**Hyphens and Dashes**
- Hyphen (-): For compound words and line breaks
- En dash (–): For ranges (pages 15–30) and compound adjectives
- Em dash (—): For breaks in thought—like this
- Never: Multiple hyphens as substitute for dashes

**Apostrophes**
- Direction: Always point downward (')
- Not: Straight marks (')
- Context: Contractions and possessives

**Ellipses**
- Use proper ellipsis character (…)
- Not: Three periods with spaces (. . .)
- Spacing: Treat as single character

**Foot and Inch Marks**
- Use straight marks: 5' 10" or 5′ 10″
- Not: Curly quotes for measurements
- Context: Only for actual measurements

### TEXT FORMATTING GUIDELINES

**Bold and Italic Usage**
- Use sparingly and purposefully
- Never combine bold and italic together
- Purpose: Emphasis, not decoration

**Underlining**
- Avoid completely in print
- Exception: Web links (but consider alternatives)
- Alternative: Use bold or italic for emphasis

**All Caps**
- Limit: Less than one line of text
- Required: Add 5-12% extra letterspacing
- Context: Headers, logos, short emphasis

**Small Caps**
- Only use real small caps (OpenType feature)
- Never fake small caps (reduced regular caps)
- Required: Add 5-12% extra letterspacing
- If unavailable: Don't use at all

**Centered Text**
- Use sparingly
- Best for: Short headlines, formal invitations
- Avoid for: Body text, long passages

**Letterspacing and Kerning**
- Kerning: Always enable in all applications
- Extra letterspacing required for:
  - All caps: 5-12% extra
  - Small caps: 5-12% extra
- Never add letterspacing to regular mixed-case text

### PARAGRAPH AND PAGE LAYOUT

**Paragraph Separation**
- Choose one method:
  1. First-line indents (1-4 times the point size)
  2. Space between paragraphs (4-10 points)
- Never use both methods together
- First paragraph: No indent after headings

**Hyphenation**
- Always use with justified text
- Recommended for most text layouts
- Set appropriate hyphenation zone in software

**Justified vs. Flush Left**
- Justified: Requires hyphenation to avoid bad spacing
- Flush left: More forgiving, easier to implement
- Never: Centered body text, flush right body text

**Page Margins**
- Print minimum: Larger than 1 inch
- Rationale: Proper line length and visual breathing room
- Web: Prevent text from touching browser edges

**Line Spacing Variations**
- Body text: 120-145% of point size
- Headings: Can be tighter (100-120%)
- Dense material: Toward 145%
- Airy layouts: Toward 120%

### SPECIALIZED PUNCTUATION

**Ampersands (&)**
- Use sparingly
- Appropriate: Company names, formal titles where included
- Avoid: As substitute for "and" in regular text

**Trademark and Copyright Symbols**
- Use proper symbols: ® © ™
- Not alphabetic approximations: (R) (C) (TM)
- Legal accuracy matters

**Exclamation Points**
- Extreme restraint: One per document over 3 pages
- Context: Genuine exclamations only
- Avoid: Multiple exclamation points (!!!)

**Question Marks**
- Standard usage applies
- Avoid: Multiple question marks (???)
- Style: Match text formatting

**Math Symbols**
- Use proper mathematical symbols: × ÷ ± ≠ ≤ ≥
- Not: Keyboard approximations like x for multiplication
- Context: Mathematical expressions and equations

**Paragraph and Section Marks**
- Use proper symbols: ¶ §
- Include nonbreaking space after the symbol
- Context: Legal documents, academic references

### DIGITAL-SPECIFIC CONSIDERATIONS

**Web Typography**
- Font loading: Consider fallbacks and performance
- Responsive sizing: Adjust for different screen sizes
- High-resolution displays: Most fonts now work well
- Accessibility: Maintain proper contrast ratios

**Email Typography**
- Simplified approach: Many email clients strip formatting
- Stick to basics: Proper spacing, minimal formatting
- Test across clients: Gmail, Outlook, mobile apps

**PDF Generation**
- Embed fonts: Ensures consistent appearance
- Resolution: Appropriate for intended use
- Accessibility: Include proper tags and structure

### FONT SELECTION HIERARCHY

**Professional Fonts (Recommended)**
- Investment in quality pays long-term dividends
- Consider licensing for organization use
- Evaluate: Character set, language support, OpenType features

**System Font Alternatives (When Budget Constrains)**
- Better choices: Charter, Palatino alternatives
- Avoid: Times New Roman, Arial, Courier
- Evaluate carefully: Not all system fonts are equal

**Free Font Caution**
- Most free fonts: Poor quality, limited character sets
- Exceptions exist but require careful evaluation
- Consider: Long-term support and updates

### ADVANCED TYPOGRAPHY FEATURES

**OpenType Features**
- Ligatures: Enable for better character combinations
- Alternate figures: Use appropriate number styles
- Small caps: Real small caps when available
- Contextual alternates: Let font optimize automatically

**Mixing Fonts**
- General rule: Stick to one font family
- If mixing: Ensure clear hierarchy and purpose
- Test thoroughly: Ensure compatibility across uses

**Color in Typography**
- Use purposefully, not decoratively
- Maintain sufficient contrast for readability
- Consider accessibility requirements
- Test in different contexts: screen, print, projection

### DOCUMENT-SPECIFIC APPLICATIONS

**Business Documents**
- Professional appearance essential
- Conservative font choices appropriate
- Consistent formatting throughout
- Clear hierarchy with headings

**Academic Writing**
- Follow specific style guide requirements
- Footnotes and citations: Consistent formatting
- Long documents: Extra attention to readability
- Tables and figures: Clear, well-formatted

**Web Content**
- Performance considerations: Font loading strategy
- Responsive design: Appropriate scaling
- User control: Respect accessibility preferences
- Cross-browser testing: Ensure consistency

### QUALITY CONTROL CHECKLIST

**Before Finalizing Any Document:**
- [ ] Body text uses appropriate point size and line spacing
- [ ] Line length falls within 45-90 character range
- [ ] All quotation marks are curly, not straight
- [ ] Single space between all sentences
- [ ] Hyphens and dashes used correctly
- [ ] Apostrophes point downward
- [ ] No fake small caps or inappropriate all caps
- [ ] Consistent paragraph separation method
- [ ] Proper margins and spacing throughout
- [ ] Professional font choice maintained
- [ ] All caps and small caps have extra letterspacing
- [ ] Kerning enabled in all applications

### COMMON MISTAKES TO AVOID

**Typography Sins:**
- Double spaces between sentences (typewriter habit)
- Using straight quotes instead of curly quotes
- Underlining for emphasis (use bold or italic)
- Multiple hyphens instead of proper dashes
- Fake small caps (reduced regular capitals)
- Times New Roman or Arial as font choice
- Default line spacing (usually too tight)
- Margins of exactly one inch (usually too small)
- Centered body text or long passages
- Multiple exclamation points or question marks

**Software-Specific Pitfalls:**
- Not enabling kerning in design software
- Using default "single line" spacing in word processors
- Forgetting to embed fonts in PDFs
- Not testing web fonts across browsers and devices
- Relying on automatic hyphenation without review

---

## Implementation Guidelines

When applying these rules in generated content or recommendations:

1. **Prioritize readability**: All rules serve the goal of better communication
2. **Context matters**: Adjust recommendations based on medium (print vs. web vs. email)
3. **Be specific**: Provide exact measurements and percentages when possible
4. **Explain reasoning**: Help users understand why rules improve typography
5. **Offer alternatives**: When ideal solutions aren't possible, suggest best available options
6. **Consider constraints**: Account for technical limitations, budget, and software capabilities

**When generating typography advice:**
- Always mention the core principle: body text quality determines overall document quality
- Provide specific, measurable guidelines rather than vague suggestions
- Explain the reader benefit of each recommendation
- Acknowledge when compromises are necessary
- Suggest progressive improvement paths for beginners

This guide distills decades of typographic knowledge into actionable, specific rules that consistently improve document quality and readability across all media types.
