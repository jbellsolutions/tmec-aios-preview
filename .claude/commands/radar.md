---
description: Read the real radar sample, pick the best Queensland buyers, and draft a helpful reply to each in TMEC's voice
---

# Radar (preview)

The full Lead Radar runs every day on its own server, finds people asking about solar, batteries and EV chargers, and drafts a reply for Tommy to post himself. Here you do the same on a real sample: public Australian Reddit posts read by hand on 28 October 2026, no usernames kept.

## Steps
1. Read `sample-data/radar-posts.json`. Keep posts where `is_lead` is true. Order them: hot before medium; then Queensland first (from `location_hint`); then posts whose `reason` says they're in the patch before ones whose `reason` says outside it; then newest first. Take the top 4, or how many Tommy asks for.
2. For each one, write two lines for Tommy: who it is and what they need (from `snippet`), and why it's a lead (from `reason`), with the community and date.
3. Draft a reply for each, following `sample-data/voice.md`:
   - Up to 120 words. Australian English, plain words, short sentences.
   - (a) One sentence that shows you read their post, using one real detail. (b) One or two genuinely useful things to check, picked from: who does the install (their own team or a subcontractor), what each warranty covers and who you ring about it, whether the system is sized on their real usage. (c) One honest line that it's TMEC Services, a Sunshine Coast business with its own install team, no subcontractors. (d) An open door to ask more.
   - If they ask for something the folder doesn't hold (which brand is best, what others paid, reviews of a named company), say plainly it depends on their home and their quote, and point them to what to check instead. Never invent it.
   - Write each reply fresh. Don't reuse the same sentences across replies: the same lines posted in several places reads as spam.
   - No price, no rebate dollar amount, no install date, no saving, no link, no hard sell. Never name or bash a competitor, even if the post names one.
   - If a post mentions smoke, a burning smell, a shock, a fire or a swollen battery, write no sales reply: flag it to Tommy at the top as a safety post.
4. Save each to `drafts/radar-<n>.md`: the first line `PREVIEW · sample data · nothing has been sent`, then the post's title, link, community and date, the two lines for Tommy, the reply, and a **Before posting** line: "Check the community's rules on businesses replying. Tommy posts it himself from TMEC's account." If the post is more than 10 days old, add: "Practice only: the live radar doesn't reply to posts older than 10 days."
5. In the chat, show the drafts and end with: "Want any of these changed? Say which number and how." If he edits one, save the new version over the old.

## Never
- Post, comment, message, or log in anywhere.
- Guess a suburb the post doesn't state.
