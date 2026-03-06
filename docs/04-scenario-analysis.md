---
title: Scenario Analysis
layout: default
nav_order: 5
parent: Contract Analysis
---

# Scenario Analysis

## Baseline Assumptions

```
Purchase Price:               $471,708
Current Mortgage Balance:     $375,417 (Jan 2026)
Monthly Payment:              $3,090.10 (split 50/50)
Annual Property Tax:          ~$3,688
Selling Costs:                6% of sale price
Payment Split:                50% Mae / 50% Starseed
```

## Mortgage Balance Projection

| Year | Months Paid | Approx Balance | Principal Paid |
|------|-------------|----------------|----------------|
| 0 | 0 | $377,366 | $0 |
| 2 | 24 | $370,456 | $6,910 |
| 5 | 60 | $356,000 | $21,366 |
| 7 | 84 | $345,542 | $31,824 |
| 10 | 120 | $328,157 | $49,209 |

---

## SCENARIO A: Sale at Year 2

### Year 2 -- 20% Appreciation ($566,050 sale)

```
Sale price:         $566,050
Selling costs (6%): $33,963
Mortgage balance:   $370,456
Net proceeds:       $161,631
```

| Model | Mae Receives | Starseed Receives | Notes |
|-------|--------------|-------------------|-------|
| **Model 1** (Cash %) | $127,204 (78.7%) | $34,427 (21.3%) | Based on total cash contributed |
| **Model 2** (Debt first) | $130,816 | $30,816 | $100k + 50% of remainder |
| **Model 3** (Waterfall) | $130,816 | $30,816 | Same as Model 2 with 50/50 payments |
| **Model 4** (Earn-in 58/42) | $93,746 | $67,885 | Ownership-based split |
| **Model 5** (Commitment) | $97,787 | $63,844 | 60.5/39.5 split by commitment |
| **Model 6** (Commit+Floor) | $97,787 | $63,844 | Same as M5 (Mae > $100k) |

### Year 2 -- Flat Market ($471,708 sale)

```
Sale price:         $471,708
Selling costs (6%): $28,302
Mortgage balance:   $370,456
Net proceeds:       $72,950
```

| Model | Mae Receives | Starseed Receives | Notes |
|-------|--------------|-------------------|-------|
| **Model 1** | $57,411 | $15,539 | Starseed barely gets anything |
| **Model 2** | $72,950 (capped) | $0 | Parents get partial return |
| **Model 3** | $72,950 (all) | $0 | Preferred equity absorbs all |
| **Model 4** | $42,311 | $30,639 | Split by ownership % |
| **Model 5** | $44,135 | $28,815 | 60.5/39.5 (parents lose $56k) |
| **Model 6** | $72,950 | $0 | Floor triggered (parents protected) |

### Year 2 -- Down 10% ($424,537 sale)

```
Sale price:         $424,537
Selling costs (6%): $25,472
Mortgage balance:   $370,456
Net proceeds:       $28,609
```

| Model | Mae Receives | Starseed Receives | Notes |
|-------|--------------|-------------------|-------|
| **Model 1** | $22,513 | $6,096 | Mae takes most of the loss |
| **Model 2** | $28,609 (all) | $0 | Parents get partial return |
| **Model 3** | $28,609 (all) | $0 | Preferred equity takes precedence |
| **Model 4** | $16,593 | $12,016 | Shared loss by ownership % |
| **Model 5** | $17,308 | $11,301 | 60.5/39.5 (parents lose $83k) |
| **Model 6** | $28,609 | $0 | Floor triggered (parents protected) |

---

## SCENARIO B: Sale at Year 5 (Expected Timeline)

### Year 5 -- 20% Appreciation ($566,050 sale)

```
Sale price:         $566,050
Selling costs (6%): $33,963
Mortgage balance:   $356,000
Net proceeds:       $176,087
```

| Model | Mae Receives | Starseed Receives | Mae % | Starseed % |
|-------|--------------|-------------------|-------|------------|
| **Model 1** | $118,859 | $57,228 | 67.5% | 32.5% |
| **Model 2** | $138,044 | $38,044 | 78.4% | 21.6% |
| **Model 3** | $138,044 | $38,044 | 78.4% | 21.6% |
| **Model 4** | $95,087 | $81,000 | 54% | 46% |
| **Model 5** | $106,533 | $69,554 | 60.5% | 39.5% |
| **Model 6** | $106,533 | $69,554 | 60.5% | 39.5% |

