---
title: "Calc 10 - Comparing and Deciding"
aliases:
  - "decision rule"
tags:
  - calculation
description: "Comparing chi-square with the critical value and deciding to reject or fail to reject."
---

> [!example] The Feynman version
> The critical value is a fence. If your χ² stays inside the fence, the gap is the kind luck makes all the time. If it jumps the fence, luck rarely does that, so you suspect something real.

## Write it like this (TA tip)

χ² = ___ ; critical value = ___ ; then the sign.

| Comparison | p | Decision | Meaning |
|---|---|---|---|
| χ² **<** critical | p > 0.05 | **fail to reject H₀** | data fit the prediction; gap is chance |
| χ² **≥** critical | p < 0.05 | **reject H₀** | data don't fit; something other than chance |

The 'alligator' sign eats the bigger number: 0.130 < 3.841; 7.348 > 3.841.

## Traps

- Comparing χ² with 0.05. No: 0.05 only chooses the column.
- 'Small χ², so reject.' Backwards: small χ² = small gap = fail to reject.
- 'We proved it.' No: fail to reject is not proof.

Concepts: [[Critical Value]] · [[Reject the Null Hypothesis]] · [[Fail to Reject the Null Hypothesis]] · [[P-Value]] · Back to [[MOC - Calculations]]
