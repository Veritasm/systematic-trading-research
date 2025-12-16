# systematic-trading-research

🔹 WEEK 1 — BUILD RESEARCH DISCIPLINE
Day 1 — Pick ONE Strategy & Extract the Idea

Book use: Open the time-series momentum / trend-following chapter

Tasks

Read only enough to answer:

What is the signal?

What is the holding period?

What market behavior is assumed?

Do not run code

Deliverable
research/strategy_0.md

Strategy description (plain English)

Economic intuition

5–10 assumptions

✅ If you can’t list assumptions → stop.

Day 2 — Own the Data Layer

Book use: Skim data ingestion chapters only for patterns

Tasks

Write your own:

price loader

return calculator

Enforce:

datetime index

no forward-looking data

Deliverable
data/loader.py

Day 3 — Build the Signal (No PnL)

Book use: Re-read only the signal definition

Tasks

Implement signal calculation only

Normalize signal (z-score / rank)

No backtest yet

Deliverable
signals/momentum.py

Day 4 — Signal Sanity Checks

Book use: Ignore

Tasks

Check:

distribution

stability

randomization test

Shift signal by 1 day

Deliverable
research/signal_checks.ipynb

Day 5 — Minimal Backtest Engine

Book use: Look at backtest logic with skepticism

Tasks

Write explicit logic:

signal → position

position → PnL

Add:

transaction cost

execution delay

Deliverable
backtest/engine.py

Day 6 — Performance Metrics That Matter

Book use: Ignore fancy metrics

Tasks

Implement:

Sharpe (correct)

Max drawdown

Turnover

Vol targeting

Deliverable
backtest/metrics.py

Day 7 — First Strategy Autopsy

Book use: None

Tasks

Write a rejection-style critique:

Where it breaks

What regime it depends on

Why it might be fake alpha

Deliverable
research/critique_v1.md

🔹 WEEK 2 — REALISM & DEPTH
Day 8 — Robustness & Overfitting

Book use: None

Tasks

Vary:

lookback windows

thresholds

Walk-forward split

Deliverable
research/robustness.ipynb

Day 9 — Portfolio Thinking

Book use: Optional reference

Tasks

Extend to 2–3 assets

Add:

position caps

cash constraint

Deliverable
backtest/portfolio.py

Day 10 — Execution Reality

Book use: Execution chapter (API orientation only)

Tasks

Paper-trading interface

Slippage + partial fills (simple)

Deliverable
execution/paper.py

Day 11 — Kill It (Professional Review)

Book use: None

Tasks

Write:

“If I were a PM, I would reject this because…”

Deliverable
research/rejection_note.md

Day 12 — Fix ONE Weakness

Book use: None

Tasks

Pick the single biggest flaw

Improve only that

Measure effect

Deliverable
Code + short note

Day 13 — Final Write-Up

Book use: None

Tasks

Write a professional summary:

Strategy

Assumptions

Failure modes

Next steps

Deliverable
research/final_review.md

Day 14 — Reset (This Is Key)

Tasks

Delete strategy-specific code

Keep framework

Pick next idea

This proves you learned process, not tricks.

🎯 HOW TO USE THE BOOK (FINAL RULE)

The book is reference material

You never “finish” it

You extract ideas, not code

If you follow this plan correctly:

Most strategies will die

Your thinking will improve fast

You’ll start to sound like a real systematic trader

Next step (do this now)

Reply with:

“I will start Day 1 with time-series momentum.”

Then I’ll tell you exactly what to extract from that chapter and what to ignore line by line.