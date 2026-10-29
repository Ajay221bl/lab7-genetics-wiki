---
title: "Rounding and Decimal Places"
type: atomic
aliases:
  - "rounding"
  - "decimal places"
tags:
  - atomic
  - basics-from-zero
description: "Rounding means shortening a number to fewer decimal places, and the rule for this lab is: keep plenty of decimals while you work, and round only the final χ²."
---

Rounding means shortening a number to fewer decimal places, and the rule for this lab is: keep plenty of decimals while you work, and round only the final χ².

Why does it matter? Because small rounding errors pile up. Suppose you round E to whole numbers too early: 17.25 becomes 17 and 5.75 becomes 6. Now the O − E column is off, the squares are off, and the final χ² can shift. Usually that doesn't change the decision. But when χ² lands near the critical value, as one table in the TA meeting did (just under 3.841), early rounding can flip "fail to reject" into "reject".

A practical rule: keep at least two decimal places for E and three or four for each (O − E)²/E, then give χ² to two or three decimals.

How to round: look at the next digit. 5 or more, round up; less than 5, leave it. 0.0326 to three places is 0.033; 3.6739 is 3.674.

Try it yourself. Round 7.3478 to two decimal places. 7.35.

See also: [[Calc 07 - The Chi-Square Grid]], [[Expected Value]].
