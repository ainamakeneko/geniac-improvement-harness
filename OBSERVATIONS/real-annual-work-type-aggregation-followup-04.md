# Real Pilot 1 — Follow-up 04: workbook structure notes

> REAL FACILITY OBSERVATION. Content-free structural description only. No service-user records or identifying values are included.

## OBSERVED

- One Excel file represents one month.
- The relevant sheet is described as `作業記録`.
- The operator describes columns as:
  - A: 日付
  - B: 利用者
  - C: 作業種類
  - D: 備考
- A blank indicates no work.
- Example work categories include 清掃, 部品組立, 販売, 陶芸, and others.
- The intended annual output is a table of annual counts by 利用者 × 作業種類.
- A required high-level verification is that monthly totals and annual totals agree.
- The operator states that when one person performs multiple kinds of work on the same day, multiple cells may contain a `○`.

## IMPORTANT STRUCTURAL AMBIGUITY

The statement `C: 作業種類` is not yet fully consistent with `multiple cells may contain ○ for the same person/day`.

Possible interpretations include, but are not limited to:
1. each row has a single work-category value in column C, and multiple rows represent multiple work types; or
2. work categories are actually represented across multiple category columns with `○` marks; or
3. column C contains a higher-level grouping while additional columns encode individual categories.

Do not choose among these interpretations without confirmation.

## UNKNOWN

- Exact row/column layout of the relevant table.
- Whether category names are stored as cell values or column headers with `○` marks.
- How multiple categories for one person/day are represented in the real workbook.
- Whether merged cells, totals, formulas, header repeats, correction rows, or month-to-month layout variations exist.
- The exact annual output layout beyond `利用者 × 作業種類` counts.

No prototype should use real personal data. A synthetic prototype may proceed only after the minimum encoding ambiguity above is resolved.