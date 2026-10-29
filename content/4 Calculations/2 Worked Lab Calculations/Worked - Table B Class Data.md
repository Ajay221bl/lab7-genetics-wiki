---
title: "Worked - Table B Class Data"
aliases:
  - "Table B class"
tags:
  - calculation
description: "Table B class data: chi-square of the whole room's seedling totals against both possible crosses."
---

> [!warning] Sample data
> These counts are the answer key's example numbers (the 18 green : 5 albino tray is from the TA meeting; the rest are made up). Swap in your room's real counts; the method stays the same.

Class totals: **106 green, 34 albino** (140 plants).

## Gg × Gg (3 : 1)

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Green | 106 | 0.75 | 105 | 1 | 1 | 0.010 |
| Albino | 34 | 0.25 | 35 | −1 | 1 | 0.029 |
| **Sum** | 140 | | 140 | | | **χ² = 0.038** |

0.038 < 3.841 → fail to reject Gg × Gg.

## Gg × gg (1 : 1)

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Green | 106 | 0.5 | 70 | 36 | 1296 | 18.514 |
| Albino | 34 | 0.5 | 70 | −36 | 1296 | 18.514 |
| **Sum** | 140 | | 140 | | | **χ² = 37.029** |

37.029 > 3.841 → reject Gg × gg, far more decisively than one table's data (7.348).

Next: [[Worked - Question 9 Sample Size]] · Back to [[MOC - Calculations]]
