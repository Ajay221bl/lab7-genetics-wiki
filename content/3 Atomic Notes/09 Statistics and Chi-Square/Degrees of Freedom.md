---
title: "Degrees of Freedom"
type: atomic
aliases:
  - "d.f."
tags:
  - atomic
  - statistics-and-chi-square
description: "Degrees of freedom (df) is how many categories are free to vary once you know the total: categories − 1."
---

Degrees of freedom (df) is how many categories are free to vary once you know the total: categories − 1.

Imagine 23 seedlings split into green and albino. Tell me green = 18 and I already know albino = 5. Only one number was "free". With 4 categories and a known total, you can choose 3; the last is forced ([[Why degrees of freedom are categories minus one]]).

![[Degrees of freedom - the forced last count.png|700]]

*With a fixed total, once all but one category is filled in, the last one has no choice.*

Why it matters: more categories means more places for chance gaps to pile up, so χ² naturally runs bigger, and the cut-off has to be higher. df picks the row of the table.

| Categories | df | Critical value (0.05) |
|---|---|---|
| 2 | 1 | 3.841 |
| 3 | 2 | 5.991 |
| 4 | 3 | 7.815 |
| 5 | 4 | 9.488 |

Try it yourself. Ear 5 (four phenotypes): df? 3, critical value 7.815.

See also: [[Critical Value]], [[Categories]], [[Calc 08 - Degrees of Freedom]], [[Why ear 5 uses a different critical value]].

Learn more: [Wikipedia: Degrees of freedom (statistics)](<https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics)>)
