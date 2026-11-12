# v2 Pre-code decision

Authority reloaded: `AGENTS.md`, `PROJECT_CORE.md` 14.2A/14.3–14.6, research_20260901, and all applicable local Skills before customer-visible implementation.

**Purchase thesis:** UK / GBP / £99 AS-SHOWN HANDOVER or £199 ONE PERSONALISED UPDATE. The static page makes Nothing But Nails, Arundel, four verified treatment choices and the current Fresha booking route legible in one shareable business path; it does not replace booking. Sources: research `SOURCE_LEDGER.md` SRC-01/02.

**Design Read:** Arundel nail salon · chromatic studio precision · brand · SOUL 8 / SPECTACLE 5 / DENSITY 6. `DESIGN_VARIANCE=8`, `MOTION_INTENSITY=3`, `VISUAL_DENSITY=6`. Reject pink/cursive/rounded-price-card salon templates, beige-brass wellness, text-only services and fake reviews. Tokens: #080B18 / #E9EDF7 / #235EFF / #6A39E7 / #A9B8D8. Display: Bodoni Moda, Georgia, serif. Body: Helvetica Neue, sans-serif. Never Arial.

## Opened UK reference board — 2026-09-01

Every URL below was opened during the pre-code review. It is a decision reference, not a source of copy, images, layout or claims.

