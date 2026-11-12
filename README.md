# Gas Spikes and Nonce Gaps

## Description
How do nonce gaps cluster when gas is low and when gas is high? This analysis shows how clusters of nonce gaps look like relevant to gas price in a 7-day dataset, November 2 - November 8, 2026 PHT. 

## 1. Parts / Statements

**1. Daily Gas Spike**
<br>
Average gas price each day in Gwei. Shows the trend of gas price daily; when gas was the highest and lowest.

**2. Daily Nonce Gaps**
<br>
Total missing nonces each day. Shows the days when transaction gaps were the highest and lowest. 

## 2. Workflow

1. Explored tables on Dune, picked the block range for last 7 days (Nov 2 - Nov 8, 2026).
2. Queried dataset for 2 parts (assisted with WizardsCamp and AI for automation of queries).
3. Made visualizations and built final dashboard.

## 3. Files

- **README.md** - Project overview.
- **Dune Queries and Results**:
  - Data Source: https://dune.com/queries/9110148?sidebar=none
  - Part 1 - Daily Gas Spike: https://dune.com/queries/9112189/13163487?sidebar=none
  - Part 2 - Daily Nonce Gaps: https://dune.com/queries/9112374/13163669
- **Dune Dashboard**: https://dune.com/pameladeerana/gas-spikes-vs-nonce-gaps
 
## 4. Data Coverage

- **Date:** November 2 - November 8, 2026 PHT
- **Blocktime Range:** 2026-11-01 16:00:00 to 2026-11-08 16:00:00 UTC (from query_9110148) 

## 5. Tools

- Dune Analytics
- WizardCamp
- LLM Meta AI

## Author

Pamela Dee Elegio Rana
