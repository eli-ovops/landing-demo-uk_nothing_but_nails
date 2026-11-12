# Local visual QA — v2

**Scope:** local static Concept Demo only. This is not deployment, upload, outreach, booking, source-transfer or customer-authorisation evidence.

## Browser evidence — 2026-09-01

| Viewport | Screenshot | Raster check | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `desktop-1440x900.png` | 1440×900 | `903be968893768f1e915d1a81acfd40e8ea0303c380d3b62c2bcec2967becc2c` |
| Mobile 390×844 | `mobile-390x844.png` | 390×844 | `b7d25bcb0771b3ffff9083b9b1d5db18429c5ded6887d48ba1f292b1a541d212` |
| Mobile service follow-up | `mobile-services-390x844.png` | 375×812 browser capture | `2c7580da9fee2c88dfe69a0d9c2355110f4e1b097d72c3332a55008dbeff25f2` |
| Full desktop page | `desktop-full-css1440.png` | 1440×4263 | `70f4e4cda8e3c8cfc18648dda60be93158698fe4b2a32fa81d35cc076cf7618e` |
| Full mobile page | `mobile-full-css390.png` | 390×5089 | `3d1f42fc57f17de1fec7ef315d84bf1d840ea5e89169efca4f02b4e7576aa588` |

The page was tested in a local browser preview. At the exact CSS viewports, `documentElement.scrollWidth` did not exceed `clientWidth`; four image elements and four Fresha outbound links were present; the browser console returned no errors.

## Acceptance checks

- Hero is an unmistakable manicured hand, not an abstract substitute.
- Four distinct supplied concept images serve Hero, services, hands/feet and closing; no single image is repeated as filler.
- The visible business facts are restricted to Nothing But Nails, Arundel, the verified address, four verified services and the existing Fresha route.
- No prices, hours, reviews, staff names, portfolio claims, form, payment, booking clone, internal governance text, AI claim or asset-rights assertion appears in the page.
- Mobile service list was changed from two columns to a single readable list; the full 390px capture records all four labels before the hands/feet, visit and closing sections.
- The long captures were taken only after scrolling the local page through every visual section, so its lazy-loaded pedicure and closing images are present in the saved evidence.

`LOCAL BROWSER QA = PASS — AWAITING INDEPENDENT VISUAL ACCEPTANCE`.

## Hero V3 revalidation — 2026-09-01

The Hero was directionally redesigned after user feedback. The change is confined to the Hero markup and its matching desktop/mobile CSS; all prior evidence for protected downstream sections remains unchanged.

| Viewport | Screenshot | Raster check | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `hero-v3-desktop-1440x900.png` | 1440×900 | `6e83df1b1983ba1a7da7da3618931fe39a14083fa80a01871aa518262c03466b` |
| Mobile 390×844 | `hero-v3-mobile-390x844.png` | 390×844 | `2ab7f390782fc550923d7357d7058d0af147fd5d9f2ce4b1c0030db62ab7bc8b` |

- Desktop: the blue gel manicure is the dominant visual, with the business name and Fresha CTA legible in the first viewport.
- Mobile: the actual manicure image appears first; the two-line title and Fresha CTA are visible within the 390×844 capture.
- At the mobile viewport, `documentElement.scrollWidth = clientWidth = 375`; no horizontal overflow was detected.
- The image remains a supplied concept asset and is not presented as a customer project, staff member or verified portfolio work.

`HERO V3 LOCAL BROWSER QA = PASS`.

`HERO V3 INDEPENDENT VISUAL ACCEPTANCE = PASS` — the 1440×900 and 390×844 captures confirm a manicure-led Hero, legible brand/CTA, no horizontal overflow, static CSS-only treatment, unchanged Hero image hash and no customer-project misrepresentation. This is local visual evidence only; it does not authorize deployment, outreach or source transfer.

## Customer-authorised work-image update — 2026-09-01

The user confirmed customer authorisation for the four direct Fresha merchant-profile work images. All client-visible concept images were replaced with four different frozen local customer-work assets; source URLs, placement and hashes are in `docs/IMAGE_LEDGER.md` and `docs/CUSTOMER_ASSET_AUTHORIZATION.md`.

