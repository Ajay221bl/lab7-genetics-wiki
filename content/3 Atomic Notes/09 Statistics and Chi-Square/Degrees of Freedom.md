---
title: "Degrees of Freedom"
aliases:
  - "degree of freedom"
tags:
  - atomic
  - statistics
description: "Degrees of freedom (df) is the number of categories whose counts are free to vary once the total is fixed; for this chi-square test, df = k − 1."
---

> [!abstract] In one sentence
> Degrees of freedom (df) is the number of categories whose counts are free to vary once the total is fixed; for this chi-square test, df = k − 1.

> [!example] Explain it like I'm new (the Feynman way)
> If you know the total and all but one bin, the last bin is forced. df counts the bins that were free.

## Build it from first principles

Manual p. 125 reasoning with coins: if you toss 100 coins and know 58 were heads, tails *must* be 42. Only one count was free → df = 2 − 1 = **1**.

| Data | k | df | Critical value (α 0.05) |
|---|---|---|---|
| green / albino | 2 | 1 | 3.841 |
| purple / yellow (ear 1) | 2 | 1 | 3.841 |
| four kernel types (ear 5) | 4 | 3 | 7.815 |
| five colors (Lab 8) | 5 | 4 | 9.488 |

Common errors: df = number of plants − 1, or genotypes − 1. Both wrong.

> [!question]- Test yourself: df for green/albino?
> **Answer:** 1.

## Connected ideas

- [[Categories]]
- [[Critical Value]]
- [[Critical Value Table]]
- [[Calc 08 - Degrees of Freedom]]

Browse more in [[MOC - Statistics and Chi-Square]] · [[Vault Index|Index]]

## Learn more

- [Wikipedia: Degrees of freedom (statistics)](https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics))
