---
title: "Calc 07 - The Chi-Square Grid"
aliases:
  - "chi-square table steps"
  - "grid method"
tags:
  - calculation
description: "Filling the chi-square table column by column: O, E, O−E, squared, divided by E, then sum."
---

> [!example] The Feynman version
> One row per category, one column per step of the formula. You never have to hold the whole formula in your head; each column is one small, easy operation on the column before.

## The columns (manual pp. 127, 134)

| Column | What you do | Why |
|---|---|---|
| O | write your count | the data |
| Expected fraction | from the Punnett square | the prediction |
| E | N × fraction | prediction in counts |
| O − E | subtract | the gap (can be negative) |
| (O − E)² | square it | makes it positive, weights big gaps |
| (O − E)²/E | divide by E | puts the gap in proportion |
| **Sum** | add the last column | **this is χ²** |

## Example (18 green, 5 albino vs 3 : 1)

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Green | 18 | ¾ | 17.25 | 0.75 | 0.5625 | 0.0326 |
| Albino | 5 | ¼ | 5.75 | −0.75 | 0.5625 | 0.0978 |
| **Sum** | 23 | | 23 | | | **χ² = 0.130** |

## Traps

- O − E values always sum to 0. If they don't, recheck.
- **Don't take a square root** of the sum. The 'Sum =' box *is* χ².
- Round only at the end (keep 3-4 decimals in the last column).

> [!question]- Try it: 12 green, 12 albino vs 3 : 1. χ²?
> **Answer:** E = 18 and 6. (12−18)²/18 = 2.0; (12−6)²/6 = 6.0; χ² = 8.0.

Concepts: [[Chi-Square Statistic]] · [[Observed Value]] · [[Expected Value]] · [[Summation]] · Back to [[MOC - Calculations]]
