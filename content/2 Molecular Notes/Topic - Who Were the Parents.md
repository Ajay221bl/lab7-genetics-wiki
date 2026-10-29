---
title: "Topic - Who Were the Parents"
aliases:
  - "seedling experiment"
  - "green and albino experiment"
tags:
  - molecular
description: "The logic of the green and albino seedling experiment: from a tray of offspring back to the parents' genotypes."
---

> [!abstract] The big question
> You're given a tray of baby corn plants, some green, some white, all from the same two parents. Who were the parents?

## The story in plain words (detective style)

**Clue 1: there are albino seedlings.** An albino is gg ([[Albino Seedling]]). It got one g from each parent. So **both parents carry g**. That rules out any parent that is GG.

**Clue 2: there are green seedlings too.** So at least one parent carries G.

Of the six possible crosses ([[Worked - Table A Six Parental Crosses|Table A]]), only two survive: **Gg × Gg** (predicts 3 : 1) and **Gg × gg** (predicts 1 : 1).

**Clue 3: the counts.** Count the tray ([[Seedling Tray]]), compute expected numbers for each suspect, and run a [[Chi-Square Test|chi-square test]] against each ([[Worked - Table B Group Data|Table B]]). Whichever cross is rejected is ruled out. Pool the whole class for a bigger sample ([[Worked - Table B Class Data]]), then think about why that helps ([[Worked - Question 9 Sample Size]]).

With the sample counts (18 green : 5 albino): Gg × Gg gives χ² = 0.130 (fits), Gg × gg gives χ² = 7.348 (rejected). Verdict: the parents were most likely **Gg × Gg**, two green carriers.

## Build it in order

[[Green Seedling]] → [[Albino Seedling]] → [[Monogenic Trait]] → [[Worked - Table A Six Parental Crosses]] → [[Calc 06 - Expected Counts]] → [[Worked - Table B Group Data]] → [[Worked - Table B Class Data]] → [[Worked - Question 9 Sample Size]]

> [!question]- Check yourself: If a tray had only green seedlings, could you tell the parents?
> **Answer:** Not uniquely: GG × GG, GG × Gg, GG × gg (and maybe Gg × Gg by bad luck in a tiny sample) all give green.
