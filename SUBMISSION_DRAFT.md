# ReWear Studio — Hackathon Submission Draft

**Status:** Devpost draft created, not finally submitted. Required API compliance remains outstanding.

## Eligibility and technical gates

1. The Devpost event header says **students only**, while its unfinished rules page permits adults and organizations. Samer has confirmed current student enrollment. Formal eligibility remains subject to organizer verification.
2. The live event description includes placeholders for the mandatory virtual try-on API name, sign-up URL, credits and technical docs. Obtain authentic API access and integrate it before submitting.
3. A public demo and repository now exist. Add accurate screenshots and a public 1–3 minute video of the actual working integration before final submission.
4. Confirm all images are used with consent; never use photos of minors or imply accurate size/fit prediction from generated imagery.

Organizer contact: hello@fabricvton.com (listed on the organizer's website).

## Proposed submission title

ReWear Studio — Style More. Own Less.

## Track

Styling & Wardrobe. The concept emphasizes privacy-conscious outfit planning and extending the usefulness of existing clothing.

## Elevator pitch

ReWear Studio helps people make more of what they already own. It combines a personal wardrobe, cost-per-wear analytics, occasion-based outfit planning and an illustrative outfit-comparison experience into a simple, welcoming interface. Its design prioritizes accessible interaction, consent and realistic sustainability claims.

## What has been built

- An original responsive web UI with a curated outfit comparison slider.
- Three pre-generated, synthetic adult-model sample images; **not** live outputs from the hackathon API.
- A browser-local wardrobe with custom garments, purchase prices, wears, and persistent data.
- A cost-per-wear analytics dashboard and most-worn list.
- A rule-based occasion planner for work, weekend, dinner and travel.
- A permission gate for browser-local photo preview, with no upload or generation.

## How it works

Users explore the sample outfits and compare them with a consistent synthetic model. They can build a wardrobe, log wears, see cost-per-wear statistics and explore suggestions for common occasions. The transparent local-only prototype avoids retaining personal photos remotely.

## Technology

Semantic HTML, responsive CSS, modern JavaScript, localStorage and original AI-assisted editorial imagery. The app is a static deployment and requires no sign-in.

## Key decisions

The experience is organized around repeat wear and personal utility, not pressure to buy. Photos are permission-gated and local. The product avoids invented environmental impact metrics and does not equate generated appearance with actual physical fit.

## Known limits / work before a valid entry

- Mandatory API integration **not implemented** (official API specification not published in the event description).
- No production try-on service, live size estimation or trained AI stylist.
- Public demo: https://rewear-ai-studio-samer-2026.usefulotter1.chatgpt.site
- Public source: https://github.com/samertall/rewear-studio
- No public YouTube/Vimeo demo video or authentic API-backed try-on demonstration yet.
- Devpost project is saved as a draft, not finally submitted.

## Suggested 2-minute demo storyboard after API integration

1. **0:00–0:20 — Problem:** online shopping feels uncertain; unused wardrobes add complexity.
2. **0:20–0:45 — Wardrobe:** add items, track wears, and understand cost-per-wear.
3. **0:45–1:20 — Real try-on:** consent flow, upload adult person image and garment, demonstrate a real API request and result, including latency.
4. **1:20–1:45 — Outfit planning:** show recommendations based on wardrobe and occasion.
5. **1:45–2:00 — Responsible design:** privacy, accessibility, limitations and impact hypothesis. Avoid unsupported impact claims.

## Suggested evaluation metrics (future measurements, not existing results)

- Time to create a look and reach a confident selection.
- Percentage of planned outfits using existing wardrobe items.
- Task completion rate and accessibility issues in testing.
- Actual provider generation latency and valid result rate.
- Number of consented photo sessions and successful deletion events.

## Future work

A compliant API service proxy, job status/retry flow, encrypted temporary image handling, deletion policy, body-diverse consented evaluation dataset, full keyboard/a11y testing and production analytics.
