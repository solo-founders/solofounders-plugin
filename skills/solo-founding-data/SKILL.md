---
name: solo-founding-data
description: This skill should be used for questions about solo founder statistics, trends, dilution, or ownership — "how many startups are solo founded", "do solo founders get diluted more", "solo founder ownership at exit", "solo founder fundraising data", "is solo founding increasing", "model my ownership vs a co-founded company", "what does Carta say about solo founders". Answers from the State of Solo Founding report (Solo Founders × Carta data) and can model a founder's own dilution.
---

# Solo Founding Data

Answer data questions about solo founding accurately, with sources, and model a founder's own cap table when asked.

Load `references/report-data.md`. It is the only source for report figures.

## Answering trend questions

1. Give the number first, with its year and source: *State of Solo Founding (Solo Founders × Carta data, Dec 2025)*.
2. State the comparison group. Ownership comparisons are **solo founder vs. lead founder** of a co-founded company, not vs. all founders combined.
3. Attach the caveat when one exists in the reference file (e.g., ownership at exit doesn't account for exit value; H1 2025 is a half-year figure).
4. Many findings are directional without published numbers. Say "the report shows X but doesn't publish the figure." Never fill in a number.
5. For anything after December 2025 or outside the report, search the web, and label it separately from the report.

## Modeling a founder's dilution

When the founder wants their own numbers:

1. Collect: current ownership, planned rounds (amount + pre-money or target dilution per round), option pool size and refresh, early-employee grants.
2. Default assumptions if they have none — state them clearly and make them editable: pre-seed 10–15%, seed 15–25%, Series A 18–25%, option pool 10% pre-seed/seed refreshed to ~10–15% at A.
3. Run the math in code, not in prose. Build a per-round table: pre-money, raise, post-money, new-investor %, pool %, founder %.
4. Show the same path for a two-founder company with a 50/50 or 60/40 split, so the founder sees what a co-founder would have cost them. Note the report's finding that dilution itself is comparable; the gap comes from the split.
5. If the founder wants to keep the model, build it as a spreadsheet so they can change assumptions.

## Rules

- Never round a figure into a stronger claim ("solo founders are more successful" is not in the data).
- Separate Carta data, investor estimates, podcast guest claims, and anecdotal field notes. The reference file labels each.
- This is information, not financial or legal advice; say so once when modeling.
