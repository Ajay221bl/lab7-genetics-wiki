---
title: "Why we divide by the expected count"
type: molecular
tags:
  - molecular
  - why
description: "We divide by E because a gap's importance depends on its size relative to what you expected: being off by 5 is huge if you expected 10, and trivial if you expected 1,000."
---

We divide by E because a gap's importance depends on its size relative to what you expected: being off by 5 is huge if you expected 10, and trivial if you expected 1,000.

Missing a bus by 5 minutes matters on a 10-minute trip; it doesn't on a 10-hour flight. Dividing by E turns every gap into a "relative surprise", so categories of different sizes can be added fairly.

![[Why divide by E.png|700]]

*The same gap of 5 is a big deal against E = 10 and almost nothing against E = 1,000.*

Work it out: (5)²/10 = 2.5, but (5)²/1000 = 0.025. Same gap, 100 times less surprising.

Try it yourself. Why does a small E category (like 1/16 on ear 5) need a careful count? Small gaps there count a lot.

See also: [[Chi-Square Statistic]], [[Expected Value]].
