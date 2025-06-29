# House Style Guide

This document defines the typographic and structural standards for all documents in this repository.

## Document Structure

### 1. YAML Frontmatter

Every document begins with standardized YAML metadata:

```yaml
---
title: "Document Title in Title Case"
source: "Author Name, *Book Title in Italics* (Edition/Year)"
date: "YYYY-MM-DD"
version: "X.Y"
description: |
  Multi-line description using proper indentation. First line explains
  the document's purpose. Second line adds context or scope details.
---
```

### 2. CSS Typography Block

Immediately after frontmatter, include the standard typography CSS:

```html
<style>
/* Typography: Beautiful paragraph indentation following best practices */
p {
  text-indent: 1em;
  margin-top: 0;
  margin-bottom: 0;
  line-height: 1.4;
}

/* First paragraph after headings should be flush left */
h1 + p, h2 + p, h3 + p, h4 + p, h5 + p, h6 + p,
hr + p, blockquote + p, ul + p, ol + p, pre + p,
table + p, .yaml + p, style + p {
  text-indent: 0;
}

/* Reset indentation for list items */
li > p:first-child {
  text-indent: 0;
}

/* Maintain spacing for readability in lists and blockquotes */
ul, ol {
  margin: 1em 0;
}

blockquote {
  margin: 1em 2em;
}
</style>
```

### 3. Document Sections

Use this hierarchy:

1. **Title** (H1) – Document subject
2. **Major Sections** (H2) – Primary divisions
3. **Subsections** (H3) – Secondary topics
4. **Details** (H4) – When needed

## Typography Standards

### Punctuation

- **Quotation marks**: Always use curly quotes (" " ' ')
- **Dashes**: 
  - Em dash (—) for breaks in thought—like this
  - En dash (–) for ranges (pages 15–30)
  - Hyphen (-) for compound words
- **Spaces**: Single space after periods
- **Ellipses**: Use proper ellipsis character (…)

### Emphasis

- **Bold** (`**text**`): For key concepts, rules, and principles
- **Italic** (`*text*`): For emphasis, book titles, foreign terms
- Never combine bold and italic

### Lists

- Use asterisk (`*`) for bullets
- Indent with 2 spaces
- End all list items with periods
- For sub-items, maintain 2-space indentation

### Technical Formatting

- Use backticks for:
  - Measurements: `10 pt`, `1.5 em`
  - Technical terms: `kerning`, `x-height`
  - Examples: `M/4` spacing
- Not for:
  - Font names (use regular text)
  - Simple numbers

## Content Standards

### Citations

When citing sources:
- Inline: [Author, page number]
- Or: [cite: page number] when author is clear
- Keep citations brief and unobtrusive

### Examples

- Use concrete examples
- Keep examples brief
- Format consistently with backticks when technical

### Horizontal Rules

Use sparingly:
- Between major topic shifts only
- Not between every section
- Three hyphens: `---`

## Version Control

### Version Numbers

Use semantic versioning:
- `0.1` – Initial draft
- `0.2` – Major additions
- `1.0` – Complete and reviewed
- `1.1` – Minor updates

### Change Log

Include at document end:

```markdown
## Change Log

- **1.0** (2024-06-28) – Initial complete version
- **1.1** (2024-07-15) – Added examples, fixed typos
```

## File Naming

- Lowercase only
- No spaces (use hyphens)
- Descriptive names
- `.md` extension

## Quality Checklist

Before finalizing any document:

- [ ] YAML frontmatter complete and correct
- [ ] CSS typography block included
- [ ] Consistent emphasis usage
- [ ] Proper punctuation throughout
- [ ] Lists properly formatted
- [ ] Technical terms in backticks
- [ ] Version number updated
- [ ] Date reflects last edit