| CSS viewport | Full-page evidence | Raster output | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `customer-work-full-desktop-1440.png` | 1425×4038 (scrollbar excluded by browser capture) | `8a2b29529a21208f04ff115013f5d5edc9c1bd37093d2c570707c19ddfa7e4b0` |
| Mobile 390×844 | `customer-work-full-mobile-390.png` | 375×4862 (scrollbar excluded by browser capture) | `98c370e3cad40de0242cdd36f6459922d5c8a07d3bcf5adccc10313ec5e1e2a7` |

- At both CSS viewports, all four local customer-work images loaded with `naturalWidth = 1280`.
- Mobile `documentElement.scrollWidth = clientWidth = 375`; no horizontal overflow was detected.
- Mobile photo containers were adjusted to fill their intended service, ritual and closing placements after the landscape work images replaced portrait concept images.

`CUSTOMER-WORK LOCAL BROWSER QA = PASS`.

`CUSTOMER-WORK INDEPENDENT VISUAL ACCEPTANCE = PASS` — the independent reviewer confirmed all four distinct authorised work images, readable desktop/mobile crops, no blank placeholders or mobile overflow, unchanged factual boundaries, and exact source/hash records. This remains local Concept Demo evidence only; it does not authorise deployment, outreach, source transfer or further asset reuse.

## Content-complete update — 2026-09-01

The client-visible page was expanded with the currently verified business content: rating/aggregate review count/verification, four priced core services and timings, wider service menu, full postcode, current hours, Fresha handling, social links, contact links and voucher route. The fact/source and dynamic-content boundary are recorded in `docs/CONTENT_SNAPSHOT_20260901.md`.

| CSS viewport | Full-page evidence | Raster output | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `content-complete-desktop-1440.png` | 1425×4243 (scrollbar excluded by browser capture) | `bbd83f232ad02c8b4768b8812d746d96d114fac65e25d1c57771be977bb7334f` |
| Mobile 390×844 | `content-complete-mobile-390.png` | 375×5175 (scrollbar excluded by browser capture) | `5ca0e7e1a35d6b4744325ceb87af658940e90312f23d8654793dc3092c3a9748` |

- Desktop and mobile: all four customer-work images loaded; no broken image was reported.
- Mobile: `documentElement.scrollWidth = clientWidth = 375`; no horizontal overflow was reported.
- Client-visible links include the Fresha booking route, the Fresha voucher route, two social profiles, a mail link and a telephone link. No booking, form, payment or data collection is implemented locally.
- Historical `Acceptance checks` above accurately describe the earlier limited-content page; this section supersedes the “No prices, hours, reviews…” bullet for the current content-complete version.

`CONTENT-COMPLETE LOCAL BROWSER QA = PASS — AWAITING INDEPENDENT VISUAL ACCEPTANCE`.

`CONTENT-COMPLETE INDEPENDENT VISUAL ACCEPTANCE = PASS` — the independent reviewer confirmed that the added score, pricing/timing, address/hours, contact/social and voucher information is readable on the desktop and mobile full-page evidence; no blank sections, image failure, overflow, truncation, crowding or client-visible internal text was found. The conflicting owner identity and older opening hours remain excluded. This is local Concept Demo evidence only; it does not authorise deployment, outreach, third-party account actions or source transfer.

## Typography and emphasis refinement — 2026-09-01

The serif display and decorative purple treatment were replaced by a single DM Sans family, neutral navy/mist surfaces and a coral action colour. Source-level intent and boundaries are recorded in `docs/VISUAL_REFINEMENT_20260901.md`.

| CSS viewport | Full-page evidence | Raster output | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `focused-color-desktop-1440.png` | 1425×4123 (scrollbar excluded by browser capture) | `64b5f84277e3834b2a70e2914966d9827691c7d830e245e711214bd5b2223578` |
| Mobile 390×844 | `focused-color-mobile-390.png` | 375×4926 (scrollbar excluded by browser capture) | `443d595dc16132cb86bf9eab1513aaa8ac77258857f4eabfbd3444dcb4087b49` |

- Desktop and mobile: all customer-work images loaded with no broken images.
- Mobile: `documentElement.scrollWidth = clientWidth = 375`; no horizontal overflow was reported.
- The browser confirmed the DM Sans heading family and coral primary booking CTA. Source inspection found no remaining prior Bodoni/Manrope font declarations or violet/blue design tokens.

`TYPE-AND-EMPHASIS LOCAL BROWSER QA = PASS — AWAITING INDEPENDENT VISUAL ACCEPTANCE`.

