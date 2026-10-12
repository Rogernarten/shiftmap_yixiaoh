# Shiftmap — Assignment 1: Accelerated Prototyping

25 landing pages for one idea, plus a gallery (`index.html`) that tells the story
from wide exploration (v01–v12) to narrowing (v13–v19) to a final choice (v20–v25).

## The idea
Shiftmap is a (fictional) country-of-origin research tool. A sourcing team asks one
question in plain language; Shiftmap lines up their sourcing records with industry
import records and returns a landscape report for a category.

## Who the page is for
Sourcing and category managers at apparel / consumer-goods brands who decide which
countries and vendors to buy from, under tariff and freight pressure.

## What a visitor should get
For the sample category, a visitor understands within seconds:
1. where it is made today (country-of-origin mix),
2. how that compares with the industry's import mix,
3. which direction to shift volume, and why,
and that Shiftmap can do this for their own category (CTA: request a report).

## Shared content (every version uses the same facts)
Hero · current COO mix · industry comparison · recommended shift · how it works · CTA ·
fictional-product disclaimer.

Sample: **Northfold Apparel — Women's knit sweaters, HTS 6110.20, last 12 months.**

| Origin | Northfold mix | Industry import mix | Gap | After shift |
|---|---|---|---|---|
| China (CN) | 52% | 27% | +25 | 32% |
| Vietnam (VN) | 18% | 31% | −13 | 30% |
| Bangladesh (BD) | 12% | 16% | −4 | 12% |
| Cambodia (KH) | 8% | 12% | −4 | 16% |
| Other | 10% | 14% | −4 | 10% |

By origin (Northfold, last 12 months; industry = US imports of HTS 6110.20):

| Origin | Units | Sales | Freight/u (vs peers) | Net margin | Top vendor | Industry imports |
|---|---|---|---|---|---|---|
| CN | 738K | ≈$15.5M | $2.05 ($1.38) | 1.8% | Jade Harbor Apparel (61%) | $1.13B |
| VN | 256K | ≈$5.4M | $1.52 ($1.05) | 6.2% | Lotus Bay Knitwear (74%) | $1.30B |
| BD | 170K | ≈$3.6M | $1.71 ($1.20) | 4.0% | Delta Loom Industries (100%) | $0.67B |
| KH | 114K | ≈$2.4M | $1.48 ($1.10) | 6.9% | Angkor Thread Ltd. (100%) | $0.50B |
| Other | 142K | ≈$3.0M | $1.90 | 2.5% | — | $0.59B |

Totals: sales $29.8M, 1.42M units, net margin 3.3% (peers 7.4%), freight/u $1.85
(peers $1.21), US imports $4.2B. Leads: Red River Garment Co. (VN, $86M), Saigon Pine
Knit (VN, $54M), Mekong Stitch Works (KH, $38M).

Shift: move 20 pts out of China — CN→VN 12 pts, CN→KH 8 pts. Reasons: Vietnam is
already the industry's #1 origin; 14 vendors in VN/KH already ship this code to US
brands; est. landed cost per unit about −5%.

## Constraints
- Plain HTML + CSS, optional vanilla JS. No frameworks, packages, build step,
  external APIs, CDNs or data storage. System font stacks only (ask before any web font).
- Each version lives in `vNN/index.html`, self-contained (inline CSS/JS), with a
  visible "← Gallery" link to `../`, and works at phone width.
- Everything is fictional: never use real companies, brands, vendors, internal tool
  names or real figures.

## How we work
- The user directs. One version per round; never batch-generate versions.
- Every version shows the COO mix and the shift **visually** (map or chart) and keeps
  copy minimal: a business reader should get it at a glance (user feedback on v01).
- v01–v12: each a radically different direction (layout, metaphor, era, tone,
  audience). Color or font swaps don't count. Prefer trade/apparel-specific
  metaphors over generic SaaS looks — 20+ designs must be unique across the class.
- After each version: add its gallery card (what changed + why), log the round in
  `process.md` (asked / built / pushed back / decided), commit as `vNN: <direction>`.
