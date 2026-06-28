# Gold Market Trend Analysis & Price Forecast
**Author:** Daron Nyarko  
**Analysis Period:** October 2024 – February 2025  
**Published to GitHub:** June 2026

---

## Overview

This project is a forward-looking investment memo I built in Python to analyze gold 
price dynamics and develop a short-term price forecast. The analysis was conducted 
between October 2024 and February 2025 — before gold's historic run to $3,000+ — 
and presented a bullish thesis with a 60-day price target of $2,879/oz.

The thesis proved correct. Gold crossed $3,000/oz in early 2025 and has continued 
climbing since, validating the macro and technical signals identified in this analysis.

---
## Background & Inspiration

Gold was the first asset I ever paid close attention to. Before I understood technical 
analysis or macro economics, I noticed something was happening in the gold market — 
prices were moving in ways that seemed tied to what was going on in the world.

It was gold that first taught me how to option trade, and more importantly, how to 
connect political and geopolitical events to investor behavior. Watching how gold 
reacted to the Fed, to wars, to banking stress — that was my introduction to thinking 
like an analyst rather than just a trader.

This project is a formalization of that early curiosity. I wanted to take what I had 
been observing informally and build something rigorous around it — real data, real 
analysis, a documented thesis.

---

## What This Project Covers

- **Macro Trend Analysis** — Gold price history from 2022–2024 annotated with key 
geopolitical and monetary policy events (Ukraine invasion, Fed hike cycle, SVB collapse, 
Fed pivot)
- **Technical Signal Analysis** — 50-day and 200-day moving averages with automated 
Golden Cross and Death Cross detection
- **Price Forecast** — Linear regression model on trailing 120-day momentum with an 
expanding uncertainty band, projecting 60 trading days forward
- **Investment Memo** — Written bullish thesis structured around macro drivers, 
technical confirmation, and key risk factors

---

## Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Scikit-learn)
- Data sourced from Yahoo Finance via `yfinance`
- Jupyter Notebook

---

## Key Findings

- Gold sold off ~21% during the Fed's 2022 rate hike cycle before bottoming at ~$1,620
- A Golden Cross in early 2023 signaled the start of a sustained recovery
- Gold broke out to all-time highs in 2024, advancing ~36% in a single calendar year
- 60-day price target of $2,879/oz was issued in late 2024 — gold subsequently exceeded 
$3,000/oz in early 2025

---

*This analysis was conducted as a personal investment research project and does not 
constitute financial advice.*
