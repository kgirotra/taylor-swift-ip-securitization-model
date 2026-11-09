# Taylor Swift IP Securitization Model
FIN 418 Financial Modeling · University of Illinois Urbana-Champaign · Fall 2026

A financial model for a hypothetical asset-backed securitization of Taylor Swift's music catalog. An SPV holds her music rights, royalty cash flows service the debt, and equity reverts to the artist when the debt is fully repaid.

## Project Overview
Taylor Swift's music catalog generates predictable royalty income from streaming, vinyl, concerts, merchandise, and licensing. This model structures those cash flows into a securitization, sizing the debt against the catalog's earning power and stress-testing repayment across three operating cases (Base, Good, Bad).

## Model Structure
| Sheet | Description |
|---|---|
| Assumptions | Live case switch (1 = Base, 2 = Good, 3 = Bad). Change one cell and every forecast updates. Covers stream growth, vinyl, concerts, merchandise, and licensing, with fixed inputs for distributor fee, pressing cost, and cost of services. |
| Revenues & Capital Structure | Historical revenue (2022–2025), 10-year forecast (2026–2036), debt waterfall, and credit metrics. |

## Key Assumptions
| Input | Value / Approach |
|---|---|
| Forecast period | 2026–2036 |
| Streaming platforms | Spotify, Apple Music, YouTube, YouTube Art Tracks, SoundCloud |
| Vinyl take-home | (Price × (1 − 25% distributor fee) − $8 pressing cost) ÷ price |
| Album cycle | One album every 1.5–2 years, built into 2027 growth rates |
| Licensing rate | 10.97% of recorded music revenue (WMG proxy) |
| Cost of services | 2.5% of revenue |

## Debt Structure
| Parameter | Value |
|---|---|
| Initial debt | $1,105,489,511 |
| Debt / EBIT multiple | 8.75× |
| Maturity | 10 years |
| Fixed interest rate | 7.21% (SOFR 3.71% + spread 3.50%) |
| Repayment | Bullet at maturity |
| Minimum DSCR (Base) | 1.41× |

## Scenario Assumptions
| Scenario | Description |
|---|---|
| Base | Streams fade from −24% to −5% a year by 2029, moderate album lift in 2027 |
| Good | Streams grow with the market, strongest album lift |
| Bad | Current −21% decline continues, smallest album lift |

## Tools Used
Microsoft Excel · Bloomberg Terminal · PowerPoint

## Files
- `Financial_Model.xlsx` — Full model with Assumptions and Revenues & Capital Structure sheets
- `Fin 418 Project - Taylor Swift.pptx` — Team deck

*Hypothetical educational project. Not investment advice.*
