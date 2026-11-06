# Funboarding v2: design plan

**Subject:** LaunchGood onboarding for people and organizations raising donations, along with the compliance checks behind it.
**Audience:** the product, compliance and engineering reviewers who walk the prototype, and the fundraisers it simulates.
**Primary job:** let reviewers walk every path, from the risk score through verification to the action hub, and see the admin side next to it.

## Tokens

| Name | Light | Dark | Role |
|---|---|---|---|
| Sage mist | #EDF2EC | #0E1712 | Page |
| Paper | #FBFCF9 | #17251D | Surfaces |
| Cedar | #173A2B | #E3EDE6 | Ink, primary buttons |
| Launch green | #4AA567 | #5CC27A | Progress, approval, organization applicant |
| Saffron | #E8B23A | #E8B23A | Anything that changes with the vendor, plus the vendor toggle |
| Lapis | #23395F | #182640 | Admin view: a different room from the applicant's side |

**Type**
- **Reem Kufi**, a geometric Latin face with Kufic roots: page headings and the wordmark only.
- **Plus Jakarta Sans** (the client's choice): everything else.
- **Scale:** 15/24 body, 13 small, 16 h2, 30 h1.

## Layout

```
[ wordmark ]          applicant / vendor toggles   map  bell  admin  theme
+-----------+--------------------------------+------------------------+
| step rail | applicant screen, left aligned | admin drawer (lapis)   |
|  * done   | max 640px measure              | tabs: emoji            |
|  * here   |                                |                        |
|  o next   |                                |                        |
+-----------+--------------------------------+------------------------+
```

Everything is left aligned. The rail is a real sequence, so its markers carry order.

## Principles

1. **One memorable thing: the eight-point star.** It's the step marker on the rail, filled green when a step is done. On the start page, one large star draws itself once.
2. **Two rooms.** Applicant screens sit on sage and paper. The admin view is lapis, so a reviewer always knows which side they're on.
3. **Quiet everywhere else.**
   - Flat surfaces with no stacked shadows. The bell's notification is the one exception, because it floats.
   - Radius follows hierarchy: surfaces 18, controls 12, chips fully round.
4. **No template chrome.** No all-caps labels, no meta strings joined with middle dots, no arrows on buttons, no gradient washes.
5. **Words.**
   - Fundraisers, never "campaigns".
   - Donations, never "gifts".
   - Buttons say what happens.

## Review against the brief (what changed)

- **Dropped a tessellated geometric background on every page.** It was the generic "Islamic pattern" move and decoration, not information. The star now lives only where it means progress.
- **Dropped cream paper.** It's a common default, and it fights LaunchGood green. Sage keeps the palette inside the brand.
- **Dropped a horizontal progress bar and step strip.** Those come from the SaaS kit. A vertical rail reads as a path and leaves the measure for content.
