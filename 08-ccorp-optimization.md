# C-Corp Optimization Strategies

Gumroad is staying a C-Corp. That is the right answer. The question now is: how do you minimize the tax burden within that structure?

The "double taxation" problem of C-Corps -- corporate tax on profits, then individual tax on dividends -- is real. But it is dramatically overstated in popular discourse. With proper planning, the effective combined rate for a C-Corp can be competitive with or better than an S-Corp pass-through, especially for high-income shareholders.

Here are seven strategies, each with IRC citations and estimated impact.

---

## Strategy 1: Qualified Dividend Optimization

**IRC Section 1(h)(11)**

### How It Works

Dividends paid by a C-Corp to individual shareholders are taxed at preferential rates if they meet the "qualified dividend" requirements:
- The stock must be held for more than 60 days during the 121-day period beginning 60 days before the ex-dividend date
- The corporation must be a domestic corporation (or certain qualified foreign corporations)

**Qualified dividend tax rates:**

| Taxable Income (Single) | Rate |
|--------------------------|------|
| Up to $47,025 | 0% |
| $47,026 - $518,900 | 15% |
| Over $518,900 | 20% |

Plus the 3.8% Net Investment Income Tax (NIIT) for taxpayers with modified AGI above $200,000 (single) or $250,000 (married filing jointly).

### Application to Gumroad

Sahil's dividends from Gumroad are almost certainly qualified dividends. At his income level, the rate is 20% + 3.8% NIIT = **23.8%**.

Compare this to ordinary income, which would be taxed at up to **37% + 3.8% NIIT = 40.8%** at the top bracket.

The spread between 23.8% and 40.8% is 17 percentage points. On the 2023 dividend of $5.34M, assuming Sahil receives the majority, the qualified dividend treatment saves hundreds of thousands compared to what the same cash would cost if paid as salary or pass-through income taxed at ordinary rates.

### Optimization

Structure the timing, amount, and documentation of dividends to ensure they always qualify for preferential rates. This is largely mechanical -- the key is maintaining clean records and proper board authorization.

---

## Strategy 2: Accumulated Earnings Tax Defense

**IRC Sections 531-537**

### The Risk

The accumulated earnings tax is a **20% penalty surtax** on earnings retained by a C-Corp beyond the reasonable needs of the business. It exists to prevent shareholders from using the corporation as a tax shelter to avoid dividend taxation.

Gumroad's profile raises flags:
- $8.9M net income, only $5.34M distributed
- Lean operating model with minimal capital expenditure needs
- ~$3.56M retained in the corporation
- High profitability with low reinvestment requirements

The IRS may ask: why is this corporation retaining cash instead of distributing it?

### The Defense

The accumulated earnings credit allows a corporation to retain up to $250,000 ($150,000 for certain personal service corporations) without any justification. Beyond that, retained earnings must serve a **specific, definite, and feasible** business purpose.

Acceptable business purposes include:

| Purpose | Application to Gumroad |
|---------|----------------------|
| Business expansion | New product development, market expansion, AI integration |
| Working capital reserves | 3-6 months of operating expenses as a buffer |
| Debt retirement | Paying off any outstanding obligations |
| Acquisition fund | Documented plan to acquire complementary businesses or technology |
| Product liability / litigation reserve | Reserve for potential legal costs |
| Self-insurance | Reserve for uninsured risks |
| R&D investment | Ongoing software development and AI capabilities |

### Action Required

**Document everything.** The defense against accumulated earnings tax is documentation, not just intention. Gumroad's board should:

1. Pass resolutions identifying specific business purposes for retained earnings
2. Attach dollar amounts to each purpose
3. Create a timeline for when the funds will be deployed
4. Review and update this documentation annually
5. Maintain minutes showing the board considered and discussed the retention decision

A vague statement like "we might need the money someday" will not survive IRS scrutiny. Specific plans -- "We are retaining $2M for AI development to be deployed over 18 months, and $1.5M as a working capital reserve equal to 4 months of operating expenses" -- will.

---

## Strategy 3: Reasonable Compensation Analysis

### The Issue