| Opened reference | Unique principle → selector | Explicit non-copy boundary |
| --- | --- | --- |
| [Iris Avenue](https://www.irisavenue.com/) — opened 2026-09-01 | distinct nail/pedicure image roles support the editorial split of `#services` and `#ritual` | no copy, London identity, awards, service language, layout or imagery |
| [Nails & Co.](https://nailsnco.uk/) — opened 2026-09-01 | a concise boutique proposition can leave the booking CTA visible in `#hero` | no copy, identity, palette, composition or imagery |
| [Saturn Beauty Bar](https://www.saturnbeautybar.com/) — opened 2026-09-01 | location and booking form a decisive close in `#visit` | no testimonials, warm-stone visual language, claims, copy, images or layout |
| [MAU Beauty](https://maubeauty.co.uk/) — opened 2026-09-01 | treatment categories can be scanned before the booking handoff in `#services` | no catalogue, prices, ratings, testimonial, copy, images or layout |

## Two comparable directions

| Direction | Hero & material roles | Section rhythm | Bottom 40 mechanism | Purchase thesis / decision |
| --- | --- | --- |
| **A — Studio Chromatic (selected)** | one cobalt manicure image held in a dark asymmetrical hero; distinct lacquer, pedicure and non-figurative images later; cool ink/chrome/orchid substrate | identity split → asymmetric four-service index → hand/foot editorial interval → address route → image-led booking close | `#visit` gives the precise verified street location beside the existing Fresha route, then `#close` resolves to one factual action | A visitor sees an actual nail service immediately, then can recognise services, place and booking route without confusing the site for a marketplace profile. |
| **B — Arundel Colour Book (rejected)** | light paper field with a single narrow manicure crop; lacquer texture as a later divider, pedicure as the final panel | location masthead → colour-book service columns → full-width pedicure panel → address strip → compact Fresha footer | a labelled address strip would lead directly into a small booking panel | It is technically credible but reads like a beauty catalogue / local directory at 390px, makes the original nail visual feel secondary, and has less commercial pull than A. |

| Section | task / source | selector and responsive layout | boundary |
| --- | --- | --- | --- |
| Hero | 5-sec identity, IMG-001 + name/Arundel | `#hero` split, image-top mobile | pointer light strip; static reduced-motion; concept only |
| Services | four verified choices, IMG-004 | `#services` asymmetrical 1+3 → stack | no prices/availability |
| Ritual | hands/feet, IMG-002 | `#ritual` image split → image-first | no technique claim |
| Place | new commercial info: address + booking path | `#visit` route composition → stack | no map/form |
| Closing | Fresha handoff, IMG-003 | `#close` image close → tall crop | static poster fallback |

Shown: name, Arundel, four services, Fresha. Reserved: prices, availability, owner/team, reviews, portfolio, payment and form. The selected direction uses a quiet grain, tinted borders and one orchid accent, but does not repeat a single card system: hero split / list index / image interval / route composition / editorial close. Hero max two lines/one CTA; 44px targets/focus/AA/mobile stack; no fake metrics, copied material, internal text or AI/rights claims.

## Skill receipts and implementation impact

| Skill | Read receipt | Produced decision / artifact | Visible implementation impact |
| --- | --- | --- | --- |
| `website-delivery-sop` | local `SKILL.md` read for this local-only concept scope | isolated `demo_20260901_v2`, no deploy/upload/contact/data collection, explicit QA package boundaries | `index.html` may contain only static outbound Fresha links; no form, booking clone, analytics or production language |
| `finesse-brief` | local `SKILL.md` plus discovery/hook guidance read | `DEMO_BRIEF.md`: five-second visitor job, factual hierarchy and single conversion path | `#hero` must carry name/Arundel/nail signal/CTA; `#visit` must finish the business route rather than add generic filler |
| `finesse-ui` | local redesign, soul, design-DNA, anti-cheap and preflight guidance read | Design Read; SOUL 8 / SPECTACLE 5 / DENSITY 6; `DESIGN_VARIANCE=8`; rejection list and selected Direction A | token system and `#hero/#services/#ritual/#visit/#close` use five different compositions; Bodoni Moda/Georgia + Helvetica Neue, never Arial; one static light-strip detail with reduced-motion-safe state |
| `frame-smith` | `SKILL.md` and environment gate read; `bash .../scripts/check-runtime.sh .` found skill files but no renderable project | `NOT VERIFIED — NO RENDERABLE PROJECT`; no motion asset, video, render or installation | `#hero` light strip and every other section remain CSS-static; `@media (prefers-reduced-motion: reduce)` removes any transition if one is later introduced |

## Cross-Demo Similarity Check

Compared with the nearest prior own version, `../demo_20260901/index.html`, and the nearest adjacent beauty demo, `../../client_uk_wild_clover_skin_care/demo_v4_20260823/index.html`, on 2026-09-01. This checks direction, not an artificial business-name uniqueness rule.

| Dimension | v2 selected A | v1 / Wild Clover contrast |
| --- | --- | --- |
| business signal | full-frame cobalt manicure at first fold | v1 has a generic dark split; Wild Clover opens with a facial-treatment composition |
| substrate | ink / chrome / electric orchid | v1 cool monochrome/violet; Wild Clover cream, black, red, yellow and blue bands |
| headline voice | compact chromatic title lockup | v1 oversized sentence with line breaks; Wild Clover soft editorial facial statement |
| service architecture | asymmetric 1+3 index | v1 symmetric 2×2 list; Wild Clover three price/duration bands |
| image rhythm | four non-repeating visual roles across page | v1 uses two images; Wild Clover has a four-photo treatment grid |
| location treatment | route-composition information block | v1 violet two-column visit band; Wild Clover plain visit panel |
| CTA cadence | one outward Fresha handoff repeated only at decision points | v1 repeats conventional pill CTAs; Wild Clover uses booking button pattern with inline arrows |
| device response | hero image first, index stacks by service, route becomes a vertical path | v1 simply collapses its existing grid; Wild Clover is a different editorial-band stack |
| texture / geometry | hairline chrome, square panels, restrained grain | v1 rounded buttons / flat panels; Wild Clover uses broad coloured bands |
| proof boundary | no reviews, portfolio or invented service claims | Wild Clover legitimately uses published reviews and treatment-method claims; v2 deliberately does not |

`CROSS-DEMO SIMILARITY CHECK = PASS` — the business facts, imagery, substrate, information rhythm and mobile composition are materially distinct; no prior demo’s copy, imagery or code will be reused.

## v3 Hero Direction Amendment — 2026-09-01

**Trigger:** user judged the current Hero insufficiently attractive. This is a direction-level Hero redesign, not a superficial font-size patch. Everything below `#services`, all verified facts, the four-image storyboard, the Fresha URL and local-only scope remain protected.

**Design Read:** Arundel nail salon · lacquered cutout editorial · register=brand · SOUL 9 / SPECTACLE 4 / DENSITY 5 · Hero Engine: CSS-only chromatic shutter around the actual manicure image. `DESIGN_VARIANCE=9`, `MOTION_INTENSITY=3`, `VISUAL_DENSITY=5`.

The rejected default is a dark two-column “text left / photo right” salon hero with a generic lifestyle headline. It already reads competently, but it does not make this salon's name or nail image feel like the object of attention.

| Direction | Composition | Decision |
| --- | --- | --- |
| **Cobalt cutout masthead (selected)** | `.hero` becomes a full-height image stage. The actual manicure is the dominant surface; oversized `Nothing / but / Nails.` type cuts across the image edge, with a single black booking control and a thin cobalt shutter plane. Mobile is a deliberate image → type → CTA stack. | Turns the business name and nail work into one recognisable mark while preserving an immediate booking path. |
| Lacquer label sheet (rejected) | Cream label over a narrow nail crop, with product-like service tags and a large serial number. | Risks looking like cosmetic packaging rather than a place to book a nail appointment. |

**Skill receipts and impact:**

| Skill | Read receipt | Produced decision | Exact impact |
| --- | --- | --- | --- |
| `finesse-ui redesign` | `SKILL.md`, `redesign-mode.md`, `hero-engines.md`, `design-dna.md`, `anti-cheap.md` and `preflight.md` read for this change | the split composition and generic headline are the highest-leverage failure; CSS-only is the appropriate SPECTACLE 4 engine | replace the `.hero-grid` two-column composition while retaining a static complete reading state |
| `design-taste-frontend` | local `SKILL.md` read for this redesign; its brief inference, anti-default, responsive variance and pre-flight rules applied | reject generic dark text-plus-photo split, repeated tiny section labels and automatic decorative motion; choose a business-name masthead with deliberate 390px collapse | rewrite `.hero-rail`, `.hero-top`, `.hero-grid`, `.hero-copy`, `.hero-image`, `.hero-scroll` and their `@media (max-width:760px)` rules; remove hero eyebrow rather than adding a new one |
| `website-delivery-sop` | local `SKILL.md` read for local L0 scope | preserve an isolated local static presentation boundary | edits stay in `index.html` Hero markup and Hero CSS only. No deployment, upload, form, data collection or booking ownership. |

**Selector-level implementation boundary:**

| Allowed to change | Exact scope |
| --- | --- |
| `index.html` | only the markup between `<section class="hero" id="top" ...>` and its matching `</section>` |
| `styles.css` | only `.hero`, `.hero::after`, `.hero-rail`, `.hero-top`, `.wordmark`, `.top-link`, `.hero-grid`, `.hero-copy`, `.hero h1`, `.hero-intro`, `.hero-image`, `.hero-image img`, `.hero-image::after`, `.hero-image figcaption`, `.hero-scroll` and the matching mobile rules |
| Existing asset | `assets/concept/hero-nail-service-concept-v1.png` only, unchanged file/hash |

**Protected, must not change:** every `#services` and later HTML block; every non-Hero CSS rule; the four service labels, address, all Fresha href values, all other image resources, the asset ledger and image hashes.

**Desktop and 390px locks:** Desktop uses a `min-height: 820px` Hero with `IMG-001` covering the dominant right/centre stage, object-position locked to the visible blue nails; headline is maximum three deliberate lines with no crop; CTA is inside the initial 900px viewport. At 390px, the image comes first at 430–460px high, the heading then uses a maximum three lines and `clamp()` sizing without horizontal overflow, and the CTA remains visible directly after the subline. The shutter is a static CSS plane; it has no loop, no scroll listener and no Frame-smith claim.

**Pre-flight changes:** no new font family, business fact, image, service, CTA URL, external dependency, automatic animation or device requirement. The hero still has one CTA, no more than four information groups, a static/reduced-motion state and a 390px-specific layout.

`HERO V3 PRE-CODE REVIEW = PASS — Hero-only local implementation permitted.`

`PRE-CODE GATE = PASS — Hero V3 amendment independently reviewed.`

## v4 Whole-page rhythm amendment — 2026-09-01

**Trigger:** the user explicitly requested another `finesse-ui` pass and a whole-page optimisation after judging multiple areas visually awkward. This is a direction-level rhythm and image-framing rebuild, not another isolated colour or crop patch.

**Design Read:** Arundel nail studio · tactile appointment folio · register=brand · SOUL 8 / SPECTACLE 3 / DENSITY 6 · Hero Engine: deliberately restrained CSS/static image stage. `DESIGN_VARIANCE=7`, `MOTION_INTENSITY=2`, `VISUAL_DENSITY=6`.

**Protected:** all verified business facts, service names, address/hours/contact details, every Fresha/Instagram/Facebook URL, the four customer-authorised original image files and their ledger entries, local-only static scope, the single booking path, and the user-approved vertically flowing blue → pink → orange page colour field. No deployment, outreach, account action, data collection, or image generation/alteration.

### Audit → priority changes

| Finding | Evidence in current composition | Redesign response |
| --- | --- | --- |
| Work images are repeatedly forced into incompatible tall/narrow crops | the closing photo was 428px wide by 600px high against a 16:9 source; similar `object-fit: cover` framing appears across the page | every customer work image gets a wide, natural-ratio stage; use `contain` only where a complete image matters more than fill |
| The page feels like several unrelated posters | oversized name, oversized NB monogram, large isolated section headlines and small labels compete for attention | replace the poster rhythm with one continuous appointment folio: identity → work → services → location → booking |
| The visual hierarchy is too abstract for a nail business | hairline circles, diamonds and typographic panels receive more area than finished nails | retain only quiet hairlines; make real nail work the primary visual evidence in Hero, service proof, treatment interval and final action |
| Closing does not resolve naturally | NB, copy and a contained photo compete across three columns | remove the standalone NB-poster role; make a full, complete nail-work photograph and factual booking control the final payoff |

### Finesse decisions and implementation map

- **Rejected lazy defaults:** pink cursive / round salon cards; dark tech split hero; faux-luxury editorial typography; photos used as cropped texture; generic "ready to book" poster close.
- **Premium substrate:** a single named vertical colour field, quiet grain, translucent navy hairlines, no opaque coloured panels, one deep-berry action colour, and one humanist sans type system with compact metadata. The accent is action-only; photos own the emotional colour.
- **Layout direction:** `Hero` uses a compact identity/booking block followed by a complete wide manicure image; `Services` pairs a concise four-treatment index with a complete French-tip work image; `Ritual` uses the foil-nail work as an image-led visual interval rather than a giant text poster; `Visit` becomes a compact factual route; `Closing` becomes a wide complete nude-nail image plus the single Fresha handoff. Mobile preserves that sequence without any tall image crop or horizontal overflow.
- **Full-page storyboard:** CUST-001 (blue manicure) = first recognition; CUST-002 (French tips) = service quality; CUST-003 (foil nail art) = creative range; CUST-004 (nude extensions) = calm final booking proof. No asset repeats and no customer-work image is altered.

### Skill receipts

| Skill | Read receipt | Produced decision / artifact | Exact implementation impact |
| --- | --- | --- | --- |
| `finesse-ui redesign` | `SKILL.md`, `redesign-mode.md`, `design-dna.md`, `anti-cheap.md`, `style-personas.md`, `preflight.md` | audit, Design Read, constrained static Engine and tactile-folio rhythm | replace the poster-like section geometry and photo crop rules across `index.html` and `styles.css`; preserve static/reduced-motion fallback |
| `design-taste-frontend` | `SKILL.md` read for this brand redesign | reject default gradient/large-type landing-page formula; make real customer work and clear booking job decide the layout | reduce redundant eyebrow hierarchy, lock one action accent, specify deliberate desktop/mobile image ratios |
| `media-use` | `SKILL.md` read; existing `CUST-001`–`CUST-004` ledger inspected | media intent is reframing only; no grade, generation, replacement, upload or derivative treatment | source files/hashes remain unchanged; CSS may resize and fully reveal them in their recorded placements |
| `website-delivery-sop` | previous local L0 read receipt remains applicable; static/no-deploy boundary reconfirmed | retain local static demo and outbound booking links only | no new dependency, API, form, login, deploy or production claim |

### Selector, content and image-frame locks

| Page role / protected asset | Allowed HTML scope | Allowed CSS scope | Desktop image lock | 390px image lock |
| --- | --- | --- | --- | --- |
| `CUST-001` blue manicure / Hero | only the existing `.hero` inner arrangement; exact `src`, alt text, name, proof facts and Fresha `href` remain byte-for-byte unchanged | `.hero*`, `.work-frame` | `img.hero-work-image`: natural 1280:720 ratio, `width:100%; height:auto`; no `object-fit:cover`, no crop, no image filter | same natural ratio, image remains a direct full-width block above the first booking action |
| `CUST-002` French tips / Services | only the `#services` structural wrappers; four service names, durations/prices and existing text remain unchanged | `#services`, `.service-*`, `.work-frame` | `img.services-work-image`: natural 1280:720 ratio, full visible work; no fixed portrait height or crop | one-column stack: work image first, followed by service index; natural ratio retained |
| `CUST-003` foil art / Ritual | only the `.ritual` structural wrappers; paragraph and Fresha `href` unchanged | `.ritual*`, `.work-frame` | `img.ritual-work-image`: natural 1280:720 ratio, full visible work; no crop or image treatment | copy then direct full-width image; natural ratio retained |
| `CUST-004` nude extensions / Closing | only the `.closing` inner arrangement; CTA label/href and concept-preview footer text unchanged | `.closing*`, `.work-frame` | `img.closing-work-image`: natural 1280:718 ratio, full visible work; no standalone NB panel or forced tall image slot | copy/CTA then direct full-width image; natural ratio retained |

**Global implementation allowlist:** only `<main>` section wrappers and classes may be rearranged, plus all associated CSS selectors needed to realise the sequence. All `href`, `src`, `alt`, verified fact strings, price/duration strings, footer content, image files, asset hashes, `docs/IMAGE_LEDGER.md`, `docs/CUSTOMER_ASSET_AUTHORIZATION.md`, and local-only delivery boundary are immutable in this pass. There will be no new visible copy, no removed business fact, no new external request, no dependency, no JavaScript, no `<canvas>`, and no animation beyond existing hover transitions.

**Responsive locks:** at `390px`, every former multi-column region uses one column; `documentElement.scrollWidth === clientWidth`; all work images use their natural full width and full height ratio; button labels remain one line; the booking path is visible in Hero and Closing. At Desktop `1440px`, each photo remains fully visible at its native ratio, without a tall/narrow crop, and all confirmed booking/contact links remain reachable.

**PRE-CODE GATE = AWAITING INDEPENDENT v4 REVIEW — no client-visible rebuild before independent review.**

## Current-menu expansion — 2026-09-01

**Trigger:** the user required every current customer service price to be visible in the Demo, rather than a four-item featured excerpt.

**Source:** the official Fresha booking flow was visually read on 2026-09-01, without sign-in, selection, booking or data submission. It exposed 27 unique bookable services grouped as `Manicure` (11), `Spa Pedicure` (11) and `Nails Extension` (5).

**Implementation mapping:** `index.html` replaces the four-item `.service-list` with the complete three-group `.price-menu`; every service keeps its current Fresha title, duration and price. `styles.css` uses a single uninterrupted price-sheet treatment: three ruled columns at desktop and a one-column sequence at 390px. No extra action colours, images, external asset, booking clone, availability claim, JavaScript or form was added. The sole handoff is the existing official Fresha booking URL under the menu.

**Truth boundary:** this is a dated price/menu snapshot, not a promise of future availability. The customer-visible note directs visitors to Fresha for live availability.

**MENU CONTENT EXPANSION = PASS — final Desktop/390px QA and independent review completed; 27 services are readable without overflow.**

## Hero direction v5 — 2026-09-01

**Trigger:** the user rejected the current Hero and explicitly requested a new Hero design. This is a Hero-only direction rebuild, not a global palette, content, asset or pricing change.

**Design Read:** Arundel nail studio · work-first appointment editorial · register=brand · SOUL 8 / SPECTACLE 2 / DENSITY 5 · Hero Engine: static CSS composition. The rejected default is oversized brand typography on a largely empty field with the nail work deferred below the fold. The selected direction gives the real manicure work the first visual priority.

| Direction | Composition | Decision |
| --- | --- | --- |
| **A. Work-first appointment spread (selected)** | Desktop: the full, natural-ratio blue manicure image occupies the immediate left stage; a concise appointment block sits at right on the unchanged continuous blue field. Mobile: image first, then the same compact information and booking path. | This fixes the actual issue: the first screen reads as a nail salon before it reads as a typographic concept. |
| B. Full-bleed image with text overlay | The blue manicure is full-bleed with name, proof and action layered over it. | Rejected because protecting readable text would require a heavy image overlay, while mobile would either crop the work or dilute the visual impact. |

**Finesse / design-taste impact:** `finesse-ui` is used in redesign mode to reduce the Hero's visual debt by moving the genuine customer work above the fold, limiting the text stack to location, title, short service statement, proof and one action. `design-taste-frontend` rejects the previous large-empty-field / oversized-display default and locks the viewport-first hierarchy: one image, one heading, one external booking action. The page keeps its one vertical colour field and deep-berry action token. `SPECTACLE=2`: no automatic motion, canvas, carousel, overlay labels or decorative geometry is added; existing reduced-motion fallback remains valid.

| Skill | This-round read receipt | Produced decision | Exact selector / viewport impact |
| --- | --- | --- | --- |
| `finesse-ui redesign` | `SKILL.md`; `references/redesign-mode.md` audit, `design-dna.md` substrate and type-tension rules, `anti-cheap.md` hero/imagery blacklist, `preflight.md` Hero and mobile gates | Audit isolated the Hero as the failing module: its empty type-first order delays the real service evidence. The selected repair is a static work-first composition, not an unrelated page rebuild or an invented visual engine. | `.hero` becomes the compact two-part stage; `.hero-work` precedes `.hero-copy` in visible priority; `.hero-copy` is capped to the factual title, short service statement, proof and `.hero-book`; `.hero h1` reduces to a two-line maximum; mobile `.hero` becomes a single image-first stack. |
| `design-taste-frontend` | `SKILL.md` redesign mode, hierarchy, anti-default and final pre-flight guidance read | Reject text-over-photo and a second giant empty typographic field. Keep one continuous page theme, a single deep-berry action, natural customer-image framing and an explicit 390px collapse. | `.hero-work img` retains `width:100%; height:auto` without crop/filter; `.hero-copy` has no photo overlay; `.hero-book` remains one line with a 50px target; `@media (max-width:760px)` places the image before all hero copy and preserves `scrollWidth === clientWidth`. |

**Implementation boundary:** only the `.hero` HTML arrangement and matching `.hero*` CSS may change. Preserve all exact business facts, `image_001.jpg` source/hash/alt, every external href, full menu, images below the Hero, the unified background, current font family, local-static boundary and footer. `image_001.jpg` remains a visible natural-ratio image with no `object-fit: cover`, filter, generated content, crop or asset treatment. Desktop target: image and booking CTA are both present in the initial 1440×900 screen. Mobile target: 390px has image first, compact readable copy after it, a one-line CTA, no horizontal overflow and no text over the nail image.

**HERO V5 PRE-CODE GATE = PASS — independent reviewer completed the pre-code check with P0=0 and P1=0. The approved scope is limited to the Hero HTML arrangement and matching `.hero*` CSS.**

## Hero v6 image-material replacement — 2026-09-01

**Trigger:** after viewing Hero v5, the current user explicitly rejected the visual and directed creation and use of a more attractive, original nail image.

**Scope:** material-only Hero update. The approved v5 work-first layout, continuous colour field, title, facts, CTA, 27-service price menu, all outbound links and mobile ordering remain unchanged. The only customer-visible DOM change is the Hero image source, alt text and removal of the image overlay label. The prior `CUST-001` file remains preserved and used nowhere else; it is not modified or deleted.

**Creative read:** a warmer rose-nude manicure with a delicate coral micro-tip and gold foil detail creates a cleaner premium beauty signal than the heavy saturated-blue service snapshot. It is framed at its native 3:2 ratio with no crop, filter or text overlay. The image is an original anonymous-adult concept, explicitly ledgered as non-customer work; the page does not call it a real customer result.

**HERO V6 MATERIAL GATE = PASS — explicit user direction; no new capability, external write, deployment, booking clone, factual claim or layout direction introduced.**

## Violet-to-orange colour refinement and Hero scale — 2026-09-01

**Trigger:** the current user explicitly asked for the entire Demo to move from a blue-to-orange field to one continuous purple-to-orange field, and for the Hero image to be larger.

**Finesse colour decision:** keep the single, uninterrupted vertical field but reject the generic light blue/pastel treatment and the equally generic purple-neon treatment. The chosen static substrate is deep violet `#53309b` → orchid `#76409e` → berry `#a7478a` → burnt orange `#a64732`, with one pale-amber action `#ffbc80`. Text, rules and metadata are now tinted pale rather than navy, so the colour remains continuous without low-contrast dark text on purple.

**Exact implementation:** `styles.css` updates the root tokens, body gradient, quiet rules, secondary copy and primary action colour. `.hero-stage` changes from `1.18fr/.82fr` to `1.3fr/.7fr`, making the natural-ratio Hero image about 10% wider at 1440px (689.1px → 760.5px) while retaining the CTA in the first viewport. No HTML facts, price rows, image files, links, booking path, responsive stack or local-static boundary change.

**Finesse receipt:** `redesign-mode.md` isolated colour/substrate and Hero scale as the only failing modules; `design-dna.md` supplied the one-token accent lock, tinted light foreground and grain substrate; `anti-cheap.md` rejected blue-to-orange pastels and generic purple glow; `preflight.md` requires both viewport and contrast/readability checks. `SOUL=7 / SPECTACLE=2 / DENSITY=5`; no new motion or visual engine is added.

**VIOLET–ORANGE REFINEMENT GATE = PASS — direct user approval for the palette/action-colour change; implementation remains local, static and reversible.**

## Hero v7 — selected Appointment Cover and feathered image transition — 2026-09-01

**Trigger:** the user selected prototype direction `01 Cover` and explicitly requested a softened, feathered transition where the Hero image meets the information surface.

**Selected composition:** a single dark-plum appointment cover contains one title, concise service statement, readable Fresha proof and the external Fresha action at left; the original anonymous concept manicure image occupies the larger right stage. This intentionally replaces v6's ordinary image-left/copy-right split and removes the duplicate wordmark. The image does not imply customer work and remains ledgered as `CONCEPT-HERO-002`.

**Feather treatment:** `.hero-work-image` uses a CSS horizontal mask and `.hero-work::after` uses a plum-to-transparent overlay, so the image dissolves into the same plum substrate rather than stopping at a hard vertical edge. At 390px the same source uses a bottom mask and plum overlay, so the image recedes softly into the copy below. No image pixels, asset file, alt text, URL, service/menu information, booking path or customer fact changes.

**Skill impact:** `finesse-ui` Brand Hero guidance informed the one-image, one-title, one-action cover hierarchy; its anti-cheap scan rejected a second brand title, a boxed card on top of the photo and a hard image boundary. `website-delivery-sop` confirms this is a local, static L0 visual revision only: no deployment, data collection, booking integration, account action or public release.

**HERO V7 COVER GATE = PASS — direct user direction; scope limited to Hero HTML/CSS and this internal decision record.**

## Service visual clarification — hands and feet — 2026-09-01

**Trigger:** the user noted that “For hands. For feet.” was not sufficiently expressed because the Services section contained only a manicure image.

**Media-use decision:** inspected existing ledgered candidate `IMG-002` (`assets/concept/pedicure-service-concept-v1.png`, 1024×1536) before resolving or generating anything new. It clearly depicts a navy gel pedicure and is a better grounded fit than a fresh generic image. No provider, network, account or new asset was used.

**User-directed layout replacement:** remove the hand-image figure entirely. Rebuild `#services` around one compact feature composition: label and headline begin at the same top edge as original-ratio `IMG-002` (Spa pedicures), while the existing three menu categories form a small index at left and the price menu follows immediately below. On mobile the title precedes the one full-width foot image and the index is omitted because the full price menu is directly next. This removes the prior two-image stack and unstructured empty zone without changing any official menu row.

## Client-send polish pass — 2026-09-01

**Design Read:** independent Arundel nail salon · polished, friendly beauty editorial · register=brand · `SOUL=8 / SPECTACLE=2 / DENSITY=6` · existing CSS feathered-media cover retained.

**Audit and protection rules:** retain the user-approved violet-to-orange substrate, Hero composition, natural-ratio pedicure image, all three menu groups and 27 official price rows, address, hours, contact details and every Fresha destination. Retire only client-visible internal language, the date-stamped internal menu note and generic supporting copy. No deployment, recipient contact or booking-system action is included.

**Skill impact:** `finesse-ui redesign` identified unstructured client-facing metadata and under-used proof as the highest leverage fixes rather than a new Hero. Its anti-cheap pass retained the single colour lock, subtle grain and one image-led hierarchy. `design-taste-frontend` reinforced a single-page theme lock, restrained static treatment and a short source-backed quote rather than added decorative effects. `media-use` kept the existing ledgered customer nail-art image unchanged and verified that no new asset or provider was needed. `website-delivery-sop` keeps the result L0 local static only.

**Implementation:** replace the dated menu-audit sentence with a direct Fresha availability message; replace the generic Ritual copy with an existing 5-star Fresha review excerpt and attribution; replace the visible `Independent concept preview` footer label with `Book via Fresha`. No customer fact, menu row, media asset or destination URL was added, altered or removed.

**CLIENT-SEND POLISH GATE = PASS (LOCAL STATIC ONLY)** — visual/client-copy polish has passed local Desktop and mobile review. This does not create an externally accessible Demo URL and does not authorise deployment or outreach.
