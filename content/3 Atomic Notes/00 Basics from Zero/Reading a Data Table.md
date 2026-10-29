---
title: "Reading a Data Table"
type: atomic
aliases:
  - "tables"
  - "rows and columns"
tags:
  - atomic
  - basics-from-zero
description: "In a data table, each row is one category (or one thing) and each column is one kind of information about it."
---

In a data table, each row is one category (or one thing) and each column is one kind of information about it.

The chi-square table in the manual has one row per phenotype (green, albino) and one column per step (O, expected frequency, E, O − E, (O − E)², (O − E)²/E). To fill it, work across a row from left to right, then down to the next row; at the end, add the last column.

The critical value table on p. 125 is read differently: rows are degrees of freedom, columns are α levels. Find your row (df), slide across to your column (0.05), and the number where they meet is your critical value. It's like a bus timetable: find your stop, find your time, read where they cross.

The trap: reading the critical value table by the wrong axis (for example using df = 3's row but the 0.01 column).

Try it yourself. In the table on p. 125, where do the row df = 3 and the column 0.05 meet? 7.815.

See also: [[Critical Value Table]], [[Calc 07 - The Chi-Square Grid]], [[Calc 09 - Looking Up the Critical Value]].