`TYPE-AND-EMPHASIS INDEPENDENT VISUAL ACCEPTANCE = PASS` — the reviewer verified that real nail-work photography remains the primary visual; desktop and 390px layouts are intact; neutral typography/decorations no longer compete for attention; and coral now only communicates booking CTAs, service prices, the current weekday hours and actionable links. The service-card hover bar was separately inspected and is neutral `#a9b2ba`.

## Pastel palette refinement — 2026-09-01

The deep navy surfaces were replaced with a restrained pale-blue to blush-pink gradient family. Orange-coral remains the action colour; service-price text was darkened to preserve small-text contrast on the pale page surface.

| CSS viewport | Full-page evidence | Raster output | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `pastel-desktop-1440.png` | 1425×4123 (scrollbar excluded by browser capture) | `29799b832399afbde185a20f91861db7777d62b58e4fbde25b3e11f9483a34cd` |
| Mobile 390×844 | `pastel-mobile-price-legible-390.png` | 375×4926 (scrollbar excluded by browser capture) | `f33e528248ac8e40441c7c0d00a81a0998e4b031e448a1f48a805e6afee12da0` |

- Both viewports loaded all customer-work images, and the mobile viewport reported `scrollWidth = clientWidth = 375`.
- The inspected service-price colour is `#bc4e3e`; against the `#f7fbff` page surface it measured 4.70:1 contrast.

`PASTEL-PALETTE LOCAL BROWSER QA = PASS`.

`PASTEL-PALETTE INDEPENDENT VISUAL ACCEPTANCE = PASS` — the independent reviewer confirmed that the blue-to-blush gradient removes the industrial feel without overpowering the real nail-work images, CTA hierarchy remains clear, the mobile page has no overflow/truncation, and the small price contrast issue is closed.

## Continuous colour-flow refinement — 2026-09-01

The page background is now one stronger blue-to-pink-to-orange vertical colour flow. Section surfaces are translucent rather than separate pale gradients, and the shared action colour is deep berry. Service-price text remains the separately contrast-checked coral-red.

| CSS viewport | Full-page evidence | Raster output | SHA-256 |
| --- | --- | --- | --- |
| Desktop 1440×900 | `flow-strong-desktop-1440.png` | 1425×4123 (scrollbar excluded by browser capture) | `58c87457b2c0d816941636b6da83cd73eaa0c30b5483bbff2d9799655ea4d36c` |
| Mobile 390×844 | `flow-strong-mobile-390.png` | 375×4926 (scrollbar excluded by browser capture) | `0e16ba942c802c40d916853dfdeb6620c615d405f42d66dbd4ec3c19624efebc` |

- All customer-work images loaded; mobile `scrollWidth = clientWidth = 375`.
- The dark-berry CTA has measured 6.75:1 text contrast. The previously checked small price text remains `#bc4e3e` at 4.70:1 against its light local surface.

`COLOUR-FLOW LOCAL BROWSER QA = PASS`.

`COLOUR-FLOW INDEPENDENT VISUAL ACCEPTANCE = PASS` — the independent reviewer confirmed the continuous blue-to-pink-to-orange flow is more saturated yet natural, CTAs remain clear across all background colours, the real nail-work images retain visual priority, and the 390px layout is complete with no overflow or clipping.

## Finesse whole-page rhythm redesign — 2026-09-01

The v4 redesign applies a fresh `finesse-ui redesign` audit to the whole local Concept Demo. It removes the isolated NB poster and the incompatible tall photo crops. Each customer-authorised work image now appears at its natural horizontal proportion, in a clear appointment journey: identity → work → services → treatment range → location → booking.

| CSS viewport | Full-page evidence | SHA-256 |
| --- | --- | --- |
| Desktop 1440×900 | `finesse-v4-desktop-final.png` | `e5455b11478ea7c6b35b07a0b539341eac0fcdd26717eb375af8fdaf630e1de4` |
| Mobile 390×844 | `finesse-v4-mobile-final.png` | `49bdcc0908f789e7390936cb7c6d4ff95455ad2771a3d0437e3e1d460148090b` |

- Desktop: `scrollWidth = clientWidth = 1440`; mobile: `scrollWidth = clientWidth = 390`; no broken customer-work image was reported.
- CUST-001/002/003 retain their measured 1280×720 proportion; CUST-004 retains 1280×718. No work image uses `object-fit: cover` or a tall/narrow crop.
- Mobile services are a readable single-column sequence. The dark berry price `#5f1d49` measured 5.58:1–6.33:1 against the actual four service-background sample points.

