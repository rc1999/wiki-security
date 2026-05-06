# Security Wiki

Cybersecurity, threat intelligence, crypto security, nation-state attacks, and defensive security operations

## Structure

```
├── SCHEMA.md           # Conventions, tag taxonomy, domain rules
├── index.md            # Catalog of all pages
├── log.md              # Chronological action log (append-only)
├── raw/                # Immutable source material
│   ├── articles/       # Web articles, clippings
│   ├── papers/         # PDFs, datasheets
│   ├── transcripts/    # Meeting notes, interviews
│   └── assets/         # Images, diagrams
├── entities/           # People, products, brands, models
├── concepts/           # Topics, techniques, phenomena
├── comparisons/        # Side-by-side analyses
└── queries/            # Filed research results
```

## How to Use

1. **Ingest sources** — add articles, papers, notes to `raw/`
2. **Build pages** — create entity/concept pages from sources
3. **Cross-reference** — link pages with `[[wikilinks]]`
4. **Query** — ask questions, file valuable answers
5. **Lint** — run health checks to keep the wiki clean

## Initializing Git

```bash
cd /root/.openclaw/workspace/wikis/security
git remote add origin git@github.com:YOUR_USERNAME/wiki-security.git
git push -u origin main
```

Created: 2026-05-06
