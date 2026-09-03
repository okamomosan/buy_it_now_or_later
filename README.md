# Buy It Now Or Later?

This repository contains the replication materials for the paper:

**"Buy It Now Or Later? An Experimental Study of Second-price Auction with Buy Price"**

Toshihiro Tsuchihashi, Toshiji Kawagoe, and Tomohisa Okada

---

## Structure of the Repository

- `run_all.Rmd`  
  Main analysis file. Running this file reproduces the main tables and figures reported in the paper.

- `run_all.html`  
  Rendered output of the R Markdown file for quick inspection.

- `data/`  
  Contains the experimental data used in the analysis.

- `instructions.pdf`  
  Contains the experimental instructions shown to participants.

---

## How to Reproduce the Results

1. Open `run_all.Rmd` in RStudio.

2. Install the required R packages if needed.

3. Run the entire file (Knit).

The main tables and figures reported in the paper can be reproduced from this file.

---

## Experimental Design

The experiment studies buyout decisions in second-price auctions with a buyout option.

The experimental design varies:

- the number of bidders,
- the rate at which bidders' valuations decline over time,
- and uncertainty regarding these factors.

The experiment also collects measures related to participants' risk preferences, time preferences, and cognitive reasoning.

---

## Key Experimental Variables

- `N`: Number of bidders in the auction.
- `delta`: Rate of decay in the bidder's valuation.
- `private_value`: Bidder's private valuation.
- `buyout`: Indicator for whether the bidder exercised the buyout option.
- `bid`: Bid submitted in the second-price auction.
- `CRT`: Measure of cognitive reflection.

Additional variables and their definitions are documented in the analysis file.

---

## Notes

- The experiment was conducted using incentivized decisions.
- Participants completed experimental instructions and comprehension checks before making decisions.
- The repository contains materials necessary to reproduce the empirical analyses reported in the paper.
- For details of the theoretical predictions and experimental design, see the main manuscript.

---

## Paper

Tsuchihashi, Toshihiro, Toshiji Kawagoe, and Tomohisa Okada.  
**"Buy It Now Or Later? An Experimental Study of Second-price Auction with Buy Price."**

SSRN working paper.

---

## Acknowledgment

We thank you for your time and effort in reviewing this work.
