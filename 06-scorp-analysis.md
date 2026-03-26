# S-Corp Analysis: Why Conversion Is Impossible

The most common tax planning recommendation for a profitable closely-held business is to elect S-Corporation status. The logic is straightforward: S-Corps pass income through to shareholders, avoiding corporate-level tax and eliminating the "double taxation" problem.

For Gumroad, this advice does not apply. S-Corp conversion is not just inadvisable -- it is structurally impossible under current law.

More importantly, even if it were possible, it would be the wrong move. Converting would destroy QSBS eligibility worth potentially millions in tax savings.

---

## S-Corp Eligibility Requirements (IRC Section 1361)

To elect S-Corp status, a corporation must meet ALL of the following requirements:

| Requirement | Gumroad Status | Result |
|-------------|---------------|--------|
| No more than 100 shareholders | 7,387+ crowdfunding investors alone | **FAIL** |
| Only one class of stock | Preferred stock from remaining Series A VCs | **FAIL** |
| No non-resident alien shareholders | Statistically near-certain among 7,387 investors | **FAIL** |
| No corporate or partnership shareholders | Accel, First Round, Collaborative Fund (partnerships) | **FAIL** |
| Must be a domestic corporation | Delaware C-Corp | Pass |

Gumroad fails four of the five requirements. Let's examine each.

---

## Failure 1: Shareholder Limit (100 Maximum)

**The rule:** An S-Corp may have no more than 100 shareholders. Family members can elect to be treated as one shareholder, but this exception is narrow and requires affirmative election.

**Gumroad's situation:** The March 2021 Republic crowdfunding raised $5M from **7,387 individual investors.** Even if the Crowd SAFEs have not yet converted to equity, the investors hold contractual rights to equity that make any S-Corp election practically impossible.

**The math:** 7,387 is 74x the limit. There is no exception, workaround, or special election that can solve a 74x overage.

Even excluding crowdfunding investors entirely, Gumroad likely has more than 100 shareholders when counting seed investors, Series A participants, private round investors, and team members who have exercised options.

---

## Failure 2: One Class of Stock

**The rule:** An S-Corp may have only one class of stock. Differences in voting rights are generally permitted, but differences in economic rights (distribution and liquidation preferences) are not.

**Gumroad's situation:** The remaining Series A investors (those who did not exit with KPCB) hold preferred stock with approximately **$2.5M in liquidation preferences.** This preferred stock has different economic rights than common stock -- specifically, it receives its liquidation preference before common shareholders receive anything.

This constitutes a second class of stock, disqualifying S-Corp election.

**Crowd SAFE complication:** The Crowd SAFEs themselves may also be treated as a second class of stock, depending on their specific terms and whether they are treated as equity for tax purposes. Even if the SAFEs are treated as debt (which is arguable), their conversion into equity at a different price than existing shareholders paid creates additional class-of-stock problems.

---

## Failure 3: No Non-Resident Alien Shareholders

**The rule:** No shareholder of an S-Corp may be a nonresident alien (an individual who is neither a U.S. citizen nor a U.S. resident for tax purposes).

**Gumroad's situation:** The Republic crowdfunding campaign was conducted online and available to a broad investor base. With 7,387 investors, it is **statistically near-certain** that some are non-resident aliens. Republic's platform is accessible internationally, and while Regulation CF has some restrictions on non-U.S. investors, enforcement and verification are imperfect.

Even one non-resident alien shareholder disqualifies the entire election. With 7,387 investors, confirming the residency and tax status of every single one would be an enormous and likely impractical undertaking.

---

## Failure 4: No Entity Shareholders

**The rule:** With limited exceptions for certain trusts, estates, and tax-exempt organizations, S-Corp shareholders must be individuals. Partnerships, LLCs taxed as partnerships, and corporations cannot hold S-Corp stock.

**Gumroad's situation:** Several of Gumroad's investors are funds:

