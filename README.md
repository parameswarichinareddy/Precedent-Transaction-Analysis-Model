# Precedent Transaction Analysis Model

An investment-banking-style Precedent Transaction Analysis (PTA) valuation model built in Excel using a transaction database, target financials, capitalization bridge, transaction multiples, premium analysis, implied valuation, sensitivity analysis, and a football field.

## Model

- `models/Baker_Hughes_Precedent_Transactions_Analysis_Model.xlsx` — Baker Hughes PTA model

## Valuation workflow

1. **Dashboard** — key transaction and valuation outputs
2. **Transaction Overview** — selected deal context and transaction metrics
3. **Target Financials** — historical / reference financial data used for valuation
4. **Target Capitalization** — enterprise-value to equity-value bridge and capitalization items
5. **Precedent Transactions** — comparable M&A transaction set and source data
6. **Transaction Multiples** — EV / Revenue, EV / EBITDA and related trading metrics
7. **Premium Analysis** — transaction premiums and buyer-paid premium benchmarking
8. **PTA Valuation** — selected precedent multiples applied to the target
9. **Sensitivity Analysis** — valuation sensitivity to key multiple assumptions
10. **Football Field** — visual valuation range summary
11. **Transaction Screening** — transaction inclusion / screening logic
12. **Sources & Checks** — source documentation and model-control checks

## What this demonstrates

- Precedent transaction screening and benchmarking
- Enterprise value and equity value bridge
- LTM / TTM operating metrics
- Transaction multiple analysis
- EV / Revenue and EV / EBITDA valuation
- Premium analysis
- Implied target valuation
- Sensitivity analysis
- Football-field valuation presentation
- Source tracking and model audit checks

## Repository structure

```text
.
├── models/
│   └── Baker_Hughes_Precedent_Transactions_Analysis_Model.xlsx
├── .github/
│   └── workflows/
│       └── validate-pta.yml
└── README.md
```

## Automated quality control

GitHub Actions checks that the workbook is present, can be opened as an `.xlsx` file, contains the expected core PTA worksheets, and does not contain obvious Excel error literals such as `#REF!`, `#DIV/0!`, or `#VALUE!`.

## Purpose

This repository is intended as a financial-modelling and investment-banking portfolio project demonstrating practical precedent transaction analysis, M&A valuation methodology, transaction benchmarking, documentation, and model-quality control.

> **Disclaimer:** This model is for educational and portfolio purposes only and is not investment advice. Transaction data, assumptions, market inputs, and valuation outputs are time-sensitive and should be independently verified before real-world use.
