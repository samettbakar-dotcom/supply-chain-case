# TGIF: Low-Volume, High-Flexibility Operational Architecture & Supply Chain Strategy

Samet Bakar | Supply Chain & Operations | September 2026

> **Note:** TGIF is a self-initiated concept project. All figures are illustrative assumptions used to test the model. They are not real company data.

---

## 1. Introduction: An Agile Supply Chain Trial, Not a Brand Story

I frame TGIF as a deliberate operational response to the structural fragility of mass-market apparel. The standard mass-market model runs on high SKU variety, broad size and color assortment, a large forecast-error margin, and a continuous discount mechanism built to absorb that error. This makes the supply chain fragile: production volume stays high while the demand signal is weak, the error freezes into inventory, and that inventory gets burned off through markdowns.

TGIF's low-SKU / high-margin / zero-discount architecture is a classic agile supply chain proposition: manage demand uncertainty with small batches and a fast reorder cycle instead of wide production volume. This document tests that proposition as an operational model across four axes: capacity/MOQ, the financial backbone, SKU/assortment architecture, and the risk matrix. The goal is to see upfront where the model breaks.

### Baseline assumptions

| Item | Assumption |
|---|---|
| Batch size | 150 – 250 units per style |
| Drop cycle | New capsule every 6 – 8 weeks |
| Price tiers | Entry / Signature (Core) / Statement. Signature mid-price: 8,000 TL |
| Target mark-up | 3.5x – 4.2x |
| Cost structure (% of retail) | COGS 25%, shipping/packaging 7%, marketing 14% |
| CMT share of COGS | 28 – 35% |
| Pattern/sample cost | 6 – 10% of COGS (asymmetric cut) |
| Discounting | Near zero |
| Target net margin | 18 – 26% |
| Size split | 55% S–M, 35% XS+L combined, 10% XL |
| Channels | Own site (DTC) as main channel, limited consignment |

---

## 2. Capacity and MOQ Constraints

Small-batch production is a deliberate choice, but it has a cost. Most qualified CMT (Cut-Make-Trim) workshops plan capacity around high-volume, recurring orders. A profile of low unit count, frequently changing patterns and heavy sample iteration (from asymmetric cutting) reads as low-efficiency, labor-intensive work. I treat this as operational risk in three areas.

### 2.1 Low-lot cost premium

Brands ordering below the MOQ threshold typically pay a 15 – 30% premium on unit CMT cost. Cutting-table setup, thread/trim changeover and quality-control overhead are spread over few units. This pushes up the CMT share, and without a real supplier cost breakdown the 3.5x – 4.2x mark-up target cannot be verified.

### 2.2 Priority queue risk

Workshop capacity is fixed while demand is seasonal. In peak periods (pre-holiday, early summer), workshops prioritize large recurring customers, and a new low-volume brand is the first to be pushed back. This directly threatens the 6 – 8 week drop commitment.

*Mitigation:* Do not rely on a single workshop. Keep at least one backup CMT partner in a continuous, even if low-volume, relationship, so that in a capacity crunch the brand is a known, low-risk customer.

### 2.3 Lead-time compression

Lead time from sample approval to shipment typically runs 3 – 5 weeks at small workshops, which consumes most of a 6 – 8 week drop cycle. The extra fit iterations from the asymmetric pattern (each size tested separately) compress it further. A "zero tolerance" quality commitment conflicts with this calendar, and holding both at once is not realistic without sacrificing one.

**Bottom line:** Capacity and MOQ risk is as critical a breaking point as the financial one. It feeds into section 3, since lot premiums and lead-time risk affect both COGS and the cash cycle.

---

## 3. Financial Backbone

The real test of a low-SKU / high-margin model is not the mark-up on paper. It is the break-even point, the cash conversion cycle, and channel-level margin erosion. Below is a skeleton model using the baseline assumptions. It should be rebuilt with actual TL values once real fixed-cost and supplier figures are available.

### 3.1 Break-even framework

**Break-even (units) = Fixed Costs / (Unit Selling Price − Unit Variable Cost)**

Using the Signature tier mid-price (8,000 TL) and the cost percentages above (COGS 25%, shipping/packaging 7%, marketing 14%):

- Unit variable cost = 8,000 × (25% + 7% + 14%) = **3,680 TL**
- Unit contribution margin = **4,320 TL**

Fixed costs (pattern/sample amortization, invite-only event budget, software/platform costs) are not yet quantified, so break-even units cannot be calculated. This is the model's most concrete gap: the 18 – 26% net margin target remains a wish until the fixed-cost base is known.

### 3.2 Sample and pattern amortization

