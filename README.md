# The Enriched Read

Research papers, rebuilt as interactive stories — so beginners actually finish them.

Each paper in the catalog is restructured Veritasium-style: start from the reader's
(wrong) intuition, make them commit to a prediction, then let the real data land.
Concepts are explained in tap-to-expand cards, the story is broken into short acts
with hand-drawn diagrams, and progress is tied to comprehension (concepts unlocked,
suspects cleared) — never to empty streaks.

## Catalog

| Nº | Paper | Field | Time |
|----|-------|-------|------|
| 001 | [The Runaway Universe](catalog/001-runaway-universe.html) — Riess et al. 1998, the accelerating universe | 🔭 astronomy | ~25 min |

`index.html` mirrors the latest entry for easy hosting.

## Principles

- **Misconception first.** Every read opens with what a smart person would wrongly expect.
- **Commit before reveal.** Predictions are tapped, not skimmed — being wrong is the hook.
- **One authored level, adaptive in practice.** Prerequisites are inline expandable cards; readers self-select depth.
- **Intelligence offline, lookups at runtime.** Enrichment is generated once per paper; the reading experience is static and instant.
- **No junk dopamine.** No streaks, no confetti. The reward is always a resolved conceptual tension.

## Running locally

Any static server works:

```bash
python3 -m http.server 8642
```

Then open `http://localhost:8642/`.
