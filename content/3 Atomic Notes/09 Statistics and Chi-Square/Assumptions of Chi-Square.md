---
title: "Assumptions of Chi-Square"
aliases:
  - "chi-square assumptions"
  - "assumptions"
tags:
  - atomic
  - statistics
description: "The chi-square test assumes observed values are counts, each observation is independent, and expected values come from a hypothesis (they need not be whole numbers)."
---

> [!abstract] In one sentence
> The chi-square test assumes observed values are counts, each observation is independent, and expected values come from a hypothesis (they need not be whole numbers).

> [!example] Explain it like I'm new (the Feynman way)
> The rules of the game the referee assumes you followed.

## Build it from first principles

Manual p. 125:
1. **Observed values must be counts** of independent events, not percentages or proportions. '75% green' gives a wrong χ²; '18 green' is right.
2. **Each observation is independent**: one result doesn't influence another (each kernel = one fertilization).
3. **Expected values need not be whole numbers** (17.25 green is fine).

Added from statistics texts: the test gets unreliable if any expected count is very small (a common rule is E ≥ 5).

> [!question]- Test yourself: Can you put percentages in the O column?
> **Answer:** No; counts only.

## Connected ideas

- [[Observed Value]]
- [[Expected Value]]
- [[Independent Event]]
- [[Chi-Square Test]]

Browse more in [[MOC - Statistics and Chi-Square]] · [[Vault Index|Index]]

## Learn more

- [Wikipedia: Chi-squared test#Assumptions](https://en.wikipedia.org/wiki/Chi-squared_test#Assumptions)
