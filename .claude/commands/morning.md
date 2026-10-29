---
description: Tommy's morning brief from the sample data, with a short yes/no list
---

# Morning brief (preview)

Write Tommy's morning brief from what's in this folder, the way the full system does every morning.

## Read
- `sample-data/radar-posts.json`: count the leads by `intent` (hot, medium, low) where `is_lead` is true, and note how many hot ones are in Queensland (from `location_hint`).
- `sample-data/partner-prospects.csv`: how many trades are on the starter list, and which trades.
- `sample-data/quiet-quotes.csv`: how many quotes went quiet, by why they stalled. (Fictional practice data.)
- `sample-data/rebate-facts.md`: the next rebate step and its date.
- `drafts/`: anything already drafted and waiting on Tommy.
- `vault/big-list.md`, if it exists: how many items are on it.

## Write
Under 200 words, in this order:

1. **Needs you** (at most 5, oldest first), each a yes/no. Use real choices from the files, for example: "Draft replies to the 4 hot radar posts?", "Draft a first hello to 5 trades on the partner list?", "Draft follow-ups for the quiet quotes?". If something is already in `drafts/`, ask for a yes on that instead.
2. **Since yesterday**, one line per bucket, each with its number and the file it came from:
   - Radar · Partners · Quiet quotes · Ads · Newsletter · Content
   - Ads, Newsletter and Content have no sample data in the preview: say "not in the preview" for each, in one line together.
3. **Coming up:** the next rebate step from `rebate-facts.md`, with its source and check date.
4. **Big list:** how many items are on it, or "not started: say /big-list".

Then save the brief at the top of `vault/daily/<today, YYYY-MM-DD>.md` (create it; first line `PREVIEW · sample data · nothing has been sent`), and show it in the chat.

## Never
- Invent a number. A bucket with no file is "not in the preview".
- Say anything was sent, posted or booked.
