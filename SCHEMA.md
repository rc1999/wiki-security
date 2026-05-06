# Wiki Schema

## Domain
Cybersecurity, threat intelligence, crypto security, nation-state attacks, and defensive security operations

## Conventions
- File names: lowercase, hyphens, no spaces (e.g., `example-page.md`)
- Every wiki page starts with YAML frontmatter (see below)
- Use `[[wikilinks]]` to link between pages (minimum 2 outbound links per page)
- When updating a page, always bump the `updated` date
- Every new page must be added to `index.md` under the correct section
- Every action must be appended to `log.md`
- **Provenance markers:** On pages synthesizing 3+ sources, append `^[raw/articles/source-file.md]`
  at the end of paragraphs whose claims come from a specific source.

## Frontmatter
```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | summary
tags: [from taxonomy below]
sources: [raw/articles/source-name.md]
confidence: high | medium | low
contested: true
contradictions: [other-page-slug]
---
```

## Tag Taxonomy
- security
- threat-intel
- crypto
- north-korea
- lazarus
- hack
- social-engineering
- defense
- infosec
- blockchain

Rule: every tag on a page must appear in this taxonomy. Add new tags here first.

## Page Thresholds
- **Create a page** when an entity/concept appears in 2+ sources OR is central to one source
- **Add to existing page** when a source mentions something already covered
- **DON'T create a page** for passing mentions or things outside the domain
- **Split a page** when it exceeds ~200 lines — break into sub-topics with cross-links
- **Archive a page** when superseded — move to `_archive/`, remove from index

## Entity Pages
One page per notable entity. Include overview, key facts, relationships, source references.

## Concept Pages
One page per concept. Include definition, current state, open questions, related concepts.

## Comparison Pages
Side-by-side analyses. Include dimensions (table format), verdict, sources.

## Update Policy
When new information conflicts:
1. Check dates — newer sources generally supersede older ones
2. If genuinely contradictory, note both positions with dates and sources
3. Mark `contradictions: [page-name]` in frontmatter
4. Flag for user review in the lint report