For a C-Corp with a controlling shareholder, the IRS examines compensation from both directions:

- **Too little compensation:** If Sahil takes minimal salary and instead extracts value through dividends (taxed at 23.8%), the IRS may reclassify dividends as compensation (taxed at up to 40.8%). This is the mirror image of the S-Corp reasonable compensation issue.
- **Too much compensation:** If Sahil takes excessive salary to reduce corporate taxable income, the excess is not deductible by the corporation under IRC Section 162(a)(1).

### The Sweet Spot

The goal is to set Sahil's compensation at a level that:
- Is reasonable for the services he performs (setting product direction, managing the business)
- Creates enough FICA-taxable wages to maximize Social Security and Medicare calculations
- Leaves sufficient corporate income to take advantage of the 21% corporate rate
- Maintains the qualified dividend characterization of actual distributions

A reasonable range, based on comparable CEO/founder compensation for a company of Gumroad's size and profitability, might be **$300,000 to $500,000** in annual salary.

This is worth modeling carefully. The exact optimal number depends on Sahil's total income picture, including his IRS W-2 wages.

---

## Strategy 4: R&D Tax Credits

**IRC Section 41**

### How It Works

The Research and Development tax credit provides a dollar-for-dollar reduction in tax liability for qualifying research expenditures. This is not a deduction -- it is a **credit**, which is more valuable.

Qualifying activities include:
- Developing new or improved software
- Designing and testing algorithms
- Integrating AI/ML capabilities
- Resolving technical uncertainty in product development
- Building internal tools and infrastructure

### Application to Gumroad

Gumroad is a software platform that is actively developing new features, integrating AI capabilities, and building tools like Flexile. Much of the contractor team's work likely qualifies as R&D.

**Estimated annual credit:**

| Component | Estimated Qualifying Spend | Credit Rate | Estimated Credit |
|-----------|---------------------------|-------------|-----------------|
| Software development contractor costs | $1.5M - $2.5M | ~6.5% (simplified credit) | $97K - $162K |
| Cloud computing for R&D | $200K - $500K | ~6.5% | $13K - $32K |
| **Total estimated credit** | | | **$65K - $130K+** |

The simplified credit (Alternative Simplified Credit method) is 14% of qualifying research expenses exceeding 50% of the average of the three prior years. The effective rate works out to roughly 6-7% of qualifying spend.

### Action Required

Conduct a formal R&D tax credit study. This involves:
1. Identifying qualifying activities and personnel
2. Documenting the technical uncertainty being resolved
3. Calculating qualifying expenditures using an acceptable methodology
4. Filing Form 6765 with the corporate return
5. Maintaining contemporaneous documentation (time tracking, project descriptions, technical memos)

The study typically costs $10,000-$25,000 and can be applied retroactively to open tax years (generally 3 years back).

---

## Strategy 5: Retirement Plan Strategies

**IRC Sections 401(a), 401(k), 404, 415**

### How It Works

C-Corps can sponsor retirement plans that provide tax-deductible contributions. The corporation deducts the contributions, reducing taxable income at the 21% corporate rate. The recipient does not pay tax until funds are withdrawn in retirement.

For a company like Gumroad with one highly-compensated owner/executive and a small team, the most powerful combination is:

### Defined Benefit Plan + 401(k)

| Plan | 2026 Contribution Limit | Notes |
|------|--------------------------|-------|
| 401(k) employee deferral | $23,500 ($31,000 if age 50+) | Pre-tax or Roth |
| 401(k) employer match | Up to 25% of compensation | Tax-deductible to corporation |
| Defined benefit plan | Actuarially determined, up to ~$275,000/year | Based on age, salary, years to retirement |
| **Combined potential** | **$250,000 - $400,000/year** | Depends on plan design and actuarial calculations |

### Application to Gumroad

Sahil is in his early 30s. A defined benefit plan for a younger participant has lower annual limits than for someone closer to retirement, but the 401(k) employer match and profit-sharing components can still be substantial.

