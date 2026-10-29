---
title: "Worked - Table B Group Data"
aliases:
  - "Table B group"
tags:
  - calculation
description: "Table B group data: chi-square of one table's seedling counts against Gg × Gg and Gg × gg."
---

> [!warning] Sample data
> These counts are the answer key's example numbers (the 18 green : 5 albino tray is from the TA meeting; the rest are made up). Swap in your room's real counts; the method stays the same.

Our table: **18 green, 5 albino** (23 plants). Test both possible crosses.

## Cross 1: Gg × Gg (3 : 1)

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Green | 18 | 0.75 | 17.25 | 0.75 | 0.5625 | 0.033 |
| Albino | 5 | 0.25 | 5.75 | −0.75 | 0.5625 | 0.098 |
| **Sum** | 23 | | 23 | | | **χ² = 0.130** |

df = 1; critical value 3.841; **0.130 < 3.841** → fail to reject.

> There was no significant difference between the observed and expected numbers of green and albino seedlings (χ² = 0.130, df = 1, p > 0.05). We fail to reject the hypothesis that the parents were Gg × Gg.

## Cross 2: Gg × gg (1 : 1)

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Green | 18 | 0.5 | 11.5 | 6.5 | 42.25 | 3.674 |
| Albino | 5 | 0.5 | 11.5 | −6.5 | 42.25 | 3.674 |
| **Sum** | 23 | | 23 | | | **χ² = 7.348** |

**7.348 > 3.841** → reject.

> There were significantly more green and fewer albino seedlings than expected for Gg × gg (χ² = 7.348, df = 1, p < 0.05). We reject the hypothesis that the parents were Gg × gg.

**Conclusion:** most likely parents: **Gg × Gg**. (If a table fails to reject both, its sample can't decide; the smaller χ² fits better and the class data settle it.)

Note: the TA meeting said '7.25' aloud; the exact value is 7.35. Same conclusion.

Next: [[Worked - Table B Class Data]] · Back to [[MOC - Calculations]]
