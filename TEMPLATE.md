```yaml
---
title: "Title Here"
source: "Author Name, *Book Title* (Year)"
date: "YYYY-MM-DD"
version: "0.1"
description: |
  Brief description of the document's contents and purpose. This template
  follows the house style guide for typography notes.
---
```

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

# Main Title

Brief introduction paragraph that sets context for the document. This paragraph is flush left after the heading.

This second paragraph demonstrates the 1em indentation that characterizes our house style, creating a smooth flow of text without vertical gaps.

## Major Section

Key principle or concept statement goes here, often in a paragraph that introduces the section's themes.

* **First principle**: Clear explanation with proper punctuation at the end.
* **Second principle**: Another key point, maintaining consistent formatting.
* **Third principle**: Additional guidance following house style rules.

## Another Section

Content continues with proper indentation and formatting throughout the document.

### Subsection if Needed

Further detail with maintained consistency in style and structure.

## Change Log

- **0.1** (YYYY-MM-DD) – Initial draft