`FINESSE-V4 LOCAL BROWSER QA = PASS`.

`FINESSE-V4 INDEPENDENT VISUAL ACCEPTANCE = PASS` — the independent reviewer found no remaining P0/P1: the whole-page rhythm, full work-image framing, factual business/CTA path, continuous colour field and 390px layout all meet the local client-showable gate. This remains local static-demo evidence only; it does not authorise deployment, a public link, outreach, account actions or source transfer.
# Full current-price menu expansion — 2026-09-01

- Source check: official Fresha booking flow visually inspected without sign-in, service selection, booking or data submission.
- Content check: 27 unique services rendered in three groups: Manicure 11, Spa Pedicure 11, Nails Extension 5.
- Desktop local-browser check: 1440×900; 27 menu rows; `scrollWidth === clientWidth`; 0 broken images.
- Mobile local-browser check: 390×844; 27 menu rows; `scrollWidth === clientWidth`; exact official spellings retained for `Nail art designs ( freehand painting )`, `Express pedicure(without polish)` and `Spa pedicure(without polish)`.
- Booking boundary: the only new menu action is an outbound link to the official Fresha booking URL. No form, basket, service selection, login, payment, data collection, deployment or external write was added.
- Current-source visual evidence:
  - `qa/menu-current-desktop-1440x900.png` — browser viewport 1440×900, full-page capture 1425×5813, SHA-256 `252f4d7547e09f0029bdb86dec436d979854f355c2e2bbccfe52d3c7ad580232`.
  - `qa/menu-current-mobile-390x844.png` — browser viewport 390×844, full-page capture 375×5300, SHA-256 `161e19bd7027c765a0e1f2aaac188be07a55a73425dfc841df058a5961b582a4`.
- Current-source browser facts: Desktop `scrollWidth === clientWidth`, 27 rows, 0 broken images. Mobile `scrollWidth === clientWidth`, 27 rows, 0 broken images.
- Independent-review P1 correction: duration metadata increased from 9px desktop / 8px mobile to 10px in both layouts; no content or booking-path change.
- Corrected current-source visual evidence:
  - `qa/menu-final-desktop-1440x900.png` — browser viewport 1440×900, full-page capture 1425×5826, SHA-256 `fba4c98e0d79f093f74b06fc2f213e22b2316fa4019c065df5d512950e61f97b`.
  - `qa/menu-final-mobile-390x844.png` — browser viewport 390×844, full-page capture 375×5363, SHA-256 `0eee36f43012111468f885ff3f036dd322fc8a854d1d80735a6a5140fdc8a5cb`.
- Corrected current-source browser facts: Desktop `scrollWidth === clientWidth`, 27 rows, duration metadata `10px`, 0 broken images. Mobile `scrollWidth === clientWidth`, 27 rows, duration metadata `10px`, 0 broken images.
- Self-QA: PASS. Independent review: PASS — P0=0, P1=0, local client-showable demo status renewed on the current-source screenshots.

# Hero v5 work-first redesign — 2026-09-01

- Scope: Hero-only redesign after the user rejected the prior first screen. The continuous page colour field, current type family, all facts, complete 27-service price menu, four approved customer images, links and local-static boundary were preserved.
- Desktop local-browser check: viewport 1440×900; blue manicure work frame `689.1×389.6px`, CTA bottom `627.1px` (inside the initial viewport), no horizontal overflow.
- Mobile local-browser check: viewport 390×844; blue manicure work frame `335×190.4px` appears before the heading, CTA bottom `720.4px` (inside the initial viewport), `scrollWidth = clientWidth = 375`.
- Image integrity: Hero continues to use the ledgered `CUST-001` source `.media/images/image_001.jpg` at its natural 1280×720 ratio; no crop, filter, generated material or asset replacement was applied.
- Evidence:
  - `qa/hero-v5-desktop-1440x900.png` — browser viewport 1440×900, full-page capture 1425×4949, SHA-256 `c51222da14c1cd6b947c83cebdde237865f91ada7698b0d6ce47b2ae7c643ae8`.
  - `qa/hero-v5-mobile-390x844.png` — browser viewport 390×844, full-page capture 375×5310, SHA-256 `f86a1c49f79ccd87c02a7b225a65c7990e00b61553fe2eddbdaed0e57970600e`.

`HERO V5 SELF-QA = PASS`.

