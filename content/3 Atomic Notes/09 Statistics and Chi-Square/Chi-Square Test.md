---
title: "Chi-Square Test"
type: atomic
aliases:
  - "chi-square"
  - "chi square"
  - "χ² test"
  - "chi-squared test"
tags:
  - atomic
  - statistics-and-chi-square
description: "The chi-square (χ², said 'kai-square') test checks whether observed counts are close enough to expected counts that the difference could be chance."
---

The chi-square (χ², said "kai-square") test checks whether observed counts are close enough to expected counts that the difference could be chance.

The whole test in one picture: for each category, find the gap between what you saw and what you expected; square it; divide by expected; add them up. That total is χ². Compare it with a cut-off (the [[Critical Value|critical value]]). Below the line: the gap is chance-sized, keep H₀. Above: too big for chance, reject H₀.

![[Chi-square in six steps.png|700]]

*The six steps of the lab's chi-square, from hypothesis to results statement.*

Steps used in the lab:

1. State H₀ and the expected ratio ([[A Priori Hypothesis|before]] counting).
2. Turn the ratio into expected counts: E = fraction × total ([[Calc 06 - Expected Counts]]).
3. For each category: (O − E)² / E ([[Calc 07 - The Chi-Square Grid]]).
4. Add them up: that's χ².
5. Degrees of freedom = categories − 1; look up the critical value at 0.05.
6. Compare and write the results statement.

Try it yourself. Tray: 18 green, 5 albino, H₀ = 3:1. E = 17.25 and 5.75. χ² = 0.75²/17.25 + 0.75²/5.75 = 0.033 + 0.098 = 0.130 < 3.841. Keep H₀.

See also: [[Chi-Square Statistic]], [[Critical Value]], [[Topic - The Chi-Square Goodness of Fit Test]].

Learn more: [Wikipedia: Chi-squared test](<https://en.wikipedia.org/wiki/Chi-squared_test>) · [Khan Academy: Chi-square statistic for hypothesis testing](<https://www.khanacademy.org/math/statistics-probability/inference-categorical-data-chi-square-tests>)
