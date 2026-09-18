# econ3916-lab01-data-portfolio
Introductory data analysis using Big Mac Index
The Data Portfolio — Big Mac Index Analysis

Objective: This project analyzes The Economist's Big Mac Index to assess currency valuation and purchasing power parity (PPP) across 57 countries and 45 time periods (2000–2026), identifying systematic patterns of over- and undervaluation in global exchange rates.

Methodology:

Sourced raw Big Mac Index data (57 countries, 45 periods spanning 2000-04 to 2026-07) directly from The Economist's public GitHub repository
Computed implied PPP exchange rates and percentage valuation (over/undervaluation) relative to actual market exchange rates
Classified the dataset's structural dimensions — distinguishing cross-sectional (54-country July 2024 snapshot), time-series, and panel components
Conducted a missing data audit, diagnosing Russia's exit from the index as Missing Not At Random (MNAR) given its geopolitical driver
Built visualizations: a bar chart of cross-sectional currency valuations and a time series comparison tracking valuation trends across countries

Key Findings:

The Swiss franc shows persistent overvaluation, registering at +41.8% in the July 2024 cross-section
The Japanese yen has remained undervalued on average across every decade in the sample, suggesting a structural rather than cyclical mispricing
Together, these results reinforce the Big Mac Index's utility as a simplified but directionally consistent proxy for PPP deviations, while highlighting the importance of accounting for non-random data gaps (e.g., Russia) when interpreting cross-country comparisons
