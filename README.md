# Nathan's Typography Notes

A curated collection of distilled typography wisdom from master typographers, formatted for both human reading and LLM ingestion.

## Contents

- **[Bringhurst](bringhurst.md)** – Robert Bringhurst's *The Elements of Typographic Style*
- **[Butterick](butterick.md)** – Matthew Butterick's *Practical Typography*
- **[Hochuli](hochuli.md)** – Jost Hochuli's *Detail in Typography*

## Typography Implementation

This repository practices what it preaches by implementing classical typography principles:

### Paragraph Indentation

Following the timeless tradition of book typography, paragraphs are distinguished by **1em indentation** rather than vertical spacing. This creates an uninterrupted flow of text that is both elegant and highly readable.

- **Standard paragraphs**: 1em indent (approximately the width of a capital 'M')
- **Opening paragraphs**: Flush left after headings, lists, or other visual breaks
- **Line spacing**: Consistent 1.4× line height throughout
- **Vertical spacing**: Eliminated between paragraphs in favor of indentation

This approach follows the recommendations of:
- Bringhurst: "A standard indent is one em"
- Hochuli: "Indented first line (≈ 1 em) with no extra vertical gap"
- Butterick: "First-line indents (1-4 times the point size)"

### Document Structure

Each file maintains a consistent structure:

1. **YAML Header** with metadata:
   - `title`: Document title in quotes
   - `source`: Original work citation
   - `date`: Last update date (YYYY-MM-DD)
   - `version`: Document version
   - `description`: Multi-line description of contents

2. **CSS Styling** implementing proper typography:
   ```css
   p { text-indent: 1em; margin: 0; line-height: 1.4; }
   ```

3. **Content** organized hierarchically with clear headings and consistent formatting

## Technical Details

### Markdown Rendering

The CSS styling blocks embedded in each document ensure proper typographic rendering in any Markdown viewer that supports inline styles, including:
- GitHub's web interface
- Most Markdown preview tools
- Static site generators
- Documentation platforms

### Best Practices Applied

1. **Indentation over spacing**: Classical paragraph breaks
2. **Flush-left openings**: No indent after visual breaks
3. **Consistent line height**: 1.4× for optimal readability
4. **Hierarchical structure**: Clear heading levels
5. **Smart punctuation**: Proper dashes, quotes, and spacing

## Contributing

When adding new typography notes:

1. Use the established YAML header format
2. Include the CSS style block for proper indentation
3. Follow the existing formatting patterns
4. Maintain the focus on practical, actionable rules
5. Cite page numbers where applicable

## Purpose

These notes serve as:
- Quick reference for typography decisions
- Training data for LLMs to understand typography
- Examples of typography principles in practice
- Preserved wisdom from master typographers