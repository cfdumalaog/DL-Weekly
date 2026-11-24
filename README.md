# 🧠 Deep Learning Weekly

**Your curated digest of everything that happened in deep learning — every week.**

## About

Deep Learning Weekly is an open-source repository that tracks and summarizes the most important developments in deep learning research, tools, frameworks, and industry announcements. Each week's summary is published as a Markdown file in `archives/`.

## What We Cover

- **Research Papers** — New arXiv preprints, conference acceptances, and breakthroughs
- **Model Releases** — New models, architectures, and fine-tuned variants
- **Frameworks & Tools** — Updates to PyTorch, JAX, TensorFlow, Hugging Face, LangChain, etc.
- **Industry News** — Company announcements, funding rounds, product launches
- **Datasets** — New publicly available datasets and benchmarks
- **Tutorials & Courses** — Notable educational content and workshops

## Repo Structure

```
deep-learning-weekly/
├── README.md                  # This file
├── archives/                  # Weekly summary Markdown files
│   ├── 2026-W47.md            # Week of November 16, 2026
│   └── ...
├── _templates/
│   └── weekly-summary.md      # Template for new weekly summaries
├── scripts/
│   └── collect_news.py        # Semi-automated news collection helper
└── .github/
    └── ISSUE_TEMPLATE/
        └── new-weekly.md      # Template for community contributions
```

## How to Contribute

1. **Submit a weekly summary** — Open an issue using the "New Weekly Summary" template, or fork and PR directly.
2. **Suggest topics** — Open a regular issue with links and a brief description.
3. **Improve scripts** — Help automate collection from arXiv, Hugging Face, Hacker News, etc.
4. **Fix & improve** — Grammar, formatting, broken links — all contributions welcome.

## Workflow

1. Each **Monday**, create a new summary from `_templates/weekly-summary.md`
2. Fill in sections with notable events from the past 7 days
3. Save as `archives/YYYY-W##.md` (use ISO week numbering)
4. Open a PR with your summary

## Sources We Monitor

| Source | Type |
|---|---|
| [arXiv cs.LG](https://arxiv.org/list/cs.LG/recent) | Research papers |
| [arXiv cs.AI](https://arxiv.org/list/cs.AI/recent) | AI papers |
| [Hugging Face Daily Papers](https://huggingface.co/papers) | Curated papers |
| [r/MachineLearning](https://www.reddit.com/r/MachineLearning/) | Community discussion |
| [Hacker News](https://news.ycombinator.com/) | Tech news |
| [The Batch (DeepLearning.AI)](https://www.deeplearning.ai/the-batch/) | Curated newsletter |
| [OpenReview](https://openreview.net/) | Peer-reviewed papers |

## Automation

The `scripts/collect_news.py` script helps aggregate headlines from RSS feeds and APIs. Run it with:

```bash
python scripts/collect_news.py --output archives/YYYY-W##.md
```

You'll need to fill in your own API keys for sources that require authentication.

## License

MIT License — feel free to fork, remix, and republish.

## Star History

⭐ If this repo helps you stay up to date, consider giving it a star!
