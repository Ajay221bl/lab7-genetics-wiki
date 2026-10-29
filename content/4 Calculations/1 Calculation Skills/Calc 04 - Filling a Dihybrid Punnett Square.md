---
title: "Calc 04 - Filling a Dihybrid Punnett Square"
aliases:
  - "dihybrid square"
tags:
  - calculation
description: "Step-by-step filling and grouping of a 4 by 4 Punnett square."
---

> [!example] The Feynman version
> Same idea as the small square, just with four gametes per parent. Then sort the 16 boxes into piles by what the kernel looks like.

## Steps (RrHh × RrHh)

1. FOIL each parent: RH, Rh, rH, rh ([[Calc 02 - Writing Gametes]]).
2. 4 × 4 grid. In each box, write the two color letters together and the two shape letters together.

| | RH | Rh | rH | rh |
|---|---|---|---|---|
| **RH** | RRHH | RRHh | RrHH | RrHh |
| **Rh** | RRHh | RRhh | RrHh | Rrhh |
| **rH** | RrHH | RrHh | rrHH | rrHh |
| **rh** | RrHh | Rrhh | rrHh | rrhh |

3. Sort into phenotypes. A box is purple if it has ≥1 R, smooth if ≥1 H:
   - purple smooth (R_H_): 9 boxes
   - purple wrinkled (R_hh): 3
   - yellow smooth (rrH_): 3
   - yellow wrinkled (rrhh): 1
4. **Check with the [[Product Rule]]**: ¾ × ¾ = 9/16 ✓.

Genotype counts (out of 16): 1 RRHH, 2 RRHh, 1 RRhh, 2 RrHH, 4 RrHh, 2 Rrhh, 1 rrHH, 2 rrHh, 1 rrhh.

## Shortcut when one parent is rrhh

rrhh makes only rh, so every row is identical: one row is the whole answer (RrHh, Rrhh, rrHh, rrhh → 1 : 1 : 1 : 1).

> [!question]- Try it: How many of the 16 boxes are RrHh?
> **Answer:** 4.

Concepts: [[Dihybrid Cross]] · [[9-3-3-1 Ratio]] · [[FOIL Method]] · Back to [[MOC - Calculations]]
