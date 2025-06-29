# Nathan's Typography Notes

A curated collection of distilled typography wisdom from master typographers, formatted for both human reading and notes, and also agentic ingestion. 

## Contents

- **[Ambrose & Harris](ambroseharris.md)** – Gavin Ambrose and Paul Harris's *The Fundamentals of Typography*
- **[Bringhurst](bringhurst.md)** – Robert Bringhurst's *The Elements of Typographic Style*
- **[Butterick](butterick.md)** – Matthew Butterick's *Practical Typography*
- **[Hochuli](hochuli.md)** – Jost Hochuli's *Detail in Typography*
- **[Ruder](ruder.md)** – Emil Ruder's *Typography: A Manual of Design*

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

## Bibliography

### Primary Sources

- Ambrose, Gavin, and Paul Harris. *The Fundamentals of Typography*. AVA Publishing, 2006.
- Bringhurst, Robert. *The Elements of Typographic Style*. 4th ed., Hartley & Marks, 2012.
- Butterick, Matthew. *Practical Typography*. 2nd ed., 2018. https://practicaltypography.com
- Hochuli, Jost. *Detail in Typography*. Hyphen Press, 2008.
- Ruder, Emil. *Typography: A Manual of Design*. 7th ed., Niggli, 2009.

### Additional Resources

- **[STYLE.md](STYLE.md)** – Typography style guide for this repository
- **[TEMPLATE.md](TEMPLATE.md)** – Template for adding new typography notes
