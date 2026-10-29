---
title: "Topic - Hypothesis Testing"
type: molecular
aliases:
  - "hypothesis testing topic"
tags:
  - molecular
description: "The logic of null hypotheses, alternatives, significance and decisions."
---

**The big question:** How do scientists decide, fairly, whether a difference is real or just luck?

## The story in plain words

It works like a courtroom.
1. **Presume innocence**: the [[Null Hypothesis|null hypothesis]] H₀ says 'no real difference; any gap is chance'.
2. **Name other suspects** in advance: [[Alternative Hypothesis|alternative hypotheses]] H₁, H₂.
3. **Set the standard of proof before the trial**: [[Level of Significance|α = 0.05]].
4. **Look at the evidence**: compute a [[Test Statistic|test statistic]] (χ²).
5. **Verdict**: if the evidence is beyond the bar (χ² ≥ [[Critical Value|critical value]], [[P-Value|p]] < 0.05), [[Reject the Null Hypothesis|reject H₀]]: '[[Statistically Significant|significant]]'. Otherwise [[Fail to Reject the Null Hypothesis|fail to reject]] ('not guilty', which isn't 'proven innocent'; manual calls it a [[Retained Null Hypothesis|retained H₀]]).
6. **Report** it in a [[Results Statement|results statement]].

Even a fair court sometimes convicts an innocent: that's a [[Type I Error]], and α is how often you allow it.

The prediction must come before the data ([[A Priori Hypothesis]]).

## Build it in order

[[Statistical Analysis]] → [[Hypothesis]] → [[A Priori Hypothesis]] → [[Null Hypothesis]] → [[Alternative Hypothesis]] → [[Level of Significance]] → [[P-Value]] → [[Statistically Significant]] → [[Reject the Null Hypothesis]] → [[Fail to Reject the Null Hypothesis]] → [[Retained Null Hypothesis]] → [[Type I Error]] → [[Results Statement]]

Try it yourself. Why don't we 'accept' H₀? Failing to find a difference doesn't prove there isn't one; more data might reveal it.