**Key Comparison -- Starseed's Payout:**
- Model 3: $38,044
- Model 5/6: $69,554
- **Difference: $31,510 more for Starseed with debt recognition**

### Year 5 -- Flat Market ($471,708 sale)

```
Sale price:         $471,708
Selling costs (6%): $28,302
Mortgage balance:   $356,000
Net proceeds:       $87,406
```

| Model | Mae Receives | Starseed Receives |
|-------|--------------|-------------------|
| **Model 1** | $59,000 | $28,406 |
| **Model 2** | $93,703 (capped) | -$6,297 |
| **Model 3** | $87,406 (all) | $0 |
| **Model 4** | $47,199 | $40,207 |
| **Model 5** | $52,881 | $34,525 |
| **Model 6** | $87,406 | $0 |

**Key Insight -- Flat Market:**
- Model 5 gives Starseed $34,525 but parents only recover $53k of their $100k
- Model 6 protects parents ($87k) while Starseed gets $0
- This is the trade-off: debt recognition vs. downside protection

---

## SCENARIO C: Sale at Year 7

### Year 7 -- 20% Appreciation ($566,050 sale)

```
Sale price:         $566,050
Selling costs (6%): $33,963
Mortgage balance:   $345,542
Net proceeds:       $186,545
```

| Model | Mae Receives | Starseed Receives | Mae % | Starseed % |
|-------|--------------|-------------------|-------|------------|
| **Model 1** | $119,164 | $67,381 | 63.9% | 36.1% |
| **Model 2** | $143,273 | $43,273 | 76.8% | 23.2% |
| **Model 3** | $143,273 | $43,273 | 76.8% | 23.2% |
| **Model 4** | $97,003 | $89,542 | 52% | 48% |
| **Model 5** | $112,860 | $73,685 | 60.5% | 39.5% |
| **Model 6** | $112,860 | $73,685 | 60.5% | 39.5% |

---

## SCENARIO D: One Owner Stops Paying (3 months)

If Mae stops paying for 3 months ($4,635.15 missed):

### Model 3 Handles This Cleanly

```
If Starseed covers Mae's payments:
  Starseed gets credit for 100% of those payments
  Mae's principal contribution % decreases
  Final split adjusts accordingly
```

This provides natural incentive alignment --- if you don't pay, you lose equity.

---

## SCENARIO E: Significant Appreciation (40% over 7 years)

### Year 7 -- 40% Appreciation ($660,391 sale)

```
Sale price:         $660,391
Selling costs (6%): $39,623
Mortgage balance:   $345,542
Net proceeds:       $275,226
```

| Model | Mae Receives | Starseed Receives |
|-------|--------------|-------------------|
| **Model 1** | $175,757 | $99,469 |
| **Model 2** | $187,613 | $87,613 |
| **Model 3** | $187,613 | $87,613 |
| **Model 4** | $143,118 | $132,108 |
| **Model 5** | $166,512 | $108,714 |
| **Model 6** | $166,512 | $108,714 |

---

## Key Observations

1. **Models 2 and 3 produce identical results** when payments are 50/50 and no improvements are made.

2. **Models 5 and 6 produce identical results** in appreciation scenarios (when Mae's share exceeds $100k).

3. **Model 5/6 give Starseed significantly more** in appreciation scenarios:
   - Year 5, +20%: $69,554 vs $38,044 (Model 3) --- **+$31,510**
   - Year 7, +20%: $73,685 vs $43,273 (Model 3) --- **+$30,412**
   - Year 7, +40%: $108,714 vs $87,613 (Model 3) --- **+$21,101**

4. **The key trade-off:**
   - Models 3/6 protect parents' $100k in bad markets
   - Model 5 recognizes Starseed's debt commitment but exposes parents to loss

5. **Model 6 appears in the "Compromise" column for every scenario** --- it balances debt recognition with downside protection.

## Model Selection by Scenario Outcome

| Scenario | Best for Mae | Best for Starseed | Compromise |
|----------|--------------|-------------------|------------|
| Strong appreciation | Model 3 | Model 4/5 | Model 6 |
| Moderate appreciation | Model 3 | Model 5/6 | Model 6 |
| Flat market | Model 5 | Model 4 | Model 6 |
| Declining market | Model 5 | Model 4 | Model 6 |
