# Contributing to Deep Learning Weekly

## Submitting a Weekly Summary

### Option 1: Open an Issue

1. Go to **Issues** → **New issue** → **New Weekly Summary**
2. Fill in the template with the week's notable events
3. A maintainer will convert it to a file in `archives/`

### Option 2: Fork and PR

1. Fork the repo
2. Copy `_templates/weekly-summary.md` to `archives/YYYY-W##.md`
3. Fill in each section
4. Open a PR with your summary

## Writing Guidelines

- **Be concise** — Each entry should be 1-2 sentences max
- **Link everything** — Include arXiv links, GitHub repos, official blog posts
- **Explain why it matters** — Don't just list; add context for readers
- **Stay neutral** — Report facts, not opinions (unless marked as opinion)
- **Use the template** — Follow the structure in `_templates/weekly-summary.md`

## Using the Collection Script

```bash
cd scripts
pip install -r requirements.txt
python collect_news.py --output ../archives/2026-W47.md
```

This auto-fetches RSS feeds and generates a draft. Review and curate before committing.

## Code of Conduct

Be respectful, constructive, and inclusive. We welcome contributors of all backgrounds and experience levels.
