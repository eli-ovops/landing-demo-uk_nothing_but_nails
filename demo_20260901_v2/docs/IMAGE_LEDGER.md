# v2 Image Ledger

| ID | v2 path / SHA-256 | placement | creation / handling record | boundary |
| --- | --- | --- | --- |
| IMG-001 | `assets/concept/hero-nail-service-concept-v1.png` / 8f8016b36b3f392d28dbe184ecc8c57b4b05b6fe4bbb52573a0632d1737b4521 | Hero | original local concept created 2026-09-01; copied intact into v2 on 2026-09-01, no enhancement | original anonymous-adult concept, not customer work/staff/premises |
| IMG-002 | `assets/concept/pedicure-service-concept-v1.png` / 9a8e07809a9bb2212c72bf5ce04d3dde9197b4b9f12dc47cddd6a616027d6a47 | Services feature — Spa pedicures | original local concept created 2026-09-01; copied intact into v2 on 2026-09-01, no enhancement | original anonymous-adult concept; used to make the existing Spa Pedicure menu visually explicit, not represented as customer work |
| IMG-003 | `assets/concept/service-lacquer-concept-v1.png` / 0cc5563c0cb20cd77ff322977d3a21a94af164a20ec4c40b932202dfeb8dde23 | Closing | original local concept created 2026-09-01; copied intact into v2 on 2026-09-01, no enhancement | original non-representational concept |
| IMG-004 | `assets/concept/hero-lacquer-concept-v1.png` / 1f8b102da58e5b0b8e2cbff4f4b7ec045d380aeca3e777c500c0b3a2a92de749 | Services | original local concept created 2026-09-01; copied intact into v2 on 2026-09-01, no enhancement | original non-representational concept |

All: CUSTOMER AUTHORIZATION NOT VERIFIED; no asset is represented as a real customer result.

## Customer-authorised image amendment — 2026-09-01

The current user confirmed that the customer has authorised direct use of the four photos shown on the named Nothing But Nails Fresha merchant profile. This replaces the prior concept images in the client-visible v2 page only. It does not authorise deployment, outreach or source transfer.

| ID | local path / SHA-256 | placement | source ID / retrieved | handling record | boundary |
| --- | --- | --- | --- | --- | --- |
| CUST-001 | `.media/images/image_001.jpg` / `12c332c2acc89a2dbd4a2afa237cbf4f68fdd0be2ebaec08e629f0fabd30e44f` | Hero | Fresha 1646088 / 2026-09-01 | frozen through `media-use`; no enhancement | authorised work image; no customer identity or treatment-outcome claim |
| CUST-002 | `.media/images/image_002.jpg` / `0f5a69263d15b58837f38f47e3271fbd02fbc80c3c1378028fba7b2b91531906` | Services | Fresha 1646089 / 2026-09-01 | frozen through `media-use`; no enhancement | authorised work image; no customer identity or treatment-outcome claim |
| CUST-003 | `.media/images/image_003.jpg` / `11408c94a847ab1db18c371d2dcb0dcf233c4e1704135136182041befe006685` | Ritual | Fresha 1646090 / 2026-09-01 | frozen through `media-use`; no enhancement | authorised work image; no customer identity or treatment-outcome claim |
| CUST-004 | `.media/images/image_004.jpg` / `fa6d70411462a88d6222e5812f6e717716ee6a3852ab9cbe41e1387065666cde` | Closing | Fresha 1646091 / 2026-09-01 | frozen through `media-use`; no enhancement | authorised work image; no customer identity or treatment-outcome claim |

Exact source URLs and the authorisation scope are recorded in `CUSTOMER_ASSET_AUTHORIZATION.md`. The original concept assets remain local but are not referenced by the page.

## Hero editorial concept replacement — 2026-09-01

The current user rejected the Hero visual and explicitly requested a newly generated, more refined nail image. `imagegen` created this original anonymous-adult editorial concept; `media-use` recorded the project-bound asset and its non-representational boundary. It replaces only the Hero source. The four authorised Fresha photos remain unmodified and continue in the other page placements.

| ID | local path / SHA-256 | placement | creation / handling record | boundary |
| --- | --- | --- | --- | --- |
| CONCEPT-HERO-002 | `assets/concept/hero-editorial-nail-concept-v2.png` / `2301b4651f36c50e55f673b1f68929ef55f4d41ba05a6d71adfddea92f75e471` | Hero | original image generated locally with `imagegen` on 2026-09-01; 1536×1024; copied intact into the Demo; no image alteration after generation | anonymous-adult concept image, not a customer, staff member, premises, logo, or verified Nothing But Nails treatment result; local Concept Demo only |
