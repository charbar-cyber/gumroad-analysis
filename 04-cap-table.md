# Cap Table

Gumroad's capitalization table is one of the most unusual in tech. Understanding its composition is critical because the cap table is the primary reason S-Corp conversion is impossible -- and the primary reason QSBS is so valuable.

---

## Shareholder Overview

### Sahil Lavingia -- Founder

- **Stock type:** Common stock
- **Position:** Majority shareholder
- **Held since:** 2011 (15 years)
- **QSBS status:** Almost certainly qualified -- original issuance, held well past 5 years

Sahil's majority ownership of common stock is the foundation of Gumroad's governance. As the company was rebuilt around a lean model after 2015, his control was reinforced by the departure of KPCB and the reduction of VC influence.

### Seed Investors (2012)

Six to eight individual angels and early-stage funds participated in the $1.1M seed round:

| Investor | Type |
|----------|------|
| Max Levchin | Individual angel |
| Chris Sacca | Individual / Lowercase Capital |
| Ron Conway | SV Angel (fund) |
| Naval Ravikant | Individual angel |
| Accel Partners | Venture fund (partnership) |
| First Round Capital | Venture fund (partnership) |
| Collaborative Fund | Venture fund |

**Key question:** Which of these investors still hold their positions? The KPCB buyback in 2017 established a precedent for exits, but it is unclear from public information whether any seed investors also sold back.

**S-Corp implication:** Accel Partners, First Round Capital, and Collaborative Fund are typically structured as limited partnerships. S-Corps cannot have partnership shareholders. Even if all individual angels sold back, the remaining fund investors would independently disqualify S-Corp election.

### KPCB (Kleiner Perkins) -- EXITED

- **Original position:** Series A lead, $7M round
- **Exit:** Sold entire stake back to Gumroad for $1 (November 2017)
- **Current position:** None
- **Impact:** Removed the largest block of liquidation preferences from the cap table

### Remaining Series A Preferred Holders

After KPCB's exit, the remaining Series A participants (likely Accel, First Round, Collaborative Fund, and potentially others from the seed round who received pro rata rights) hold preferred stock with estimated residual liquidation preferences of approximately **$2.5M**.

**S-Corp implication:** Preferred stock with different economic rights than common stock constitutes a second class of stock. S-Corps may only have one class. This independently disqualifies S-Corp election.

### Crowd SAFE Holders (March 2021)

| Detail | Value |
|--------|-------|
| **Platform** | Republic |
| **Number of investors** | 7,387 |
| **Total raised** | ~$5M |
| **Instrument** | Crowd SAFE (Simple Agreement for Future Equity) |
| **Valuation cap** | $100M |
| **Discount** | 20% |
| **Conversion trigger** | Qualified financing, change of control, or IPO |
| **Current status** | Believed to be unconverted (SAFEs, not yet equity) |

**Critical notes:**

1. **Not yet equity.** Crowd SAFEs are contractual rights to receive equity upon a triggering event. Until conversion, these 7,387 investors may not technically be "shareholders" -- but their conversion rights create enormous structural complexity.

2. **QSBS clock.** If and when SAFEs convert to equity, the QSBS 5-year holding period likely starts at conversion, not at the original investment date. This means the March 2021 investors may not yet have qualified QSBS even though nearly 5 years have passed. The exact treatment depends on the specific terms and how the conversion is structured. This needs legal review.

3. **S-Corp math.** Even if SAFEs have not converted, 7,387 potential shareholders hanging over the cap table makes S-Corp election functionally impossible. Conversion would instantly bust the 100-shareholder limit by a factor of 74x.

### Private Round Investors (2021)

- **Naval Ravikant:** Individual investor, likely common stock or SAFEs at $125M valuation
- **Jason Fried:** Individual investor (Basecamp/37signals founder), same terms
- **Others:** Additional private investors at $125M valuation, names not fully public

### Team Equity via Flexile

| Detail | Value |
|--------|-------|
| **Instrument** | Stock options |
| **Platform** | Flexile (Gumroad's own compensation platform) |
| **Strike price basis** | $100M valuation |
| **Exercise window** | 10 years (unusually long and founder-friendly) |
| **Equity pool** | Average 18.3% equity split across team |
| **Vesting** | Standard (presumed 4-year with 1-year cliff) |

The 10-year exercise window is notable. Standard option agreements give departing employees 90 days to exercise. By extending this to 10 years, Gumroad allows contractors to hold options without the cash pressure of early exercise -- a meaningful benefit that also has tax implications for the recipients.

---

## Summary Cap Table Structure

| Holder | Type | Approximate Position | S-Corp Eligible? |
|--------|------|---------------------|------------------|
| Sahil Lavingia | Common stock | Majority | Yes |
| Seed angels (individuals) | Common or preferred | Small | Yes (if individuals) |
| Seed/Series A funds | Preferred | Small (~$2.5M liq pref) | **No** (partnerships) |
| KPCB | -- | Exited | N/A |
| Crowd SAFE holders | SAFE (unconverted) | 7,387 investors, ~$5M | **No** (too many, likely includes NRAs and entities) |
| Private round (Naval, Jason, etc.) | Common/SAFE | $1M+ at $125M val | Probably yes |
| Team (Flexile options) | Options (unexercised) | ~18.3% pool | Depends on exercise |

**Bottom line:** At least three independent disqualifying factors for S-Corp status exist in this cap table: shareholder count, stock classes, and entity/NRA shareholders. No restructuring can realistically solve all three simultaneously.

---

[Next: Financial Analysis](05-financial-analysis.md)
