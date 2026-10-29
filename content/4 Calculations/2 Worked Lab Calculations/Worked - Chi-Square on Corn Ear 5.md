---
title: "Worked - Chi-Square on Corn Ear 5"
aliases:
  - "chi-square ear 5"
tags:
  - calculation
description: "Chi-square test of Corn Ear 5 against 9:3:3:1 with df 3 (p. 135)."
---

> [!warning] Sample data
> These counts are the answer key's example numbers (the 18 green : 5 albino tray is from the TA meeting; the rest are made up). Swap in your room's real counts; the method stays the same.

## a. Hypotheses

- **H₀**: the four kernel phenotypes on ear 5 are not significantly different from 9 : 3 : 3 : 1 (RrHh × RrHh).
- **H₁**: they differ because the parents were a different cross.
- **H₂**: they differ because the genes don't assort independently (linked on one chromosome), or kernel survival differs, or counting error.

## b. Chi-square

| Phenotype | O | Expected fraction | E | O − E | (O − E)² | (O − E)²/E |
|---|---|---|---|---|---|---|
| Purple smooth | 88 | 9/16 | 84.38 | 3.63 | 13.141 | 0.156 |
| Purple wrinkled | 27 | 3/16 | 28.13 | −1.13 | 1.266 | 0.045 |
| Yellow smooth | 26 | 3/16 | 28.13 | −2.13 | 4.516 | 0.161 |
| Yellow wrinkled | 9 | 1/16 | 9.38 | −0.38 | 0.141 | 0.015 |
| **Sum** | 150 | | 150 | | | **χ² = 0.376** |

df = 4 − 1 = **3** → critical **7.815** (not 3.841). 0.376 < 7.815.

## c. Results statement

> There was no significant difference between the observed and expected numbers of the four kernel phenotypes on ear 5 (χ² = 0.376, df = 3, p > 0.05). We fail to reject H₀: the counts fit 9 : 3 : 3 : 1, so ear 5 most likely came from RrHh × RrHh, and the color and shape genes appear to assort independently.

If a real ear rejects H₀, first rule out counting errors (rows counted twice, borderline kernels), then say which class was over or under.

Back to [[MOC - Calculations]]