`HERO V5 INDEPENDENT VISUAL ACCEPTANCE = PASS — P0=0, P1=0.` The reviewer confirmed that CUST-001 is the largest first-screen visual at natural ratio, the full image and Fresha CTA are present at 1440×900, and the 390px sequence is image → copy → full one-line CTA without clipping or horizontal overflow. The current 27-service menu, verified facts and outbound paths remain intact. This is local static-demo evidence only; it does not authorise deployment, outreach, account actions or source transfer.

# Hero v6 generated editorial image — 2026-09-01

- Trigger: the user explicitly rejected Hero v5's image and requested a newly generated, more attractive nail image.
- Asset: `assets/concept/hero-editorial-nail-concept-v2.png`, original anonymous-adult image generated through `imagegen`, 1536×1024, SHA-256 `2301b4651f36c50e55f673b1f68929ef55f4d41ba05a6d71adfddea92f75e471`. Its non-customer-work boundary is recorded in `docs/IMAGE_LEDGER.md`.
- Desktop local-browser check: 1440×900; Hero image loaded at `689.1×459.4px`; Fresha CTA bottom `639.3px`, inside the initial viewport; no horizontal overflow.
- Mobile local-browser check: 390×844; natural-ratio image loaded at `335×223.3px` before all Hero copy; CTA is fully inside the first viewport and stays on one line; no horizontal overflow or broken image.
- Evidence:
  - `qa/hero-v6-generated-desktop-1440x900.png` — browser viewport 1440×900, full-page capture 1425×4973, SHA-256 `b4eefdce5fcc76242cbdfacd5f0cb3739c323c874033a7d2f57ee497709cfcf0`.
  - `qa/hero-v6-generated-mobile-390x844.png` — browser viewport 390×844, full-page capture 375×5344, SHA-256 `d6511ade2541c87f1fed31591063acee1f010ac30db8e066c8d55f227c8556d6`.

`HERO V6 GENERATED-IMAGE SELF-QA = PASS`.

`HERO V6 GENERATED-IMAGE INDEPENDENT VISUAL ACCEPTANCE = PASS — P0=0, P1=0.` The reviewer confirmed the original concept image is a cleaner nail-specific first focus in both viewports; it is complete, unobscured and not claimed as a customer result. Hero, menu, verified facts and existing Fresha paths remain intact. This remains a local Concept Demo only; it does not authorise deployment, outreach, public publishing, account actions or source transfer.

# Violet-to-orange palette and enlarged Hero — 2026-09-01

- Scope: user-directed full-page palette change from blue→orange to one continuous deep violet→orchid→berry→burnt-orange field; Hero image scale increased only. No facts, menu rows, links, assets, forms or booking flow changed.
- Desktop local-browser check: 1440×900; Hero image loaded at `760.5×507px` (was 689.1px wide), image and CTA remain in the first viewport; `scrollWidth === clientWidth`; 0 broken images.
- Mobile local-browser check: 390×844; the `335×223.3px` Hero image precedes all Hero copy; CTA is one line and visible in the first viewport; `scrollWidth === clientWidth`; 0 broken images.
- Colour check: body computes to `#53309b → #76409e → #a7478a → #a64732`; the former blue tokens and navy copy colours are absent from the stylesheet. Pale foreground and rules are used throughout; pale amber is reserved for primary actions and actionable links.
- Evidence:
  - `qa/violet-orange-desktop-1440x900.png` — browser viewport 1440×900, full-page capture 1425×5021, SHA-256 `b18f5d957a0a3b40b06a911425e94e3b7d940ae7781feed802b4fdf40822af69`.
  - `qa/violet-orange-mobile-390x844.png` — browser viewport 390×844, full-page capture 375×5344, SHA-256 `1680e63e9c2695c6c7e8481ba9c6662a3f8fe89f720597b994c1209c81afbfc9`.

`VIOLET–ORANGE SELF-QA = PASS`.

`VIOLET–ORANGE INDEPENDENT VISUAL ACCEPTANCE = PASS — P0=0, P1=0.` The reviewer verified a single vertical violet→berry→burnt-orange field without horizontal colour blocks; the enlarged Hero image, title and full CTA remain complete on desktop; and 390px keeps image → copy → CTA with no overflow, clipping or text-on-image conflict. The complete menu and all existing Fresha paths are intact. This remains local static-demo evidence only and does not authorise deployment, outreach, public publishing, account actions or source transfer.

