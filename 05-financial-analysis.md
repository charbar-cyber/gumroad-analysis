# Financial Analysis

Gumroad's financial profile is unusual: a company generating venture-scale revenue with bootstrapped-scale costs. This creates both exceptional profitability and specific tax planning challenges.

All figures are based on publicly available information from Sahil's blog posts, interviews, SEC filings, and the Republic crowdfunding campaign. Actual figures may differ.

---

## Revenue

| Year | Estimated Revenue | YoY Growth | Notes |
|------|-------------------|------------|-------|
| 2021 | ~$11M (est.) | -- | Peak GMV year ($185M) |
| 2022 | ~$11M | ~0% | Pre-pricing change |
| 2023 | ~$21M | +96% | Post-pricing change (flat 10%) |
| 2024 | ~$23.8M | +13% | Continued growth |

The 2023 revenue surge is almost entirely attributable to the pricing model change from a tiered structure to a flat 10% take rate. This was not organic growth in GMV -- in fact, GMV declined from its 2021 peak. The revenue increase came from capturing a larger percentage of each transaction.

### Gross Merchandise Volume (GMV)

| Year | GMV | Notes |
|------|-----|-------|
| 2021 | ~$185M | Peak, pandemic-era creator economy boom |
| 2022 | ~$170M (est.) | Post-pandemic normalization |
| 2023 | ~$171M | Roughly flat despite pricing controversy |
| 2024 | ~$175-180M (est.) | Modest recovery |

The gap between GMV trends (flat/declining) and revenue trends (doubling) illustrates the power of the pricing change. Gumroad is extracting significantly more value from roughly the same volume of transactions.

**Take rate calculation:** At $21M revenue on $171M GMV, Gumroad's effective take rate in 2023 was approximately **12.3%** -- higher than the stated 10%, likely because the 10% is applied before payment processing fees are added.

---

## Profitability

### 2023 Estimated P&L

| Line Item | Amount | Notes |
|-----------|--------|-------|
| **Revenue** | ~$21M | |
| Cost of revenue / processing | ~($5-6M) | Payment processing, infrastructure |
| **Gross profit** | ~$15-16M | ~73% gross margin |
| Contractor compensation | ~($3-4M) | 25 contractors, cash portion |
| Other operating expenses | ~($2-3M) | Tools, legal, accounting, misc |
| **Operating income** | ~$10-11M | ~48-52% operating margin |
| Taxes (federal + state) | ~($1-2M) | C-Corp, 21% federal rate |
| **Net income** | ~$8.9M | ~42% net margin |

These margins are extraordinary. For context:

- Stripe's operating margin is estimated at ~20-25%
- Shopify's operating margin in 2023 was ~15%
- Most SaaS companies operate at 10-25% margins

Gumroad achieves 40%+ net margins because of the contractor model. Zero full-time employees means zero employer-side payroll taxes, zero benefits costs, zero workers' compensation insurance, and dramatically lower overhead.

### Net Income Trend

| Year | Estimated Net Income |
|------|---------------------|
| 2021 | Profitable (amount not public) |
| 2022 | Profitable (amount not public) |
| 2023 | ~$8.9M |
| 2024 | Likely $9-11M (estimated) |

---

## Dividend Policy and Distribution

Gumroad's charter includes a provision requiring distribution of 60% of net income as dividends. This is unusual for a tech company and has significant tax implications.

| Event | Date | Amount |
|-------|------|--------|
| Trial dividend | July 2023 | ~$1M |
| First full annual dividend | May 2024 | $5.34M |

### Dividend math for 2023:

- Net income: ~$8.9M
- 60% distribution: ~$5.34M
- Retained: ~$3.56M (40%)

The $5.34M dividend was distributed to all shareholders (including Crowd SAFE holders, if converted, or to equity holders only if not yet converted -- this detail matters and needs verification).

### Tax Treatment of Dividends

As a C-Corp, Gumroad's dividends are classified as **qualified dividends** (assuming the holding period requirements are met), taxed at the preferential rate of 0%, 15%, or 20% depending on the recipient's income level, plus the 3.8% Net Investment Income Tax (NIIT) for high earners.

For Sahil, the likely rate on qualified dividends is **23.8%** (20% + 3.8% NIIT).

---

## Operating Model Details

### Contractor Compensation

Gumroad's team of ~25 contractors is compensated through a combination of cash and equity:

| Component | Detail |
|-----------|--------|
| **Cash pay** | Varies by role and hours; typically contractor hourly/monthly rates |
| **Equity** | Stock options via Flexile at $100M valuation |
| **Exercise window** | 10 years (far longer than the standard 90 days) |
| **Hours** | Part-time, typically 20-35 hours/week |
| **Average equity split** | 18.3% across team |

The Flexile platform (built by Gumroad) handles both compensation payments and equity management.

### Financial Operations

| Process | Cadence |
|---------|---------|
| Financial close | Quarterly (estimated) |
| Board review | Quarterly (estimated) |
| Dividend declaration | Annual (per charter, 60% of net income) |
| Dividend payment | Annual (May, for prior year) |
| Contractor payments | Monthly |

### Operating Cost Structure

Gumroad's cost structure is dominated by:

1. **Payment processing fees** -- The largest single cost. Credit card processing (Stripe), PayPal, and other payment methods typically cost 2.9% + $0.30 per transaction.
2. **Contractor compensation** -- Cash payments to the 25-person team.
3. **Infrastructure** -- Hosting, CDN, email delivery, and other technical services.
4. **Professional services** -- Legal, accounting, and compliance.
5. **Equity-based compensation** -- Non-cash expense for options granted through Flexile.

The absence of office space, employee benefits, employer payroll taxes, and a large management layer is what produces the exceptional margins.

---

## Key Financial Observations

**1. Revenue concentration risk.** Gumroad's revenue is entirely dependent on the creator economy and its competitive position within it. Competitors include Patreon, Teachable, Podia, Lemon Squeezy, and Stripe direct.

**2. Take rate sensitivity.** The jump from ~6% effective take rate to ~12% doubled revenue on flat GMV. This shows the business is highly sensitive to pricing -- in both directions. A competitive pressure that forces rates down would significantly impact profitability.

**3. Margin sustainability.** The contractor model produces extraordinary margins, but it also creates regulatory risk (see contractor classification analysis). If any contractors are reclassified as employees, costs would increase substantially.

**4. Accumulated earnings.** With $8.9M in net income, $5.34M distributed, and ~$3.56M retained, the retained earnings need a documented business purpose to avoid the accumulated earnings tax. At 40%+ net margins and limited capex needs, the IRS may question why so much cash is being retained in the corporation.

**5. Single-owner economics.** Although there are 7,387+ shareholders, Sahil holds a majority of the equity. Most of the economic benefit of tax planning accrues to him. This simplifies planning in some ways (fewer stakeholders to coordinate) but complicates it in others (reasonable compensation scrutiny, related-party transaction rules).

---

[Next: S-Corp Analysis](06-scorp-analysis.md)
