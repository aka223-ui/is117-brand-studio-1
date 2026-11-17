# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 kept, merged and published.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Complete. Learner approved merge; PR #2 verified merged into main.
- Next step: Submit repository URL through Canvas Website URL option.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                        | Secondary audience                                                             |
| ------------------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| Person in a concrete situation        | Anime fan wearing a graphic tee casually, at meetups/events, or at home | Gift buyer choosing for an Evangelion fan (AI suggestion accepted)             |
| Goal or meaning they seek             | Boldly show interest in a favorite show                                 | Choose a gift connected to the recipient's fandom (provisional assumption)     |
| Concern before choosing               | Artwork expresses the intended fandom (provisional assumption)          | May not understand the show or artwork (provisional assumption)                |
| What the page should help them decide | Whether the visible art expresses their interest                        | Whether this concept matches the recipient's interest (provisional assumption) |
| Evidence or assumption                | Assumption; not validated                                               | Assumption; not validated                                                      |

## Early brand brief

| Decision                                 | Agreement                                                                                   |
| ---------------------------------------- | ------------------------------------------------------------------------------------------- |
| Brand name                               | Ita-Tees — learner connects anime apparel with itasha car decoration                        |
| One-sentence promise                     | Wear your fandom out loud. (AI suggestion accepted)                                         |
| Primary archetype: the brand's character | Creator (AI suggestion accepted)                                                            |
| Three voice traits                       | Bold, playful, welcoming (AI suggestion accepted)                                           |
| One example line in this voice           | Wear your fandom out loud.                                                                  |
| Learner's predicted audience effect      | Empower fans and connect to their love of the show; learner enjoys merchandise with artwork |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                |
| ------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Wear your fandom out loud. / White tee with bold mecha artwork for everyday wear, meetups and home / Explore the tee. Identical in both previews.                                                                    |
| Modernist preview, reference, and annotations     | [Modernist preview](public/explorations/modern.html); Müller-Brockmann, Musica Viva (1958), [MoMA](https://www.moma.org/collection/works/7233/). Reference image visually inspected.                                 |
| Postmodernist preview, reference, and annotations | [Postmodernist preview](public/explorations/postmodern.html); Bedin, Super lamp prototype (1981), [V&A](https://www.vam.ac.uk/articles/what-is-postmodernism). Reference image visually inspected.                   |
| Chosen direction and reason                       | B / postmodernist. Learner cites lime button, tilted image, artificial frame shadow and special font as appealing and welcoming. Requested angular English lettering and chose sharply mechanical over hand-painted. |
| Original SVG logo                                 | [Mechanical wordmark proposal](public/assets/ita-wordmark.svg); approved by learner: “Looks perfect”.                                                                                                                |
| Monochrome and small-size variants                | [Review board](public/explorations/logo.html), same one-ink SVG at 175px and 110px.                                                                                                                                  |
| Logo review at actual use size                    | Learner approved board with 175px navigation and 110px small-size samples; AI inspected logo in final desktop/phone renders.                                                                                         |
| Shared palette, typography, spacing, and assets   | Shared styles.css, ita-wordmark.svg and mecha-shirt.svg. Lavender paper, purple frame, lime action, heavy oblique display and readable system body type.                                                             |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle   | Actual copy or interaction                                                          | Visitor benefit / factual support                                                                                       |
| ----------- | ----------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Reciprocity | Free gift checklist, no signup                                                      | Learner explains parents/friends unfamiliar with the show can organize shopping and find something the recipient loves. |
| Unity       | Brand story connects itasha car graphics and graphic tees as visible fan expression | AI proposal accepted by learner. Shared interest without fabricated community claims.                                   |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                                       | Issue / PR                                                                               | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BRAND-001 | [Storefront](public/index.html), [live guide](public/styleguide.html), [paired previews](public/explorations/compare.html), [shared graphic](public/assets/mecha-shirt.svg) | [Issue #1](https://github.com/aka223-ui/is117-brand-studio-1/issues/1); branch brand-001 | Final npm run check passed: formatting, HTML/CSS/JS lint, 7 server tests and 10 Chromium browser tests including axe. Image reload test updated to the branded asset path, preserving its assertion. AI inspected storefront, guide, studio and both previews at 1280px/375px: no broken images or horizontal overflow. Learner observed baseline size L added, bag count 1; Learner identified missing-size warning (AI clarified unchanged bag), described fun manga/comic impression, confirmed keyboard focus and adding without mouse, and reported a proportional narrow layout with continuous downward scrolling. Requested blueprint revision, approved it, and requested pushing for submission. After revision, lint and 10 browser tests passed again. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.

## Concept boundary

Unofficial Evangelion-inspired student concept; original geometric mecha artwork, no endorsement or affiliation. White shirt remains the same across previews; not for sale. Photographer concept was set aside at the learner's request. Audience concerns marked provisional remain assumptions to revisit. Visual direction B, mechanical logo, reciprocity gift checklist and unity brand story are agreed; learner browser checks and artwork approval recorded; approved PR merged and deployment verified.

## Artwork revision

Learner requested a simplified Unit-01 blueprint with Evangelion-related background words because the original helmet did not read clearly as Evangelion. Revised shared SVG uses full-body front elevation, horn, shoulder pylons, long armored limbs, technical grid, and EVANGELION / UNIT-01 / NERV / TOKYO-3 / A.T. FIELD / SYNCHRO lettering. Same artwork in both previews and storefront. Learner approved revised artwork and requested pushing for submission.

## Final delivery

- Learner reviewed LEARNING.md and approved publication: “All good, proceed”.
- [BRAND-001 pull request #2](https://github.com/aka223-ui/is117-brand-studio-1/pull/2) merged after learner approval; verified merge commit `4b0620b9bbb078c7e9a3cc8e50363c54e591b961`.
- [GitHub Pages storefront](https://aka223-ui.github.io/is117-brand-studio-1/) and [live guide](https://aka223-ui.github.io/is117-brand-studio-1/styleguide.html) verified accessible.
- [Deployment run](https://github.com/aka223-ui/is117-brand-studio-1/actions/runs/41760253499): checks and publishing succeeded.
- Canvas submission is the learner's next step; not yet confirmed submitted.

## Research checkpoint — November 10, 2026

[Published Research record](https://aka223-ui.github.io/is117-brand-studio-1/research.html) is included in [PR #4](https://github.com/aka223-ui/is117-brand-studio-1/pull/4); the learner approved merging and publication on November 10. It compares Hot Topic, UNIQLO and Ripple Junction original product pages, two positioning options, and the existing two audience hypotheses. It preserves the current brand and distinguishes source observations, interpretations, assumptions and planned human checks. This research follows the original November 3 prototype and precedes this revision; it is not backdated.

[Issue #3](https://github.com/aka223-ui/is117-brand-studio-1/issues/3) informs the short artwork explanation prepared in `public/index.html`. Decision: implement the explanation; retain the expressive artwork. Current checks: formatting/lint, 7 server tests and 12 Chromium browser tests passed on November 10; research page included in link/anchor, image, automated accessibility and 375px overflow checks. AI inspected desktop/phone previews. Reviewer comprehension check and retry remain pending; issue stays open. Outgoing peer-review issue links and in-class audience explanation are not evidenced in this chat.

AI researched and drafted the new content; no new learner explanations or human results have been inferred. Existing approved learning excerpts are unchanged.

## 2. Plan — PLAN-001 / November 17, 2026

### Goal and compact brand brief

Help anime fans understand the Unit-01 graphic and try a clearly labeled demo order; gift buyers provide a contrasting comprehension check. Both audience cards remain hypotheses. Preserve Ita-Tees' promise, “Wear your fandom out loud,” Creator character and bold, playful, welcoming voice.

Reuse the mechanical wordmark, lavender paper, purple framing, lime actions, angular oblique headings, hard shadows and readable body text from the [live style guide](https://aka223-ui.github.io/is117-brand-studio-1/styleguide.html). Existing [modernist/postmodernist previews](https://aka223-ui.github.io/is117-brand-studio-1/explorations/compare.html) remain historical visual explorations, not working checkout versions. Visual references and translated choices are recorded above in SPEC: Müller-Brockmann’s Musica Viva (MoMA) for alignment/hierarchy and Bedin’s Super lamp (V&A) for playful unexpected framing. The approved expressive identity is retained in both new flows.

Keep two honest persuasion elements: reciprocity through a free gift checklist without signup; unity through the itasha/fandom-expression story. They offer practical help and shared-interest context, not proven conversion gains. No fabricated reviews, scarcity, licensing or customer counts. Retain unofficial student concept, not for sale and fictional demo-price labels.

### Compare two concise approaches

A — Artwork first: promise → large blueprint graphic → short Unit-01 explanation → gift checklist → size/quantity → itemized review → simulated checkout → saved receipt/history. Benefit hypothesis: fans inspect the art quickly. Risk: unfamiliar buyers encounter unexplained references first.

B — Explanation first: promise → short Unit-01 explanation and gift checklist → same graphic → same size/quantity, review, simulated checkout and receipt/history. Benefit hypothesis: unfamiliar buyers understand the reference before acting. Risk: returning fans may need to scroll further to shop.

Selected for the next build: B, explanation first. The learner selected it to help unfamiliar buyers. A remains the comparison. Keep the same shirt/art, headline/supporting wording, $28 fictional unit price, available sizes, main action and backend. Only information order changes; this is a flow comparison, not a new visual-style contest. Main checkout action: “Place demo order — no payment.” Neither flow is implemented as a working checkout yet.

### Shared stories, essential features and observable checks

S1 / Understand the concept. As a fan or unfamiliar gift buyer, I want a plain explanation so I can judge whether the artwork suits the recipient. F1: identify Unit-01 from Neon Genesis Evangelion, link the free checklist and show concept limits. Check: a classmate explains the reference, intended audience and “not a real shop” without coaching; record their actual response and revise if unclear. Planned, not run.

S2 / Choose and review. As a demo shopper, I want size, quantity and an itemized total so I know what my selection includes. F2: sizes S/M/L/XL, integer quantity 1–5, and $28 fictional unit price; demo shipping/tax explicitly $0, no fulfillment. Check: M × 2 shows M, quantity 2 and $56 total; changing to 1 shows $28; opening the checklist preserves choices. Missing/unsupported size and quantity 0, 6 or 1.5 are rejected. Do not invent garment measurements or a fit guarantee. Planned, not run.

S3 / Complete safely. As a demo shopper, I want validation and a clear receipt so I know whether the simulated checkout succeeded. F3: synthetic email, review screen, save indicator, error feedback and demo reference. Check: missing size/invalid email prevents an order; a valid M × 2 submission creates one receipt only after a successful database save. A forced save failure shows an error, keeps input, and creates no success receipt. Disable repeated submission while saving. Planned, not run.

S4 / Save and reopen. As a reviewer, I want saved demo orders to survive restart so I can verify SQLite persistence. F4: Node 24 local server and SQLite database outside public files; order history contains reference, items and total, not email. Check: order M × 2 using demo@example.test, copy its reference, stop/restart with the same database path, reopen history and find that reference with $56. Clear browser storage and verify the server record remains. Planned, not run; browser storage alone does not pass.

S5 / Use either flow. As a keyboard or phone user, I want reachable controls and readable errors so I can complete the same demo task in A and B. F5: semantic labels, visible focus, associated validation messages and responsive summary. Check: complete the task using only keyboard; at 375px width inspect controls and page overflow; repeat both flows. Automated accessibility checks supplement human observation, not a full accessibility claim. Planned, not run.

### SQLite implementation and data plan

Reuse the supported Campus Cotton starter selectively or adapt its validation/storage pattern into this app; preserve the current working copy and document changed files. [Supported setup and save/reopen instructions](https://kaw393939.github.io/is117-demo-days/examples/submissions/run-examples.html). Starter reuse has not happened yet.

Proposed local API: GET /api/products for trusted catalog prices; POST /api/orders validates product/size/quantity and synthetic email, recalculates totals from SQLite prices and commits the order in a transaction; GET /api/orders retrieves synthetic demo history. Products hold ID, name and price in integer cents. Orders hold ID/reference, timestamp and total cents; order_items hold order/product IDs, size, quantity and the saved unit price. Use parameterized queries and foreign keys. Validate but do not persist/send email. Reject unsupported values and ignore client-submitted prices/totals. Keep SQLite files out of Git/public assets.

Checks for backend build: submitting a forged total must still save 5600 cents for two $28 shirts; malformed inputs must not increase order count; restart must retain the same reference and historical price. These checks are specified, not passed. GitHub Pages cannot run this Node/SQLite server. The public preview must state its static/demo limits; SQLite evidence comes from the local server until a suitable backend is actually deployed. Do not expose the teaching server as a real shop.

### Scope, sequence and deferred work

Essential: F1–F5. Build a small slice first: run/save/reopen the starter; adapt catalog/validation; connect shared checkout; build A/B orders of content; verify both and record results. Preserve existing logo, shared CSS and research. Defer real payments, accounts, shipping, inventory, discounts, analytics, actual fit guide and customer data. No extra business or separate report is needed.

### In-class review and same-plan revision

Scheduled for November 17; not yet happened at preparation time. Reviewer/date, story explained, observable check explained, useful question, resulting change and retry: pending. Attendance/participation are not verified by this record. Ask the classmate to explain S4: why a receipt after refresh alone is insufficient, and how stopping/restarting with the same database verifies persistence. Record their own answer, not this prompt as their response. Add the actual question and improve this same Plan section afterward.

### Issue, checks and assistance

[PLAN-001 issue #5](https://github.com/aka223-ui/is117-brand-studio-1/issues/5) tracks the plan; [peer issue #3](https://github.com/aka223-ui/is117-brand-studio-1/issues/3) motivates the artwork explanation and remains open for reader retry. This revision changes documentation only. The current prototype still has a temporary bag, no checkout and no SQLite; earlier brand checks do not prove the planned features work. AI inspected the existing record and course sources, drafted the plan and prepared technical checks; the learner selected explanation-first for unfamiliar buyers. New implementation, in-class results and learning outcomes are not inferred. Keep using this SPEC and published research record.

November 17 documentation verification: Prettier, HTML/CSS/JavaScript lint, all 7 existing server tests, internal-anchor checks and git diff --check passed. The 12 browser tests could not launch because the required Chromium binary was unavailable; the supported setup command failed downloading a valid archive. No new browser, human, checkout or SQLite pass is claimed. CI will run the repository checks on the pull request.
