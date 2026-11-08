---
name: check-in
description: Check in on this month in Wonderful. How the month is going against the plan, what's left to spend, and anything off pace.
argument-hint: "[month, e.g. September]"
---

Check in on the person's month in Wonderful. If they named a month
($ARGUMENTS), use that one; otherwise this month.

1. Call `get_month_score` and `get_month` for the month.
2. Lead with what's left to spend, from `toSpend` (the same numbers Wonderful's
   Home shows). Then how spending compares with what the plan allows.
3. Name anything off pace: a category well past its line (say why, from the
   tool's `why`), or a saving part behind.
4. If the month's `synopsis` names one change that would matter most, end on it.

Keep it to a short paragraph and a few bullets. Follow the money-answers
skill's rules: never suggest saving less, and changes happen in Wonderful.

Write without dashes (no em or en dashes): use a period, comma or colon.
