# APUTRAC LinkedIn campaign: fuel efficiency and APU fuel savings

One post a week for eight weeks (planned start: to be set). Files in this folder:

- `README.md` (this file): the strategy
- `TRACKER.md`: status and results for each post
- `drafts/week-NN-*.md`: one draft per post

## Goal

Establish credibility in airline fuel efficiency, centered on high fuel costs and APU fuel savings. Drive people to the APUTRAC FE Score (https://app.aputrac.com/score) and to conversations.

## Core idea

The website's thesis: **"Every engine on the aircraft is managed in real time, except one."** Each post adds one piece of evidence for it.

## Audience

Airline fuel efficiency managers, OCC and ground operations leads, sustainability and finance teams, and executives who approve cost programs.

## Credibility asset

"40+ years of airline experience, from the chief pilot's office to a decade of IATA fuel-efficiency leadership" (www.aputrac.com). Tell it as a story in week 1, then let the posts prove it.

## Mix

About 70% education, 20% proof, 10% invitation. Mention APUTRAC lightly. A post should never read as an ad.

## The eight weeks

| Wk | Theme | Working hook | Core point |
|---|---|---|---|
| 1 | Who I am and the blind spot | "In 10 years working on airline fuel efficiency, the biggest gap I found was the one engine nobody watches." | Personal story plus the thesis |
| 2 | The cost of fuel | "Fuel is one of an airline's biggest costs. Here's the part almost nobody manages." | Frame fuel cost, narrow to APU waste ($700M+ a year, per the website) |
| 3 | How much does an APU burn? | "A running 777 APU burns about 100 gallons an hour. A 737 burns about 36." | Carousel of burn rates by aircraft type |
| 4 | Where the waste hides | "Airlines review APU data after landing. By then the fuel is gone." | Remote stands, overnight, maintenance, review lag, the ACARS/QAR blind spot |
| 5 | The ground power paradox | "Gate power and air are installed. Crews still run the APU." | GPU/PCA availability times actual use; poll |
| 6 | It's a people problem | "The fuel isn't saved by a system. It's saved by ownership, training and a team." | Policy, ownership, training, cross-department Fuel Team; tease the FE Score |
| 7 | FE Score launch | "Where does your APU operation stand? Five minutes to find out." | The dimensions; link to the tool; state it gives estimates |
| 8 | What it adds up to | "What a 20% APU reduction is worth for an 82-aircraft fleet." | Website example: $2.7M a year, about a 5-week payback; invite a conversation |

Option for week 8: share what FE Score submissions show in aggregate. Only with submitters' consent, and the privacy policy would need to say so first.

## Facts to verify before posting

- "$700M+ wasted per year" (website): need the source and year.
- "IATA identified APU management as the #1 opportunity" (website): need the publication and date.
- Fuel's share of airline operating costs: use the latest IATA figure. Do not quote an unsourced percentage.
- "Measured, not estimated" is accurate for APUTRAC. The FE Score is an estimate. Say so plainly in week 7.
- Burn rates (week 3) come from `aputrac-api/apu_reference.json` (loaded ground operation, both air-conditioning packs on). Say "about" and name the conditions.
- The 82-aircraft impact example is the website's own illustration ($0.41/lb fuel, 20% APU fuel reduction). Label it as an example.

## Habits

- One idea per post. The hook goes in the first two lines.
- Post from the personal profile; repost from the company page.
- Same day and time each week. Reply to comments in the first hour.
- Vary format: text, carousel, poll (week 5), the 90-second video (week 4 or 8).
- Links in the first comment rather than the post body (a common rule of thumb).
- Comment on other people's posts three or four times a week.

## Measurement

Saves and comments from the right job titles, profile views, and FE Score submissions per week (see the FE Score leads page in the app). Idea not yet built: tag each post's link (for example `/score?src=li-w7`) so each lead shows its source.

## Decisions (2026-10-26)

- **Goal:** leads and visibility equally. Education-first posts; the FE Score is pushed in weeks 6 to 8.
- **Posting day:** Tuesdays. Week 1 = 3 Nov 2026, then 10, 17 and 24 Nov, 1, 8 and 15 Dec, and week 8 = 22 Dec (holiday week: reach usually drops, so consider posting week 8 on 29 Dec or moving it earlier).
- **Week 1 story:** general version for now, with a marked `[STORY]` slot for one specific moment from the IATA years.
- **Sources:** to be confirmed by Pat; see below. Drafts carry `[SOURCE]` markers until then.

## Source research (done 2026-10-26, web search, US-only; verify before posting)

| Claim | What was found | Use in posts |
|---|---|---|
| Fuel share of airline costs | IATA June 2025 outlook: 2025 fuel bill $236 billion, 25.8% of operating costs (2024: $261 billion). https://www.iata.org/en/pressroom/2025-releases/2025-06-02-01/ | Good. Check iata.org for a newer outlook (Dec 2025 or June 2026) and use the latest. |
| APU share of an airline's fuel | Roughly 2 to 2.5% (one academic paper, citing IATA, not confirmed against IATA); about 1% for British Airways per the IPCC aviation report. https://archive.ipcc.ch/ipccreports/sres/aviation/127.htm | Say "about 1 to 2.5%" and cite. Do not attribute the 2 to 2.5% to IATA unless confirmed. |
| "IATA identified APU management as the #1 opportunity" | No published IATA document found that says this. | Reframe as first-hand: "the IATA fuel efficiency team I led worked with 100+ airlines and found..." Pat to confirm the wording and whether IATA needs to approve use of its name. |
| "$700M+ wasted per year" (website) | No credible published figure found. | Pat to say where it came from. If it is APUTRAC's own model, call it "our estimate" and be ready to explain the method. |
| What an APU burns | One airline source cited in a blog: 150 to 400+ kg/h; ground power under 20 kg/h. Our reference file gives 100 to 350 kg/h by type. | Use our reference file (week 3) and say "about". |

Avoid: vendor-claimed figures (FlightWatching, Cavotec, Honeywell) unless clearly labelled as vendor claims.

## Open questions

1. Where does the "$700M+" figure come from (derivation or document)?
2. Confirm the first-hand IATA framing above, and whether IATA's name can be used.
3. One specific IATA-years moment for the week 1 `[STORY]` slot (optional).
4. Any weeks to reorder, swap or drop.
