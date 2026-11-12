# UKR-260 Nothing But Nails — Pre-code decision

**Scope:** local static one-page Independent Concept Demo only. No deployment, upload, email, contact, login, payment, self-hosted booking or data collection.

## Authority / known facts

- Research authority: `../../research_20260901/` and `../../PROJECT_CORE.md`.
- Candidate: `FINAL ACCEPT`, Priority B; separate current user has now authorised local Demo production.
- Identity: Nothing But Nails, Arundel, Shop/Unit 5 The Old Print Works; current booking surface is Fresha.
- Safe services: gel manicure, gel overlay, regular pedicure and gel pedicure; the older source additionally names acrylic extension, gel polish and nail art. No customer-visible pricing/hours/owner claims until recheck.
- Booking CTA: outbound Fresha link only.
- Asset state: no confirmed official customer image/logo currently usable. The Hero may use an original, anonymous-adult **nail-service concept image** as a service-signalling visual, never as client work, staff, salon, a client hand, result or testimonial. This follows the user’s 2026-09-01 correction: Hero must unmistakably communicate nail services.

## Design read and dials

**Design Read:** Arundel nail studio · polished chroma / quiet precision · register=brand · SOUL 7 · SPECTACLE 4 · DENSITY 6.

- Soul: lacquered-editorial rather than beige spa or generic pink-salon template.
- Spectacle: one restrained CSS variable-font/colour-shift hero surface; no automatic animation beyond a reduced-motion-safe hover/parallax response.
- Density: one clear identity, four verified service signals, an external booking route and no invented proof.
- Premium substrate: ink blue-black, milky cool white, electric orchid accent, chrome-silver hairlines; sharp card edges with pill-only buttons. Deliberately rejects warm cream/brass, bubbly rounded cards, fake testimonials, and a social-feed imitation.

## UK references (principle only; no copying)

| Reference | Checked | Borrowed principle | Rejected |
| --- | --- | --- | --- |
| https://www.thegardenroommolesey.co.uk/ | 2026-09-01 | A small salon can lead with a calm, specific appointment proposition and practical location/contact path. | Its copy, imagery and warm domestic aesthetic. |
| https://nailsnco.uk/ | 2026-09-01 | Boutique positioning can remain concise and image-led. | London identity, copy and visual language. |
| https://www.pommepedoursalon.co.uk/ | 2026-09-01 | Clear grouping of gel/acrylic/manicure/pedicure services. | Price list, service copy, images and busy catalogue pattern. |
| https://www.naturalnails.uk/ | 2026-09-01 | Hands and feet can form a clear browsing hierarchy. | Its luxury claims, testimonials and imagery. |

## Two directions

1. **Lacquered index (selected):** an asymmetric left-aligned identity sheet, a dark chromatic abstract hero, service sections as an editorial index, and a single Fresha handoff. It earns specificity from Arundel/verified service facts rather than invented salon imagery.
2. **Arundel appointment card:** light paper-like local guide with a map-like route, quick service tiles and booking handoff. Rejected: the material style risks implying a local story/premises we cannot prove and drifts toward a generic directory layout.

## Implementation map

| Area | Source-backed role | Visual / content decision | Planned target |
| --- | --- | --- | --- |
| Hero | Name + Arundel + nail identity | One original anonymous-adult nail-service concept visual; text wordmark; no fake nail portfolio. | `index.html#top`, `assets/concept/hero-*` |
| Service index | Four current Fresha categories | Four concise source-supported labels, no price/duration. | `index.html#services` |
| Local detail | Shop/Unit 5, Tarrant Street | Text-only factual location line; no map embed. | `index.html#visit` |
| Conversion | Existing Fresha booking | Single external link, no form/payment clone. | all `Book on Fresha` CTAs |
| Closing | Independent concept identity | Low-key `Independent concept preview`; no client-authorisation/AI/rights text. | footer |

## Skill receipts

| Skill | Concrete impact | Status |
| --- | --- | --- |
| website-delivery-sop | L0/local scope, no production/data/booking ownership, phase boundaries and explicit acceptance artefacts. DS-002B SHA-256 `5b70133e7a155a713c130d07d883afffbd1f57eaa7bfc7c2e2c3dfc9f9bb926a`, mtime 2026-08-09T16:00:52Z. | USED |
| finesse-ui | Brand Read/dials, cold-luxury token direction, one restrained hero engine, anti-template rejects and Desktop/Mobile preflight target. | USED |
| design-taste-frontend | Two materially different directions and anti-default layout decision. | USED |
| media-use | Asset audit determined platform/landlord media are not eligible; no provider/install/login was used. Drives concept-only asset ledger and forbids reuse. | USED — governance decision only |
| imagegen | Planned local concept-art fallback, not a customer-work substitute. | PENDING generation |

## Gate

`PRE-CODE GATE = PASS FOR LOCAL CONCEPT IMPLEMENTATION ONLY`.

Pass rationale: service/contact/booking facts are sufficient and the selected route prevents unverified asset claims. This does not pass asset transfer, client-showable quality, deployment, outreach or send gates.
