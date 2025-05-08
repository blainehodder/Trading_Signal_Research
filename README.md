# Trading Signal Research — Commodity Markets

This repository contains applied research projects for building quantitative signals in commodity trading — focused on physical oil market spreads, fundamentals, and flow-driven dislocations. Models prioritize signal generation, not price prediction, and are designed with real-world risk and execution constraints in mind.

## Active Projects

### • Brent-WTI Spread Signal
> Regression and classification models for predicting directional pressure in the Brent-WTI spread. Includes lag features, volatility, moving averages, and exploratory fundamental factors.

### • Crack Spread Signal (3-2-1 and others)
> Early stage signal models for refining margin spreads. Testing momentum, volatility, and flow-based predictors with rolling backtests and directional labels.

### • North American Grades Signal
> Multi-grade analysis including WCS (Hardisty and USGC), SYN, UHC, MEH, Midland/Cushing WTI, etc. Focused on differential modeling using storage, apportionment, refinery runs, pipe and freight dislocations etc.

### • NLP Sentiment Signal (Coming Soon)
> Natural language processing pipeline to extract directional sentiment from oil-related headlines and assess impact on spreads and flat price.

---

## Methodology

- Time Series CV for small data validation
- Signal classification models (XGBoost, Logistic Regression)
- Feature selection with domain-driven inputs
- Backtesting with rolling out-of-sample evaluation
- VaR, hit rate, Sharpe, and drawdown reporting

---

## Goals

- Replace naive regression with probabilistic signal generation
- Build a robust, explainable signal portfolio
- Bridge physical market knowledge with machine learning tools
- Publish models of public data for front-office quant strategists, PMs or dresearchers 

---

## Notes

This repo reflects *real commodity trading research*, not general ML experimentation. Models are deliberately scoped around tradeable signals, not overfit predictions.

---

## Contact

- LinkedIn: [blainehodder](https://www.linkedin.com/in/blainehodder/)
- GitHub: [@blainehodder](https://github.com/blainehodder)
