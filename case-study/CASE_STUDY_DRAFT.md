# Mayura Cafe and Food Court — A visit-first restaurant website

**Case-study status:** Working design prototype, in progress — not a launched client case study.
**Studio:** GyanArt. **Client/stakeholder:** Restaurant owner (a friend of the designer), involved in decisions.
**Location:** 7, 3rd Block, BDA Layout, 2nd Stage, Nagarbhavi, Bengaluru, Karnataka 560072.
**Research timeframe:** October 2026. **Website status:** V2.1 responsive prototype built; no production launch.

## The opportunity
Mayura Cafe and Food Court serves a broad collection of dishes, from South Indian tiffin to café snacks and drinks. Potential customers discovering it online need a quick route from curiosity to confidence: **recognise the restaurant, check when it is open, and get directions to the right location**. The business owner is actively involved in the project; a new website is being designed from the ground up. There is no claim that the restaurant lacked Google visibility, that its prior site was deficient, or that footfall has already improved.

## The challenge (working hypothesis)
How might we help someone considering a visit to Mayura quickly find verified visit information and start navigation, while still making a long, multi-category menu manageable on a phone? This is a **design hypothesis**, not a finding from conducted customer interviews.

## Stakeholder-sourced discovery inputs
| Decision | Verified information supplied during this project | Design consequence |
|---|---|---|
| D01 | Primary customer action is **find Mayura and visit in person** | Directions is more prominent than ordering or booking |
| D02 | Confirmed Maps destination: https://maps.app.goo.gl/mbjmqLDb7YmWp7bW9 | All Get Directions buttons share one destination |
| D03 | Near BDA Complex, Nagarbhavi | Landmark provides immediate location recognition |
| D04 | Full street/postal address supplied | Address is available in the Visit section and copy action |
| D05 | Open Monday–Sunday, 7:30 AM–9:30 PM | Regular hours appear in both hero and visit section |
| D06 | Restaurant menu photographs supplied as **research references only** | Dish categories and names become editable text, never embedded screenshots |
| D07 | Provisional menu prices accepted for now | Price data separated from design so owner can revise it |

**Evidence boundary:** Inputs above were supplied by the project sponsor/user; no customer interview or measured in-restaurant outcome has yet been reported.

## User journey (proposed; needs usability testing)
**Discover Mayura → Recognise food and storefront → Check hours and address → Tap Get Directions → Navigate to restaurant.**

We prioritised three concrete tasks: (1) finding the map link within seconds; (2) checking today’s usual opening hours; (3) exploring food categories without losing the primary navigation action.

## Information architecture and content strategy
Navigation uses **Home / Menu / About / Gallery / Visit Us / Contact**, with Visit and Contact currently leading to the verified visit section rather than implying a separate contact page. The menu groups include South Indian breakfast, drinks and milkshakes, quick bites, pizza and sandwiches, and tandoori starters. This hierarchy is a **design proposal** based on reference menu content, not a research-validated taxonomy. The longer paper-menu photographs were excluded from publication at the user's explicit request; the design instead renders accessible, editable text items and provisional prices.

## Design exploration and decisions
- **V1** tested a calm green/cream visual direction, an obvious directions action and text-first menu.
- **Reference mockup** explored a richer food-led identity; it was attractive but contained generated or unsupported details, including old hours and unverified benefits. The implemented site corrects those rather than copying them as facts.
- **V2.1** balances a cinematic dosa photo, six illustrated menu-highlight cards and image-backed category cards with a real storefront/visit block. The **Get Directions** CTA appears at multiple journey points and stays accessible in a mobile bottom bar.
- The exact restaurant address and opening hours are more important than a decorative, image-only menu.
- Artificial/generated food cards are explicitly labelled *illustrative*, not genuine Mayura dish photographs. The two original photographs supplied earlier are for design review until source rights are confirmed.
- The screenshot-derived price list is explicitly provisional; the website does not invent whether tax is included or additional.

## Prototype implementation
Static HTML, CSS and vanilla JavaScript. Responsive sections, collapsible mobile navigation, five clickable menu categories, copy-address affordance, directions links, keyboard focus styles, reduced-motion support and prototype `noindex` are included. Menu items are stored separately in `menu-data.js` for easy pricing edits. An optional `mayura:directions-intent` custom event exists, but **no actual analytics collection is enabled**.

## Validation and evidence to gather
1. Have the owner verify text, menu prices, tax policy, photo licensing and any catering/party-hall copy *before public launch*.
2. Ask 3–5 independent participants to find Mayura, opening hours and the maps destination on mobile; record task success, elapsed time and confusion from **actual sessions**, not imagined results.
3. Verify real-device navigation, keyboard/screen reader behaviour and performance; record results and changes.
4. Document owner review rounds with dates, requested changes and screenshots.
5. After publishing, track genuine direction link clicks if analytics is deployed; **clicks cannot establish walk-in visits**.

## Outcome so far
A working **desktop/mobile V2.1 prototype** and a transparent discovery/design decision trail. **Not yet achieved or claimed:** launched website, improved SEO rankings, extra visitors, conversion lift, footfall or revenue results.

## Portfolio publication rule
This can become a public **“Restaurant website design — In Progress”** case study after the owner signs off on wording and visual assets. Change the status to Delivered/Launched only after verifiable delivery and launch. Use self-created website screenshots and approved original restaurant assets; **never use the 12 copied Google Maps menu images** in the case study.