# Hero v7 Appointment Cover — selected direction and feathered transition — 2026-09-01

- Trigger: the user selected internal prototype direction `01 Cover` and asked for a soft image-edge transition rather than a hard split.
- Scope: local Hero-only rebuild. The generated anonymous-adult concept image, all customer facts, 27 service rows, prices, Fresha URL and the local-static boundary remain unchanged.
- Desktop 1440×900: the Hero is one appointment-cover composition: one title, concise service line, readable Fresha proof, one Fresha action and a large nail image. The image's left edge now dissolves into the matching dark-plum substrate with a CSS mask plus a plum-to-transparent overlay. There is no hard image/copy dividing line.
- Mobile 390×844: the image comes first and its lower edge dissolves into the copy surface. The headline, proof and CTA are fully visible in the captured first viewport; the formerly secondary `View menu` control is intentionally hidden at this breakpoint to keep the small-screen Hero focused and unclipped.
- Static checks: one H1; Hero keeps the exact official Fresha booking href and `CONCEPT-HERO-002` source; desktop and mobile mask declarations are present; CSS braces are balanced.
- Evidence:
  - `qa/hero-v7-cover-desktop-1440x900.png` — 1440×900, SHA-256 `fdfb8fbc2778b5049d19449df85b75fe38d65e30915081ba0a0e17764fd52630`.
  - `qa/hero-v7-cover-mobile-390x844.png` — 390×844, SHA-256 `d2bef465d9269a92e40f70c49d157c56bcc011a74fa52c88fb1b2aa9aae2d0b9`.

`HERO V7 COVER SELF-QA = PASS` — local static visual evidence only; no deployment, public link, outreach, booking-system action, account action or source-transfer authorization is implied.

# Services — single pedicure visual, compact composition — 2026-09-01

- Scope: user-directed removal of the Services hand-image figure. The section now uses exactly one original-ratio pedicure visual (`IMG-002`), paired with the hands/feet heading and the three already-present menu categories; the complete 27-row official menu remains directly below.
- Desktop 1440×2200: label, heading, category index and full pedicure image form one two-column composition; the category index fills the left lower area rather than leaving an unstructured empty field.
- Mobile 390×1700: heading precedes the single full-width pedicure image. The desktop-only category index is omitted because the complete menu immediately follows; the full feet image is shown at its natural ratio with no crop.
- Static checks: one `pedicure-service-concept-v1.png` reference; no `services-work-hands` or `.media/images/image_002.jpg` reference; three category labels present; CSS braces balanced.
- Evidence:
  - `qa/services-foot-feature-final-desktop-1440x2200.png` — 1440×2200, SHA-256 `fe53380c4e22bb34649296e6b268152fb996e0451f3ff64f96b7759f971cd0a3`.
  - `qa/services-foot-feature-final-mobile-390x1700.png` — 390×1700, SHA-256 `32ab2729b8d4dd92a23d98ec11f04ded722e35ca086aea131f8c382b8be9c1ee`.

`SERVICES SINGLE-PEDICURE SELF-QA = PASS` — local static visual evidence only; no deployment, public link, outreach, booking-system action, account action or source-transfer authorization is implied.

# Client-send polish pass — 2026-09-01

- Client-copy check: removed the dated internal menu-audit sentence and the visible `Independent concept preview` label. The page now describes current Fresha availability directly and closes with `Book via Fresha`.
- Proof check: added the existing Fresha excerpt “Lovely and friendly, treatments were fab and nails look super!” with its displayed author and 5-star attribution. It is 2 lines on desktop and source-backed by the current customer-review snapshot.
- Preservation check: 11 Manicure + 11 Spa Pedicure + 5 Nails Extension rows remain. The six Fresha links retain their original merchant slug and endpoint classes (profile, booking path and vouchers).
- Viewport evidence:
  - `qa/nine-point-final-desktop-1440x4200.png` — 1440×4200, SHA-256 `0ec352bd759990cbb7b8c459134e1e968472650010b2f9c203c4e1322b67a5a2`.
  - `qa/nine-point-final-mobile-390x4200.png` — 390×4200, SHA-256 `506eebfafd7e61cf25ad4a2ab305c1b7ff6b15d43c5042269040dffe8848c948`.

`CLIENT-SEND POLISH SELF-QA = PASS` — local static evidence only. A client-send workflow still needs an actual accessible Demo URL and separate user authorization for any deployment or message.
