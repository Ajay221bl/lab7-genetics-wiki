---
title: "Calc 08 - Degrees of Freedom"
aliases:
  - "df calculation"
tags:
  - calculation
description: "Calculating degrees of freedom as number of phenotype categories minus one."
---

> [!example] The Feynman version
> Imagine filling in your counts one category at a time, knowing the total. You get to choose freely until the last category, which is forced to make the total come out right. df counts the free choices.

## Formula

**df = k − 1**, where k = number of **phenotype categories** you counted.

| Data | k | df |
|---|---|---|
| coin (heads/tails) | 2 | 1 |
| green/albino | 2 | 1 |
| ear 1 purple/yellow | 2 | 1 |
| ear 4 or 5 (four kernel types) | 4 | 3 |
| Lab 8 (five colors) | 5 | 4 |

Wrong ways students try: number of plants − 1; number of genotypes − 1; number of rows − 1.

Concepts: [[Degrees of Freedom]] · [[Categories]] · Back to [[MOC - Calculations]]
