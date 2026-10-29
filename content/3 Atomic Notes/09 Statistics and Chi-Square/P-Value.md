---
title: "P-Value"
type: atomic
aliases:
  - "p value"
  - "probability value"
tags:
  - atomic
  - statistics-and-chi-square
description: "The p-value is the chance of getting a gap at least as big as yours if H₀ were true."
---

The p-value is the chance of getting a gap at least as big as yours **if H₀ were true**.

Small p means "this would be a rare fluke if H₀ were true", so you start doubting H₀. If p < 0.05, reject.

The lab doesn't compute p directly. Instead you compare χ² with the critical value, which is the same decision ([[Why we compare chi-square with the critical value not with 0.05]]): χ² bigger than the critical value is the same as p smaller than 0.05.

The trap: p is **not** the chance that H₀ is true. It's how surprising your data would be if H₀ were true.

Try it yourself. χ² = 0.130 with df 1. Is p above or below 0.05? Above (0.130 < 3.841), so keep H₀.

See also: [[Level of Significance]], [[Critical Value]], [[Chi-Square Distribution]].

Learn more: [Wikipedia: P-value](<https://en.wikipedia.org/wiki/P-value>)
