---
description: Read the real radar sample, pick the best Queensland buyers, and draft a helpful reply to each in TMEC's voice
---

# Radar (preview)

The full Lead Radar runs every day on its own server, finds people asking about solar, batteries and EV chargers, and drafts a reply for Tommy's yes. Here you do the same on a real sample: public Australian Reddit posts read by hand on 28 October 2026, no usernames kept.

## Steps
1. Read `sample-data/radar-posts.json`. Keep posts where `is_lead` is true. Sort hot first, then medium; within each, Queensland first (from `location_hint`). Take the top 4, or how many Tommy asks for.
2. For each one, write two lines for Tommy: who it is and what they need (from `snippet`), and why it's a lead (from `reason`), with the community and date.
3. Draft a reply for each, following `sample-data/voice.md`:
   - Up to 120 words. Australian English, plain words, short sentences.
   - (a) One sentence that shows you read their post, using one real detail. (b) One or two things that are genuinely useful, such as what to ask any installer about a quote: who does the install, what each warranty covers, whether the battery is sized on their real usage. (c) One honest line that it's TMEC Services, a Sunshine Coast business with its own install team, no subcontractors. (d) An open door: "happy to answer anything here".
   - No price, no rebate dollar amount, no install date, no saving, no link, no hard sell. Never bash a competitor, even if the post names one.
   - If a post mentions smoke, a burning smell, a shock, a fire or a swollen battery, write no sales reply: flag it to Tommy as a safety post.
4. Save each to `drafts/radar-<n>.md`: the first line `PREVIEW · sample data · nothing has been sent`, then the post's title, link, community and date, the two lines for Tommy, the reply, and one line: "Practice draft: these posts are older than 10 days, so the live radar would not reply to them. It only replies to fresh posts, and only after your yes."
5. In the chat, show the drafts and end with: "Want any of these changed? Say which number and how." If he edits one, save the new version over the old.

## Never
- Post, comment, message or open a link to log in anywhere.
- Guess a suburb the post doesn't state.
