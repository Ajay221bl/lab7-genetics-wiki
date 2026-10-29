---
title: "Why chi-square needs counts not percentages"
type: molecular
tags:
  - molecular
  - why
description: "Chi-square needs raw counts because the size of χ² depends on how many things you counted; percentages throw away the sample size, so the test can't judge how much wobble to expect."
---

Chi-square needs raw counts because the size of χ² depends on how many things you counted; percentages throw away the sample size, so the test can't judge how much wobble to expect.

Try it: 18:5 as counts gives χ² = 0.130. As percentages (78.3% : 21.7%, "out of 100") you'd get χ² ≈ 0.56, which is just a different number for the same data. And 1.8 : 0.5 (out of 2.3) would give 0.013. Scale up or down and χ² changes, so only the real counts give the true answer.

The intuition: 3 heads out of 4 and 750 out of 1,000 are both 75%, but only the second should surprise you. Counts carry that information; percentages lose it.

Try it yourself. A student enters percentages (77 and 23) instead of ear 1's real counts (154 and 46). What goes wrong? χ² is halved, so the test is too lenient.

See also: [[Assumptions of Chi-Square]], [[Percent]], [[Sample Size]].
