---
title: "Calc 02 - Writing Gametes"
type: molecular
aliases:
  - "gametes calculation"
  - "finding gametes"
tags:
  - calculation
description: "How to list every gamete a parent can make, for one gene or two."
---

A gamete is a half-set: it takes **exactly one letter of each gene**. If a parent has two different letters for a gene, the gamete could get either one. List every way to pick one letter per gene.

## One gene

| Parent | Gametes |
|---|---|
| RR | R (only one kind) |
| Rr | R, r (½ each) |
| rr | r |

## Two genes (use [[FOIL Method|FOIL]])

Write (R r)(H h). First R·H, Outer R·h, Inner r·H, Last r·h.

| Parent | Gametes |
|---|---|
| RrHh | RH, Rh, rH, rh (¼ each) |
| rrhh | rh only |
| DDHH | DH only |
| DdHh | DH, Dh, dH, dh |
| RRHh | RH, Rh |

## Self-check

Every gamete: one color letter + one shape letter. **Never** two of the same gene (Rr, Hh) in one gamete. Number of gamete types = 2^(number of heterozygous genes).

Try it yourself. Gametes of DdHH? DH and dH.

Concepts: [[Gamete]] · [[Law of Segregation]] · [[Law of Independent Assortment]] · Back to [[MOC - Calculations]]
