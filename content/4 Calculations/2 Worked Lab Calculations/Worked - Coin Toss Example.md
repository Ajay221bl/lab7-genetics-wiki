---
title: "Worked - Coin Toss Example"
aliases:
  - "coin toss"
tags:
  - calculation
description: "The manual's chi-square example: 58 heads and 42 tails in 100 tosses."
---

> [!example] The Feynman version
> If a coin is fair, 100 tosses 'should' give 50 : 50. We got 58 : 42. Is that just luck, or is the coin bent?

H₀: the coin is fair (no significant difference from 50 : 50).

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Heads | 58 | ½ | 50 | 8 | 64 | 1.28 |
| Tails | 42 | ½ | 50 | −8 | 64 | 1.28 |
| **Sum** | 100 | | 100 | | | **χ² = 2.56** |

df = 2 − 1 = 1 → critical value 3.841. 2.56 < 3.841 → p > 0.05 → **fail to reject H₀**.

> There was no significant difference between observed and expected heads and tails in 100 coin tosses (χ² = 2.56, df = 1, p > 0.05).

Steps used: [[Calc 06 - Expected Counts]] → [[Calc 07 - The Chi-Square Grid]] → [[Calc 08 - Degrees of Freedom]] → [[Calc 09 - Looking Up the Critical Value]] → [[Calc 10 - Comparing and Deciding]] · Back to [[MOC - Calculations]]
