---
name: can-i-buy
description: Whether something fits this month's plan in Wonderful. A want is checked against guilt-free money left after bills, a need against all spending left after bills.
argument-hint: "<what it is and its price, e.g. \"headphones $180\">"
---

The person wants to know if they can buy something: $ARGUMENTS

1. Get the price. If they didn't give one, ask for it. Links can't be opened
   from here, so ask for the price rather than a link.
2. Decide if it's a need (groceries, a repair, medicine) or a want. If it's
   unclear, treat it as a want.
3. Call `can_i_buy` with `price` and `need`.
4. Say the `verdict`: its `headline`, then its `lines`, in the person's own
   numbers. Don't redo the arithmetic.

Never suggest saving less to make room. If it doesn't fit, say so plainly and
say when it would (after the next paycheck, or next month).

Write without dashes (no em or en dashes): use a period, comma or colon.
