---
title: "Why we compare chi-square with the critical value not with 0.05"
type: molecular
tags:
  - molecular
  - why
description: "We compare χ² with the critical value, not with 0.05, because they're different kinds of numbers: χ² is a mismatch score, 0.05 is a probability."
---

We compare χ² with the critical value, not with 0.05, because they're different kinds of numbers: χ² is a mismatch score, 0.05 is a probability. The critical value is 0.05 translated into χ² units.

Comparing χ² with 0.05 is like comparing a height in centimetres with a percentage. The table does the conversion: for df 1, a χ² of 3.841 is the point that chance alone exceeds 5% of the time. So "χ² > 3.841" means exactly the same as "p < 0.05".

The trap: a student gets χ² = 0.427 and says "it's bigger than 0.05, so reject". Wrong comparison. 0.427 < 3.841, so keep H₀.

Try it yourself. χ² = 2.56 (the coin toss, df 1). Decision? 2.56 < 3.841: fail to reject; the coin is fair.

See also: [[Critical Value]], [[P-Value]], [[Level of Significance]], [[Worked - Coin Toss Example]].
