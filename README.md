# FX Macro Event Study Framework

## Overview
A quantitative framework analysing the impact of central bank interventions 
and macro data releases across G10 and Asian currency pairs. Built in Python 
using real market data from 2015 to present.

## Motivation
Central bank intervention and macro data releases are the primary drivers of 
short term FX moves. This project quantifies exactly how different currency 
pairs respond to these events, compares intervention effectiveness across 
different exchange rate regimes, and generates actionable trade signals based 
on historical patterns.

## Currency Pairs Covered
**G10:** EUR/USD, GBP/USD, USD/JPY, AUD/USD  
**Asian:** USD/KRW, USD/SGD, USD/HKD, USD/INR

## Events Studied
- Bank of Japan (BoJ) FX interventions — 2022 and 2024
- Bank of Korea (BOK) interventions — risk-off episodes
- Monetary Authority of Singapore (MAS) policy decisions
- Federal Reserve rate decisions — full 2022-2024 hiking cycle
- Non-Farm Payrolls — beats vs misses

## Key Findings
- BoJ interventions produce the largest immediate price impact due to 
  Japan's $1.2 trillion FX reserves — USD/JPY drops ~2% on average at day 0
- BOK interventions have similar but less persistent impact — Korea's 
  smaller reserve base limits effectiveness
- MAS policy decisions produce minimal event-day volatility due to 
  transparent forward guidance — market pre-positions before announcements
- Fed rate decisions strengthen the dollar immediately but the effect 
  fades within 10 days as markets digest the decision
- NFP surprise impact is regime-dependent — beats had larger dollar impact 
  during the 2022 hiking cycle than after peak rates were confirmed

## Signal Dashboard
A real-time signal generator monitors current market conditions across all 
pairs and flags elevated intervention risk, momentum signals, and central 
bank policy alerts based on historical pattern recognition.

## Tools Used
- Python, Pandas, NumPy, Matplotlib
- yfinance for market data
- Jupyter Notebook

## Context
Built as part of independent study alongside BSc Economics at University 
of Manchester, targeting sell-side FX research and trading roles.
