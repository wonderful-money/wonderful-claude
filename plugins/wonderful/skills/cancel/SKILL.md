---
name: cancel
description: How to cancel a subscription, with the company's own cancel page, and what it costs the person now.
argument-hint: "<subscription name, e.g. Hulu>"
---

The person wants to cancel: $ARGUMENTS

1. Call `how_to_cancel` with the name.
2. If `found` is true, give that page as the way to cancel. Say steps only when
   the result states them plainly. If `found` is false, never write a link of
   your own: say to cancel in their account with that company, or in their
   phone's subscriptions if they signed up through the App Store or Google
   Play.
3. Call `get_recurring` to say what it costs them now and when it next charges.

Wonderful never cancels anything itself. After they cancel, they can ask
Wonderful at https://app.wonderful.money to watch for the charge, so they hear
if it comes again.

Write without dashes (no em or en dashes): use a period, comma or colon.
