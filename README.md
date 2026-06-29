# anaideas — AI Business Opportunity Intelligence

This repo is the output of a recurring automated research loop that hunts for real, fast-to-revenue AI-leveraged business opportunities — specifically ones that can realistically reach $10k/mo, $50k/mo, or $100k/mo without a 12-month enterprise sales cycle.

It runs on a schedule, treats each run as an incremental update (not a fresh start), and maintains the following files:

- **`opportunities.md`** — every opportunity ever discovered, cumulative, with scores and a $10k/$50k/$100k revenue-tier tag. Source of truth for "what have we found."
- **`validated.md`** — the subset of opportunities backed by real evidence (case studies, sourced pricing, disclosed comparable businesses), separated from speculative/single-source claims.
- **`leaderboard.md`** — top 25 highest-scoring ideas ever generated, ranked, one-line pitch each. Capped at 25; lowest entry drops when a better one is found.
- **`current_best_business.md`** — the single current #1 pick, why it's #1, its revenue tier, and a dated promotion history every time the pick changes.
- **`action_plan.md`** — concrete, dated first-5-steps plan to get the current #1 pick to its first paying customer.
- **`outreach_scripts.md`** — ready-to-use cold email/DM scripts for the current #1 pick's likely first customers. Rewritten whenever the top pick changes.

## How to read this repo
Start with `current_best_business.md` for the single highest-conviction idea right now, then `action_plan.md` if you want to actually go execute it, then `outreach_scripts.md` to start contacting prospects. Check `leaderboard.md` if you want the broader ranked list, and `validated.md` if you want to know which claims have real evidence behind them vs. which are still directional estimates.

## Methodology notes
- Scoring is a 7-dimension composite (startup cost, time to first revenue, competition, scalability ceiling, likelihood of success, AI-leverage, customer acquisition speed) — see the top of `opportunities.md` for the rubric.
- Every claim is marked as either sourced (with a link) or an estimate/directional claim. Sparse evidence is never a reason to skip logging an idea — gaps are noted explicitly so future runs know what to validate next.
- First run: 2026-06-27. Most recent run: 2026-06-29.