- **Accel Partners** -- Typically structured as a limited partnership
- **First Round Capital** -- Typically structured as a limited partnership
- **Collaborative Fund** -- Fund structure

If any of these funds still hold Gumroad stock (either from the seed round or Series A), their presence as partnership-entity shareholders independently disqualifies S-Corp election.

Additionally, among the 7,387 crowdfunding investors, it is likely that some invested through LLCs, trusts, or other entities that would not qualify as eligible S-Corp shareholders.

---

## The Crowd SAFE Problem

Even setting aside the four failures above, the unconverted Crowd SAFEs create a unique structural problem.

**SAFEs are not equity.** They are contractual rights to receive equity in the future. If Gumroad elected S-Corp status before the SAFEs converted, the subsequent conversion of 7,387 SAFEs into equity would instantly violate the shareholder limit, causing **involuntary termination** of the S-Corp election.

Involuntary termination of S-Corp status triggers a mandatory **5-year waiting period** before the company can re-elect S-Corp status, creates a short tax year, and potentially generates unexpected tax consequences for all shareholders.

This is not a manageable risk. It is a structural impossibility.

---

## Could Restructuring Work?

In theory, there are several restructuring strategies that could address some of the S-Corp eligibility failures. In practice, none of them work for Gumroad.

### Option 1: F Reorganization

An F reorganization (IRC Section 368(a)(1)(F)) involves creating a new holding company, contributing Gumroad shares to it, and making the S-Corp election at the holding company level.

**Problem:** This does not solve the shareholder count. All 7,387 investors would still be indirect shareholders. The same eligibility requirements apply.

### Option 2: Share Buyback Program

Buy back shares from enough investors to get below 100 shareholders.

**Problem:** You would need to buy out at least 7,287 of the 7,387 crowdfunding investors, plus any excess shareholders from other groups. At a $100M+ valuation, even buying back $5M worth of Crowd SAFEs at face value would require significant capital, complex negotiations with thousands of individuals, and SEC compliance for any tender offer.

The cost, complexity, and timeline make this impractical.

### Option 3: Crowd SAFE Cancellation

Negotiate with SAFE holders to cancel their SAFEs in exchange for cash or other consideration.

**Problem:** Same practical issues as a buyback, plus potential securities law violations. Crowd SAFEs were sold under Regulation CF with specific investor protections. Mass cancellation would likely require SEC approval, disclosure filings, and potentially litigation from investors who object.

### Option 4: Convert to LLC

Restructure Gumroad from a C-Corp to an LLC taxed as a partnership, then make an S-Corp election for the LLC.

**Problem:** Converting from a C-Corp to an LLC is treated as a liquidation for tax purposes. This would trigger recognition of all built-in gains at the corporate level (at a $100M+ valuation, this could mean tens of millions in tax) and distribution of assets to shareholders (triggering individual-level tax as well).

The tax cost of this restructuring would vastly exceed any future S-Corp tax savings.

---

## Recommendation: Stay C-Corp and Optimize

The S-Corp analysis leads to a clear conclusion: **Gumroad should remain a C-Corporation.**

This is not a concession. It is the right answer. Here is why:

1. **QSBS eligibility is worth more than S-Corp savings.** Sahil's QSBS exclusion alone could save $2.38M on a future exit. S-Corp conversion would permanently destroy this. (See [QSBS: The Crown Jewel](07-qsbs-crown-jewel.md).)

2. **C-Corp tax rates are competitive when optimized.** With proper planning -- qualified dividends, retirement plans, R&D credits, strategic compensation -- the effective tax rate can reach 26-28%. (See [C-Corp Optimization](08-ccorp-optimization.md).)

3. **The cap table makes conversion impossible anyway.** Even if S-Corp were desirable, the 7,387 investors, multiple stock classes, and entity shareholders make it structurally impossible.

The right strategy is not to fight the structure. It is to optimize within it.

---

[Next: QSBS: The Crown Jewel](07-qsbs-crown-jewel.md)
