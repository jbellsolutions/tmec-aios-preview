---
description: Tommy's morning brief from the sample data, with a short yes/no list
---

# Morning brief (preview)

Write Tommy's morning brief from what's in this folder, the way the full system does every morning. In the full system "since yesterday" means what the specialists did overnight; here the sample is fixed, so the brief says "in the sample" instead.

## Read
- `sample-data/radar-posts.json`: count the leads by `intent` (hot, medium, low) where `is_lead` is true, and note how many hot ones are in Queensland (from `location_hint`).
- `sample-data/partner-prospects.csv`: how many trades are on the starter list, and which trades.
- `sample-data/quiet-quotes.csv`: how many quotes went quiet, by why they stalled. (Fictional practice data.)
- `sample-data/rebate-facts.md`: the next rebate step and its date.
- `drafts/`: anything already drafted and waiting on Tommy.
- `vault/big-list.md`, if it exists: how many questions are answered.

## Write
Under 200 words, in this order:

1. **Needs you** (at most 5), each a yes/no. Use real choices from the files: "Draft replies to the 4 hot radar posts?", "Draft a first hello to a trade on the partner list?", "Draft follow-ups for the 6 quiet quotes (made-up practice data)?". If a draft already exists in `drafts/`, ask for his yes on that instead of offering to draft it again.
2. **In the sample**, one line per bucket, each with its number and the file it came from: Radar, Partners, Quiet quotes. Then one line: "Ads, newsletter and content: built in the full system, not in the preview."
3. **Coming up:** the next rebate step from `rebate-facts.md`, with its source and check date. No dollar figures.
4. **Big list:** how many of the 9 questions are answered, or "not started: say /big-list".

Then save the brief at the top of `vault/daily/<today>.md` (create it; first line `PREVIEW · sample data · nothing has been sent`, then the brief, then an empty `## Log`), and show it in the chat.

## Never
- Invent a number. A bucket with no file is "not in the preview".
- Say anything was sent, posted or booked.
