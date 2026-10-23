# SQL Server Interview Question Kit

**10 SQL patterns asked in 12 to 35 LPA interviews.** Part 1 has one worked question for every pattern interviewers love, and Part 2 has 20 practice questions with full solutions.

By **Deepankar Sir** | [Instagram @datawithdeepankar](https://instagram.com/datawithdeepankar) | [YouTube @deepankarpathak983](https://youtube.com/@deepankarpathak983)

---

## What's inside

### Part 1: 10 worked questions (multiple choice)

Each question has a table script, a query to read, four options, and a full solution with **The Rule** and a **Pro Tip**.

| # | Pattern | The trap |
|---|---------|----------|
| 1 | Running Totals | `ORDER BY` alone means `RANGE`, so tied rows share a total |
| 2 | Top N Per Group | `ROW_NUMBER` vs `RANK` vs `DENSE_RANK` |
| 3 | Previous Row Comparison | `NULL` from `LAG` makes the comparison UNKNOWN |
| 4 | Gaps and Islands | Date minus `ROW_NUMBER` gives the island ID |
| 5 | Moving Average | `AVG` of an `INT` column returns an `INT` |
| 6 | Pivot | `PIVOT` groups by the remaining columns; missing cells are `NULL` |
| 7 | Duplications | `ORDER BY` inside `ROW_NUMBER` decides which row survives |
| 8 | Window Functions | `LAST_VALUE` needs an explicit frame |
| 9 | Self Joins | A `WHERE` on the right side of a `LEFT JOIN` makes it an `INNER JOIN` |
| 10 | Recursive CTE | The condition tests the row going in, not the row coming out |

### Part 2: 20 practice questions

Two questions per pattern, each with a table script, a hint, and a full solution with expected output.

## How to use this kit

1. Open SQL Server Management Studio (SSMS) and run the table script from the question page.
2. Read the query and predict the output on paper. Do not run it yet.
3. Pick A, B, C or D. Then run the query and compare.
4. Read the solution. Focus on **The Rule** and **The Pro Tip**, they are what the interviewer wants to hear.

## Requirements

- SQL Server 2017 or later (any edition, including Express and Developer)
- SQL Server Management Studio, or Azure Data Studio

## Contents

- Question pages: 2 to 11
- Solution pages: 12 to 21
- Quick answer key: page 22
- Practice set (20 questions): pages 23 to 32
- Practice solutions: pages 33 to 42

## Before your next interview

Most of these questions are not hard SQL. They are small traps: NULL logic, default window frames, data types, and the order in which SQL Server runs each clause. Practise explaining the Rule in your own words and you will stand out from candidates who only memorise syntax.

## Follow for more

A new SQL Server interview question every day on Instagram: **[@datawithdeepankar](https://instagram.com/datawithdeepankar)**

Questions about this kit? Send a DM.

---

*Prepared by Deepankar Sir, MarutiNovaTech.*
