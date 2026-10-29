---
title: "Topic - The Chi-Square Goodness of Fit Test"
type: molecular
aliases:
  - "chi-square topic"
tags:
  - molecular
description: "The complete chi-square test from first principles, with every step and why it exists."
---

**The big question:** How do you turn 'observed vs expected' into one number and a yes/no decision?

## The story in plain words

You want one number that says how badly the data miss the prediction. Build it step by step, the way you'd invent it yourself:

1. **Gap per category**: O − E. ([[Observed Value]], [[Expected Value]])
2. **Problem**: positive and negative gaps cancel out. **Fix**: square them. Bonus: big misses count extra.
3. **Problem**: a miss of 5 is huge if you expected 5, tiny if you expected 500. **Fix**: divide by E.
4. **Combine**: add across categories ([[Summation|Σ]]). That's [[Chi-Square Statistic|χ²]].

Now, how big is 'too big'? Luck alone produces some χ² every time. Statisticians worked out the [[Chi-Square Distribution|distribution]] of χ² under pure luck. It depends on how many categories were free to vary ([[Degrees of Freedom|df = k − 1]], with k = number of [[Categories|categories]]). The [[Critical Value|critical value]] is the χ² that luck exceeds only 5% of the time ([[Level of Significance|α = 0.05]]), read from the [[Critical Value Table|table]].

**Decision**: χ² < critical → fail to reject H₀ (fits). χ² ≥ critical → reject H₀ (doesn't fit).

Rules of the game: [[Assumptions of Chi-Square]] (counts, independence).

## The full calculation path (in the Calculations folder)

[[Calc 06 - Expected Counts]] → [[Calc 07 - The Chi-Square Grid]] → [[Calc 08 - Degrees of Freedom]] → [[Calc 09 - Looking Up the Critical Value]] → [[Calc 10 - Comparing and Deciding]] → [[Calc 11 - Writing the Results Statement]]

Practice: [[Worked - Coin Toss Example]], [[Worked - Table B Group Data]], [[Worked - Chi-Square on Corn Ear 1]], [[Worked - Chi-Square on Corn Ear 5]].

## Build it in order

[[Goodness of Fit]] → [[Chi-Square Test]] → [[Observed Value]] → [[Expected Value]] → [[Summation]] → [[Chi-Square Statistic]] → [[Test Statistic]] → [[Categories]] → [[Degrees of Freedom]] → [[Chi-Square Distribution]] → [[Critical Value]] → [[Critical Value Table]] → [[Assumptions of Chi-Square]]

Try it yourself. Why is χ² never negative? Every term is a square divided by a positive E.