Key considerations:
- The plan must not discriminate in favor of highly compensated employees (but with all contractors and no employees, the testing is simpler)
- Contractor status matters -- if team members are reclassified as employees, they may need to be included in the plan
- The corporate deduction reduces Gumroad's taxable income at the 21% corporate rate

**Estimated annual tax savings:** $250K-$400K in contributions x 21% corporate rate = **$52,500 - $84,000** in reduced corporate tax, plus the tax deferral benefit to Sahil personally.

---

## Strategy 6: Contractor Classification Compliance

**IRC Section 3509; IRS Form SS-8; Revenue Ruling 87-41**

### The Risk

Gumroad operates with ~25 independent contractors working 20-35 hours per week. Several factors in Gumroad's contractor arrangements may indicate an employment relationship under IRS and state tests:

| Factor | Risk Level |
|--------|------------|
| Regular weekly hours (20-35) | High |
| Ongoing, indefinite engagements | High |
| Work integral to core business | High |
| Potential economic dependence on Gumroad | Medium |
| Company-provided tools/platforms | Medium |
| Contractor controls own methods/schedule | Mitigating |
| No benefits, no withholding | Standard for contractors |

### Potential Consequences of Reclassification

If the IRS or a state agency reclassifies contractors as employees:

- **Back employment taxes:** Employer share of FICA (7.65%), FUTA, and state unemployment taxes for all reclassified workers, going back up to 3 years
- **Penalties:** Failure to withhold, failure to file, and potential fraud penalties
- **Worker claims:** Reclassified employees may claim benefits, overtime, and other protections
- **State exposure:** California (where Gumroad has nexus through Sahil's past residence) uses the ABC test, which is stricter than the federal common law test

### Mitigation

1. Review all contractor agreements for proper language and structure
2. Ensure contractors maintain independence (own tools, other clients, control over methods)
3. Consider converting the most at-risk contractors to actual employees (those working 30+ hours, with multi-year tenure, performing core functions)
4. Document the business rationale for contractor classification
5. Consider a Voluntary Classification Settlement Program (VCSP) filing if the risk is significant

---

## Strategy 7: Open-Source IP Valuation

### The Opportunity

Gumroad has open-sourced portions of its codebase. While open-sourcing software is generally not a taxable event, the intellectual property considerations are worth evaluating:

**Charitable contribution of IP:** If Gumroad donates intellectual property to a qualified organization, the corporation may be entitled to a charitable deduction. For C-Corps, the deduction for contributed IP is generally limited to the lesser of the property's fair market value or the corporation's basis in the property (IRC Section 170(e)).

**Defensive IP strategy:** Open-sourcing can be framed as a business strategy to build community, attract talent, and defend against competitive threats -- all of which support the accumulated earnings tax defense ("we are investing in community-building and developer relations as a business strategy").

**Brand and ecosystem value:** The open-source strategy creates intangible value (community goodwill, developer ecosystem) that, while not directly deductible, supports the company's overall valuation and business purpose narrative.

### Action Required

1. Inventory all open-sourced IP and determine Gumroad's tax basis in each component
2. Evaluate whether any charitable deduction opportunity exists
3. Document the business purpose of open-sourcing (supports accumulated earnings defense)
4. Consider whether any open-source contributions qualify for R&D credit treatment (the development work, not the contribution itself)

---

## Combined Impact

When all seven strategies are applied together:

| Strategy | Estimated Annual Benefit |
|----------|--------------------------|
| Qualified dividend optimization | Saves 17 percentage points vs. ordinary income on dividends |
| Accumulated earnings tax defense | Avoids 20% surtax on retained earnings |
| Reasonable compensation | Optimizes split between salary (deductible) and dividends (preferential rate) |
| R&D tax credits | $65K - $130K+ in dollar-for-dollar tax reduction |
| Retirement plans | $52K - $84K in corporate tax savings + personal tax deferral |
| Contractor compliance | Avoids potential six-figure back-tax liability |
| IP valuation | Potential charitable deduction + accumulated earnings support |

**Net effect:** An optimized C-Corp effective tax rate of approximately **26-28%**, competitive with S-Corp pass-through in most scenarios.

---

[Next: Tax Comparison](09-tax-comparison.md)
