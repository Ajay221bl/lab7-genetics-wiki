---
title: "Critical Value"
aliases:
  - "critical values"
  - "chi-square critical value"
tags:
  - atomic
  - statistics
description: "The critical value is the cut-off χ² from the table (for your df and α) that chance alone exceeds only α of the time; your χ² must reach it to count as significant."
---

> [!abstract] In one sentence
> The critical value is the cut-off χ² from the table (for your df and α) that chance alone exceeds only α of the time; your χ² must reach it to count as significant.

> [!example] Explain it like I'm new (the Feynman way)
> The finish line: if your χ² crosses it, the gap is too big to blame on luck.

## Build it from first principles

For α = 0.05: df 1 → **3.841**; df 2 → 5.991; df 3 → **7.815**; df 4 → 9.488.

Decision rule (manual p. 125):
- χ² **≥** critical value → significant difference → **reject H₀**, p < 0.05.
- χ² **<** critical value → not significant → **fail to reject H₀**, p > 0.05.

TA tip: write 'χ² = …, critical value = …' then the comparison sign, so you don't mix them up. The 'alligator' (< or >) eats the bigger number.

> [!question]- Test yourself: χ² = 0.130, df = 1. Reject?
> **Answer:** No: 0.130 < 3.841, fail to reject.

## Connected ideas

- [[Critical Value Table]]
- [[Degrees of Freedom]]
- [[Level of Significance]]
- [[Calc 09 - Looking Up the Critical Value]]
- [[Calc 10 - Comparing and Deciding]]

Browse more in [[MOC - Statistics and Chi-Square]] · [[Vault Index|Index]]
