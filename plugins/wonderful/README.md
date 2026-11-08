# Wonderful for Claude

Wonderful is a budgeting app for one person or a couple. This plugin connects
your Wonderful account to Claude, so you can ask about your money where you
already work: how the month is going, what's due before payday, whether a
charge looks odd, and whether you can afford something.

It only reads. Changes to your plan happen in Wonderful itself.

## Install

In Claude Code:

```
/plugin marketplace add wonderful-money/wonderful-claude
/plugin install wonderful@wonderful
```

In Claude or Cowork, add the marketplace `wonderful-money/wonderful-claude` from the
plugins screen and install Wonderful.

## Connect

- **Claude Code:** install the plugin, run `/mcp`, pick `wonderful` and sign in
  in your browser.
- **Claude and Cowork:** add the plugin, open its Connectors tab and connect
  Wonderful. You sign in with your Wonderful email and allow Claude to read.

You can disconnect any time in Wonderful, under Settings, AI apps.

## Commands

- `/wonderful:check-in [month]`: how the month is going and what's left to spend.
- `/wonderful:before-payday`: what's due before your next paycheck.
- `/wonderful:odd-charges`: charged twice, new fees, prices that went up.
- `/wonderful:can-i-buy <item and price>`: whether it fits this month.
- `/wonderful:cancel <subscription>`: the company's own cancel page.

Or just ask in your own words.

## Privacy

Claude reads your Wonderful data only after you sign in and allow it, and only
through read-only tools. Emails and long account numbers are taken out of every
answer. See https://wonderful.money/privacy.
