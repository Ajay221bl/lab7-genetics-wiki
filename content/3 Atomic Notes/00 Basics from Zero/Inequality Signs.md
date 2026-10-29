---
title: "Inequality Signs"
type: atomic
aliases:
  - "less than"
  - "greater than"
  - "inequality"
  - "alligator trick"
tags:
  - atomic
  - basics-from-zero
description: "The signs < and  say which of two numbers is bigger: 0.130 < 3.841 reads '0.130 is less than 3.841', and 7.348  3.841 reads '7.348 is greater than 3.841'."
---

The signs < and > say which of two numbers is bigger: 0.130 < 3.841 reads "0.130 is less than 3.841", and 7.348 > 3.841 reads "7.348 is greater than 3.841".

The TA trick for remembering them: the sign is an alligator's open mouth, and the alligator always eats the bigger number. The wide open side faces the bigger number, the pointy closed side faces the smaller one.

![[Inequality signs - the open side eats the bigger number.png|700]]

*The open side of the sign always faces the bigger number.*

Why does this tiny symbol matter so much in Lab 7? Because the whole decision of a chi-square test is one inequality. You write χ² = …, critical value = …, and then put the right sign between them. Get the sign backwards and you reach the opposite conclusion.

Results statements use it too: p > 0.05 means "not significant"; p < 0.05 means "significant".

There are versions with a line under them: ≥ means "greater than or equal to". The manual's rule is that χ² **greater than or equal to** the critical value means reject.

The trap: comparing the wrong pair. You compare χ² with the critical value. You never compare χ² with 0.05.

Try it yourself. χ² = 4.2, critical value = 3.841. Which sign goes between them, and what do you decide? 4.2 > 3.841, so reject H₀.

See also: [[Critical Value]], [[Calc 10 - Comparing and Deciding]], [[P-Value]].
