---
description: Draft the right follow-up for each quote that went quiet, sorted by why it stalled (practice data)
---

# The quotes that went quiet (preview)

Most quoted leads don't sign straight away, and some just need more time and a straight answer. In the full system the Mail agent reads HubSpot, sorts each quiet quote by why it stalled, and drafts a short, helpful email series from Tommy that stops the moment someone replies, buys or opts out. Here you do the first email for each, on **made-up practice data**.

## Steps
1. Read `sample-data/quiet-quotes.csv`. Say first, in one line, that these people are fictional.
2. Sort each row into one segment from its `lost_reason` and `stall_notes`. Never guess; if nothing clear is written, it's S5.
   - **S1 Price:** too expensive, over budget, needs finance
   - **S2 Timing:** not ready, after the holidays, moving, renovating, waiting on something
   - **S3 Battery undecided:** unsure about the battery, solar only for now
   - **S4 Comparing:** comparing quotes, got another quote
   - **S5 Went quiet:** no reply, no reason written
3. **Timing.** If the notes say when to get back to them (after Christmas, once the car arrives), still draft the email, but mark it `HOLD until <when>` so it isn't sent early. Don't write "this month" or other words that go stale.
4. Draft the first email for each, from Tommy. Under 120 words, plain text, Australian English, one idea, with a short subject line:
   - Open by name and the system they were quoted for.
   - One line that fits the segment. S1: offer honest options (a different size or layout) rather than pushing the same quote; if they asked about finance, say Tommy will come back to them on it, and promise nothing. S2: no drama, just checking the quote still fits how things stand. S3: say the next email answers the battery questions people ask most. S4: comparing is the right thing to do, and TMEC's quote should stand up next to the others. S5: "I don't know where you landed, so I'm keeping this short."
   - The edge, once: TMEC's own team installs, no subcontractors, local.
   - If it helps a battery quote, the battery fact F1 from `sample-data/rebate-facts.md`, with "(Clean Energy Regulator, checked <date>)". Never a dollar figure, and never to hurry someone who isn't ready.
   - An easy reply: "Just hit reply, even if it's a no."
   - Sign off as Tommy, then `[TMEC footer and unsubscribe line]`.
5. Save all of them in one file, `drafts/quiet-quotes.md`, first line `PREVIEW · made-up practice data · nothing has been sent`, one heading per person with their segment and any HOLD.
6. In the chat, show a table (name, segment, hold, the opening sentence after the greeting), then the full email for one of them, and end with: "Want me to change the tone of any of these?"

## Never
- Promise a saving, a price, finance or an install date.
- Treat a fictional person as real anywhere outside this preview.
