---
title: "Chi-Square Statistic"
type: atomic
aliases:
  - "chi-square value"
  - "chi square value"
tags:
  - atomic
  - statistics-and-chi-square
description: "The chi-square statistic is the single number the test produces: χ² = Σ (O − E)² / E."
---

The chi-square statistic is the single number the test produces: χ² = Σ (O − E)² / E.

Read it as a "surprise score". Zero means the data matched the prediction perfectly. The bigger it gets, the more surprised you'd be if H₀ were true ([[Why a big chi-square means a poor fit]]).

Each piece has a reason:

- **O − E**: the gap in each category.
- **Squared**: so negative and positive gaps can't cancel ([[Why we square the gaps in chi-square]]).
- **÷ E**: so a gap of 5 counts more when you expected 10 than when you expected 1,000 ([[Why we divide by the expected count]]).
- **Σ**: add the surprise from every category.

The trap: the answer key writes "Sum =" at the bottom of the grid. That sum **is** χ². Don't take its square root.

Try it yourself. Can χ² ever be negative? No: every piece is a square divided by a positive number.

See also: [[Chi-Square Test]], [[Observed Value]], [[Expected Value]], [[Summation]].

Learn more: [Wikipedia: Chi-squared test](<https://en.wikipedia.org/wiki/Chi-squared_test>)
