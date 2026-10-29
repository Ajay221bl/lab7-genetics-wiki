---
title: "Chi-Square Statistic"
aliases:
  - "chi-square value"
  - "calculated chi-square"
tags:
  - atomic
  - statistics
description: "The chi-square statistic is the single number χ² = Σ (O − E)² / E that summarizes how far all the observed counts are from the expected counts."
---

> [!abstract] In one sentence
> The chi-square statistic is the single number χ² = Σ (O − E)² / E that summarizes how far all the observed counts are from the expected counts.

> [!example] Explain it like I'm new (the Feynman way)
> For each category: how far off were you, squared, measured relative to what you expected. Then add them all up.

## Build it from first principles

Why each piece of the formula is there:
- **O − E**: the gap in each category.
- **squared**: makes every gap positive (so + and − gaps don't cancel) and makes big gaps count much more.
- **÷ E**: puts the gap in proportion. Missing by 3 when you expected 5 is big; missing by 3 when you expected 500 is nothing.
- **Σ**: add across all categories.

χ² is never negative. 0 = perfect fit. **No square root**: the ² is part of the name. The 'Sum =' box under the last column of the manual's table *is* χ².

> [!question]- Test yourself: Why divide by E?
> **Answer:** A gap of 3 matters a lot if you expected 5, hardly at all if you expected 500.

## Connected ideas

- [[Chi-Square Test]]
- [[Observed Value]]
- [[Expected Value]]
- [[Summation]]
- [[Test Statistic]]
- [[Calc 07 - The Chi-Square Grid]]

Browse more in [[MOC - Statistics and Chi-Square]] · [[Vault Index|Index]]

## Learn more

- [Wikipedia: Chi-squared test](https://en.wikipedia.org/wiki/Chi-squared_test)
