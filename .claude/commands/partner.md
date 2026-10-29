---
description: Pick a Sunshine Coast trade from the starter list, draft Tommy's first hello to them, and the email they'd send their own customers
---

# Contractor partners (preview)

Campaign partners are trades that don't do solar (builders, plumbers, pool shops, pest control and so on). One of them sends one email to its own customers recommending TMEC. Their customers already trust them, the list never leaves them, and TMEC pays a fee per sale. In the full system the Partners agent finds them, writes to them, books the send and tracks every sale. Here you draft the first two emails.

## Steps
1. Read `sample-data/partner-prospects.csv` (a real starter list from OpenStreetMap, fetched 29 October 2026; electricians left out because that's TMEC's trade). If Tommy named a business or a trade, use that row. Otherwise list five rows (name, trade, suburb) and ask which one; if he says "you pick", pick one with a suburb filled in.
2. **Tommy's first hello to the trade.** Up to 110 words. Subject up to 4 words, lower case, doesn't sell (start from `solar for your customers`). Rules: Australian English, no dashes as punctuation, no exclamation marks, no emoji, no links, no fee figure, no results, no promises.
   - Greeting: "Hi there," (the list has no owner names).
   - Hook: "I came across <business> while looking at <trade, plural> around <suburb>." Only say something more specific if it's in the row.
   - Then: who Tommy is (TMEC Services, Sunshine Coast, solar, batteries and EV chargers with their own installers, not subcontractors); that their customers who ask about solar end up going elsewhere; the offer (they send one email to their customers, TMEC writes it, TMEC pays a fee for every sale from it, their list stays with them); and a soft ask for a quick call.
   - End with `[TMEC contact block]` and the line "If you'd rather not hear from me, reply UNSUBSCRIBE and I will take you off straight away."
3. **The email the partner would send their own customers.** Written as the partner, recommending TMEC: a few customers have asked about solar, they don't do it, so they found someone they'd be comfortable sending people to; TMEC installs with its own team; three ways to get in touch (a form, ringing TMEC with a code, or replying "yes"); "No pressure from me." Use placeholders in square brackets for what isn't known yet: `[customer first name]`, `[tagged link]`, `[TMEC phone]`, `[phone code]`, `[partner sign-off]`.
4. Save both to `drafts/partner-<business name>.md`, first line `PREVIEW · sample data · nothing has been sent`, then the row it came from.
5. In the chat, show both and say what the full system does next: checks the Australian spam rules and Tommy's yes before anything goes out, sends from a separate outreach address so his main inbox stays clean, and follows up three times at most.

## Never
- Look anything up on the web, or invent a fact about the business.
- Put a fee amount in either email. That's Tommy's call, and it's on the list for Tuesday.
