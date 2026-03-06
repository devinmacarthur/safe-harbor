# Debt Recognition Models

## The Core Insight

Starseed signed the mortgage. That's $188,683 of personal liability -- real risk that should count as a contribution from day one.

### Commitment Breakdown

| Party | Cash Contributed | Debt Liability | Total Commitment | % of Total |
|-------|------------------|----------------|------------------|------------|
| Mae (+ parents) | $100,000 | $188,683 | $288,683 | **60.5%** |
| Starseed | $0 | $188,683 | $188,683 | **39.5%** |
| **Total** | $100,000 | $377,366 | $477,366 | 100% |

---

## Model 5: Pure Commitment-Based

**Concept:** Ownership equals total commitment (cash + debt liability). No preferred return.

```
Ownership:
  Mae:      60.5%  (down payment + half mortgage)
  Starseed: 39.5%  (half mortgage)

At sale:
  Mae_Payout = Net_Proceeds x 60.5%
  Starseed_Payout = Net_Proceeds x 39.5%
```

**Pros:** Recognizes debt commitment from day one, simple to calculate

**Cons:** Doesn't specifically protect Mae's parents' $100k

---

## Model 6: Commitment-Based with Floor Protection

**Concept:** Split by commitment ratio, BUT Mae's share can never go below $100k if there's enough equity.

```
At sale:
  1. Calculate commitment-based split:
     Mae_Base = Net_Proceeds x 60.5%
     Starseed_Base = Net_Proceeds x 39.5%

  2. Apply protection floor:
     IF Mae_Base < $100,000 AND Net_Proceeds >= $100,000:
       Mae_Payout = $100,000
       Starseed_Payout = Net_Proceeds - $100,000
     ELSE:
       Mae_Payout = Mae_Base
       Starseed_Payout = Starseed_Base
```

---

## Scenario Comparison: All Models

### Year 5, 20% Appreciation ($176,087 net proceeds)

| Model | Mae Receives | Starseed Receives |
|-------|--------------|-------------------|
| **Model 1** (Total Cash) | $118,859 | $57,228 |
| **Model 3** (Waterfall) | $138,044 | $38,044 |
| **Model 4** (Earn-In) | $95,087 | $81,000 |
| **Model 5** (Commitment) | $106,533 | $69,554 |
| **Model 6** (Commit+Floor) | $106,533 | $69,554 |

**Key Insight:** Model 5/6 gives Starseed $69,554 vs only $38,044 under Model 3. That's $31,510 more.

### Year 5, Flat Market ($87,406 net proceeds)

| Model | Mae Receives | Starseed Receives |
|-------|--------------|-------------------|
| **Model 3** (Waterfall) | $87,406 | $0 |
| **Model 5** (Commitment) | $52,881 | $34,525 |
| **Model 6** (Commit+Floor) | $87,406 | $0 |

**Key Insight:** Model 6 protects parents in flat markets while Model 5 does not.

### Year 5, Down 10% ($43,065 net proceeds)

| Model | Mae Receives | Starseed Receives |
|-------|--------------|-------------------|
| **Model 3** (Waterfall) | $43,065 | $0 |
| **Model 5** (Commitment) | $26,054 | $17,011 |
| **Model 6** (Commit+Floor) | $43,065 | $0 |

