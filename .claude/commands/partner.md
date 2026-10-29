---
description: Pick a Sunshine Coast trade from the starter list, draft Tommy's first hello to them, and the email they'd send their own customers
---

# Contractor partners (preview)

Campaign partners are trades that don't do solar (builders, plumbers, pool shops, pest control and so on). One of them sends one email to its own customers recommending TMEC. Their customers already trust them, the list never leaves them, and TMEC pays a fee per sale. In the full system the Partners agent finds and screens them, writes to them, books the send and tracks every sale. Here you draft the first two emails.

## Steps
1. Read `sample-data/partner-prospects.csv` (a real starter list from OpenStreetMap, fetched 29 October 2026; electricians left out because that's TMEC's trade; none screened yet). If Tommy named a business or a trade, use that row. Otherwise list up to five rows that have a suburb (name, trade, suburb) and ask which one; if he says "you pick", pick one.
2. **Tommy's first hello to the trade.** The body is up to 110 words, not counting the contact block and the unsubscribe line. Subject up to 4 words, lower case, doesn't sell (start from `solar for your customers`). No dashes as punctuation, no exclamation marks, no emoji, no links, no fee figure, no results, no promises.
   - Greeting: "Hi there," (the list has no owner names).
   - Hook: "I came across <business> while looking at <their trade, in plain plural words: builders, glaziers, pool shops, pest controllers> around <suburb>." If the row has no suburb, say "on the Sunshine Coast". Say nothing more specific than the row holds.
   - Then: who Tommy is (TMEC Services, Sunshine Coast, solar, batteries and EV chargers with their own installers, not subcontractors). The offer, as an "if": if their customers ever ask about solar, TMEC would like to be who they send them to. They send one email to their customers recommending TMEC, TMEC writes it, TMEC pays a fee for every sale from it, and their customer list stays with them. A soft ask for a quick call. Sign off "Tommy".
   - End with `[TMEC contact block]` and the line "If you'd rather not hear from me, reply UNSUBSCRIBE and I will take you off straight away."
3. **The email the partner would send their own customers.** Written as the partner, recommending TMEC. It's theirs to change before it goes anywhere, so mark every line they must confirm is true with `[confirm]`: that customers have asked them about solar, that they don't do it themselves, and why they trust TMEC. Then: TMEC installs with its own team; three ways to get in touch (a form, ringing TMEC with a code, or replying "yes" so the partner passes on their details); "No pressure from me." Use square-bracket placeholders for what isn't known yet: `[customer first name]`, `[tagged link]`, `[TMEC phone]`, `[phone code]`, `[partner sign-off]`, `[partner footer and unsubscribe]`.
4. Save both to `drafts/partner-<business name in lower case, spaces and symbols as hyphens>.md`, first line `PREVIEW · sample data · nothing has been sent`, then the row it came from.
5. In the chat, show both and say what the full system does next: screens the trade, checks the Australian spam rules, gets Tommy's yes on the exact email, sends from a separate outreach address so his main inbox stays clean, and follows up three times at most. End with a numbered yes/no.

## Never
- Look anything up on the web, or invent a fact about the business.
- Put a fee amount in either email. The fee is Tommy's call; if he wants to set it, add it to `vault/big-list.md` as a decision for Session 1.