The asymmetric pattern strategy raises the cost per sample round, since each size is tested separately. Budgeted at 6 – 10% of COGS against a sector average of 3 – 6%, it is already above normal. The minimum sales volume needed to amortize it is undefined. At 150 – 250 units per style, the amortized share per unit stays high and only falls as volume grows. Low volume plus high sample cost creates a structural drag on the margin target from day one.

### 3.3 Margin erosion in the consignment channel

Consignment was defined as a visibility tool, not a volume tool, but its margin impact was never quantified. Concept-store consignment commission typically runs 40 – 50%.

| Line item | DTC (own site) | Consignment (45% commission) |
|---|---|---|
| Retail price | 8,000 TL | 8,000 TL |
| Store commission | — | 3,600 TL |
| Revenue to brand | 8,000 TL | 4,400 TL |
| COGS (25% of retail) | 2,000 TL | 2,000 TL |
| Gross margin | 6,000 TL (75% of retail) | 2,400 TL (30% of retail) |

The same product at the same price drops from 75% to 30% gross margin. The effective mark-up of 3.5x – 4.2x falls to roughly 1.9x – 2.3x. Putting a Signature Core item on consignment contradicts its role as the margin engine, so consignment should stay limited to the Entry tier or a small showcase item.

### 3.4 Return rate and cash conversion cycle (CCC)

**CCC = DIO + DSO − DPO**

(DIO: days inventory outstanding, DSO: days sales outstanding, DPO: days payable outstanding.)

In DTC, DSO is near zero because online orders are prepaid. That is an advantage. But fit and size uncertainty from the asymmetric pattern raises the return rate, and every return goes back into DIO (warehouse intake, quality check, relisting), which extends the CCC. No return-rate target or return policy is defined yet. Online returns in contemporary/premium womenswear typically run 20 – 35%, so this line needs its own budget above sector-average assumptions.

---

## 4. SKU and Assortment Architecture

### 4.1 Capacity pressure from the 6 – 8 week drop cycle

Each capsule requires a full development loop: pattern development, sample, approval/revision, production, shipment. With 3 – 5 weeks of workshop lead time (see 2.3), development and production overlap in the tightest scenario, leaving no buffer. The extra fit iterations eat further into it.

Two practical options:

- Stretch the cycle to 10 – 12 weeks (slightly softens the "always something new" feel), or
- Design each capsule as a variation of the same core pattern family (new fabric, color or detail, not a new pattern) to shorten development time.

As it stands, the cycle puts both workshop capacity and quality-control discipline at risk.

### 4.2 Size distribution as an inventory problem

The 55% core (S–M) / 35% edge (XS+L combined) / 10% XL split is not a design preference. It is a classic newsvendor (single-period inventory) problem: the cost of overstock against the cost of stockout. With near-zero discounting, unsold inventory is close to a total loss, so the cost of a wrong size distribution is far higher than in mass-market retail, where markdowns absorb the error.

| Size | Planned weight | Inventory risk | Mitigation |
|---|---|---|---|
| S–M (core) | 55% | Low, strong demand signal | Priority for fast reorder |
| XS + L (edge) | 35% combined | Medium, partial mismatch with persona | Revise against real sell-through data |
| XL | 10% | High, excluded demand | Evaluate a made-to-order option |

This table rests on assumed stock depth, not actual sell-through data. Without real demand data, the 55/35/10 split is a hypothesis, not a decision.

---

## 5. Operational Risk Matrix

| Risk | Root cause | Impact | Priority |
|---|---|---|---|
| Low-lot cost premium | Order volume below MOQ | COGS increase of 15 – 30% | High |
| Capacity deprioritization | Low-volume, new-customer profile | Drop schedule slippage | High |
| Lead-time compression | 6 – 8 week cycle vs. 3 – 5 week workshop time | Quality-control trade-off | High |
| Break-even uncertainty | Fixed-cost data missing | Margin target unverifiable | Critical |
| Consignment margin erosion | 40 – 50% commission | Effective mark-up 3.5x falls to about 2x | High |
| Return rate / CCC extension | Asymmetric pattern + online sales | Cash cycle deterioration | Med-High |
| Size distribution error | No real demand data | Stockout or dead stock | Medium |

---

## 6. Conclusion

TGIF's low-SKU / high-margin / zero-discount proposition is operationally defensible, but only if the model is validated numerically across its four axes (capacity, financial backbone, SKU architecture, risk matrix) rather than argued through brand narrative.

- **Most critical gap:** missing break-even and fixed-cost data. Without it, the model cannot be tested on paper.
- **Second gap:** the margin impact of consignment was not factored into the original strategy.

Until both gaps are closed, this remains a vision, not yet an operational architecture.

---

Samet Bakar | Supply Chain & Operations | APICS/CSCP | September 2026
