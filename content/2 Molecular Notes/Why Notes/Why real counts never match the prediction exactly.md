---
title: "Why real counts never match the prediction exactly"
type: molecular
tags:
  - molecular
  - why
description: "Real counts almost never match the prediction exactly because each offspring is a separate chance event, and chance wobbles."
---

Real counts almost never match the prediction exactly because each offspring is a separate chance event, and chance wobbles.

Flip a fair coin 10 times. Exactly 5 heads happens only about 25% of the time; 4, 6, 3 or 7 are all ordinary. The coin isn't broken. The same goes for seedlings: Gg × Gg has a ¼ chance of albino for **each** seedling, but in a tray of 23 you might easily get 3, 5, or 8 albinos.

Sometimes exact matching is literally impossible: 3:1 of 23 is 17.25 : 5.75, and you can't have a quarter of a seedling.

![[Sample size wobble.png|700]]

*Small samples bounce around the true ¼; large samples settle near it.*

So the real question is never "does it match?" but "is the gap small enough to be chance?" That's the job of the chi-square test.

Try it yourself. A student gets 160 purple : 40 yellow on ear 1 and worries it isn't 3:1 (150:50). Should they? Test it: χ² = 100/150 + 100/50 = 2.67 < 3.841. Chance-sized.

See also: [[Random Chance]], [[Sample Size]], [[Why we need a statistical test at all]].
