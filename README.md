# Private Credit BDC Analytics Suite

A client-side analytics suite for parsing, standardizing, and analyzing SEC Schedule of Investments (SOI) filings across flagship Private Credit Business Development Companies (BDCs).

## Live Demo
Access the web application directly: [Live Dashboard](https://grishmagarg.github.io/bdc-credit-analytics/)

## Key Features
- **Automated Entity Normalization:** Matches borrowers across disparate GP filing conventions using normalized investee keys.
- **Pairwise Overlap Matrices:** Evaluates bidirectional portfolio overlap (by Fair Value and position count) across 10+ mega-cap private credit funds.
- **Level 3 Debt Surveillance:** Aggregates stressed debt exposure as a cumulative % of total assets across custom valuation bands (<=70%, <=80%, <=90% of cost).
- **Cross-Manager Pricing Divergence:** Tracks quarterly Fair Value-to-Par trajectories for shared borrowers to detect credit deterioration and mark variance.

## Sample Data
Sample multi-quarter filing datasets for testing are available in the `/data` directory:
- `BDC_SOI_Input_2026-03-31_10Funds.xlsx`
- `BDC_SOI_Input_2026-06-30_10Funds.xlsx`
