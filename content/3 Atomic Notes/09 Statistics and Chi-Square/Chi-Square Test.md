---
title: "Chi-Square Test"
aliases:
  - "chi-square analysis"
  - "chi-squared test"
  - "χ² test"
  - "chi square"
tags:
  - atomic
  - statistics
description: "The chi-square (χ²) test is a statistical test that measures how far observed counts are from expected counts and decides whether that gap is small enough to be due to chance."
---

> [!abstract] In one sentence
> The chi-square (χ²) test is a statistical test that measures how far observed counts are from expected counts and decides whether that gap is small enough to be due to chance.

> [!example] Explain it like I'm new (the Feynman way)
> A 'surprise meter': it adds up how surprising each category's gap is, then asks if total surprise is more than luck usually produces.

## Build it from first principles

Say 'KY-square'. The steps:

1. State [[Null Hypothesis|H₀]] (data fit the predicted ratio).
2. Compute [[Expected Value|expected counts]] from the ratio.
3. Compute [[Chi-Square Statistic|χ² = Σ (O − E)² / E]].
4. Find [[Degrees of Freedom|df = k − 1]].
5. Look up the [[Critical Value|critical value]] for df at [[Level of Significance|α = 0.05]].
6. χ² < critical → [[Fail to Reject the Null Hypothesis|fail to reject]]; χ² ≥ critical → [[Reject the Null Hypothesis|reject]].
7. Write a [[Results Statement|results statement]].

Full walk-through: [[Topic - The Chi-Square Goodness of Fit Test]] and [[Calc 07 - The Chi-Square Grid]].

> [!question]- Test yourself: List the steps of a chi-square test.
> **Answer:** H₀ → E → χ² → df → critical value → compare → results statement.

## Connected ideas

- [[Chi-Square Statistic]]
- [[Degrees of Freedom]]
- [[Critical Value]]
- [[Null Hypothesis]]
- [[Goodness of Fit]]
- [[Assumptions of Chi-Square]]

Browse more in [[MOC - Statistics and Chi-Square]] · [[Vault Index|Index]]

## Learn more

- [Wikipedia: Chi-squared test](https://en.wikipedia.org/wiki/Chi-squared_test)
- [Khan Academy: Chi-square statistic for hypothesis testing](https://www.khanacademy.org/math/statistics-probability/inference-categorical-data-chi-square-tests)
