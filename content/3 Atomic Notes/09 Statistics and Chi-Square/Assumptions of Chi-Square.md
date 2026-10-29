---
title: "Assumptions of Chi-Square"
type: atomic
aliases:
  - "chi-square assumptions"
tags:
  - atomic
  - statistics-and-chi-square
description: "The chi-square test only works properly when its assumptions hold:"
---

The chi-square test only works properly when its assumptions hold:

- **Counts, not percentages or measurements** ([[Why chi-square needs counts not percentages]]).
- **Independent observations**: each kernel or seedling counted once, and one doesn't affect another.
- **Categories that don't overlap**, and every individual fits in exactly one.
- **Expected counts not too small**: a common rule is every E at least 5. With tiny E, dividing by E blows small gaps up into huge numbers.
- **Hypothesis chosen beforehand** ([[A Priori Hypothesis]]).

Try it yourself. A student converts counts to percentages before the test. What goes wrong? χ² changes with the scale, so the result is meaningless.

See also: [[Chi-Square Test]], [[Why chi-square needs counts not percentages]].

Learn more: [Wikipedia: Chi-squared test#Assumptions](<https://en.wikipedia.org/wiki/Chi-squared_test#Assumptions>)
