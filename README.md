# Research Paper

**Author:** Abdoulaye Gaye  
**Company:** Amundi Asset Management  
**Team:** Smart Beta and Factor Investing (Amundi ETF)  
**Date:** June 2024  

## Title  
**How Do Investment Factors Interact with Each Other and How Are They Influenced by Economic Conditions?**

## Summary  
This thesis investigates the interaction between investment style factors (Value, Momentum, Quality, Size, and Low Volatility) and how macroeconomic cycles (recession, slowdown, recovery, and growth) influence their performance. The study is based on MSCI factor indices in the US, Europe, and Japan, and draws conclusions on how these strategies behave under different economic regimes.

## Context  
This research was conducted during a one-year apprenticeship within the Engineering & Investment Solutions team at Amundi ETF, following Amundi’s acquisition of Lyxor. The role involved quantitative analysis, tool development, and participation in team research projects on factor investing.

## Technical Contributions  
- Developed Python scripts to extract ETF compositions via REST/SOAP APIs using Amundi’s internal platform, ALTO.  
- Built a Streamlit dashboard to standardize output across different ETF replication types (physical, synthetic, sampled).  
- Rebuilt Fama-French factor portfolios (SMB, HML, CMA, RMW) with US equity market data and computed daily/monthly returns.  
- Benchmarked internal factor performance against data from the Kenneth R. French Data Library.  

## Research Focus  
- Computed excess returns by removing market effects using CAPM-style regressions.  
- Conducted performance attribution across economic cycles using macro regime definitions.  
- Applied statistical methods: ADF tests for stationarity, MS-AR (Markov Switching AutoRegressive) models for regime transitions.  
- Inspired by and partially replicated results from the academic paper: "Value and Momentum Everywhere" (Asness, Moskowitz, Pedersen).

## Tools and Technologies  
- Python (pandas, numpy, statsmodels, matplotlib, Streamlit)  
- Excel  
- Bloomberg Terminal  

## Key Findings  
- In recessions, Quality and Low Volatility factors tend to outperform, while Value and Momentum underperform.  
- In recoveries, Value and Size show strong positive returns across all regions.  
- The US market exhibits more stable factor performance; Europe and Japan show greater regime sensitivity.  
- Negative correlation is observed between Value and Growth, while Quality shows mixed correlations depending on the region.

## Acknowledgments  
Special thanks to my apprenticeship supervisor and team members for their support, training, and technical mentorship throughout this experience.

## Disclaimer  
This project is based on public datasets and personal development work. Proprietary tools and confidential data from Amundi Asset Management are not included in this repository.
