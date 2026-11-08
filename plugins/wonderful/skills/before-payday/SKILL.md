---
name: before-payday
description: What's due before the next paycheck in Wonderful, and whether there's enough for it.
---

Tell the person what's due before their next paycheck and whether they'll have
enough for it.

1. Call `get_due_next` for the bills and subscriptions due before the next
   paycheck, and when that paycheck lands.
2. Call `get_month` for what's left to spend this month.
3. List what's due with each date and amount, then the total. Say plainly
   whether what's left this month covers what's due this month. If it
   doesn't, say by how much.
4. A bill dated next month (the window can run past the month's end) is part
   of next month's plan, not this month's left to spend. Say that, and don't
   count it against this month.

Use only the tools' numbers, and never say what a number includes unless the
tool says so. Follow the money-answers skill's rules.

Write without dashes (no em or en dashes): use a period, comma or colon.
