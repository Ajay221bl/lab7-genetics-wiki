---
title: "Why we square the gaps in chi-square"
type: molecular
tags:
  - molecular
  - why
description: "We square the gaps because the raw gaps (O − E) always add up to zero, so you have to remove the signs to measure the total mismatch, and squaring also makes big gaps count more than small ones."
---

We square the gaps because the raw gaps (O − E) always add up to zero, so you have to remove the signs to measure the total mismatch, and squaring also makes big gaps count more than small ones.

Work it out with the tray: O − E = 18 − 17.25 = +0.75 for green, 5 − 5.75 = −0.75 for albino. Add them: 0. That says "perfect fit", which is nonsense. It's always zero, because the observed and expected totals are the same, so every extra in one category is a shortfall in another.

![[Why square the gaps.png|700]]

*Raw gaps cancel to zero; squared gaps are all positive and add up.*

Squaring makes every gap positive. As a bonus, a gap of 10 becomes 100 while a gap of 2 becomes 4, so one large miss raises more alarm than several tiny ones, which is what you want.

Try it yourself. Why not just ignore the minus signs (absolute values)? You could, but squaring is what the χ² distribution and its table are built on.

See also: [[Chi-Square Statistic]], [[Squares and Square Roots]], [[Why we divide by the expected count]].
