# Topical Authority — karpet.lantai.id

## Role and boundary

Karpet.Lantai.id is a specialist shop-and-installation property for fitted carpet, loose rugs, artificial turf, and functional soft-floor systems. The knowledge plan helps Indonesian buyers, designers, facility teams, and installers choose a system, prepare the substrate, specify performance, install it, and maintain it. Product and installation routes own quotations, stock, service coverage, and sales conversion; articles must remain decision support rather than disguised location pages.

Performance and health claims are evidence-gated. Fiber composition, pile construction, backing, dimensions, and care limits require a current technical data sheet. Adhesive compatibility, open time, substrate moisture limits, and conditioning require manufacturer instructions plus site measurements. Fire, VOC/emissions, slip, acoustics, thermal behavior, antistatic performance, colorfastness, durability class, and sports/playground impact claims require an applicable test report, certification, or project standard—not generic labels such as “aman,” “antibakteri,” or “kedap suara.” Prices, warranties, recycled content, and service life must be dated and tied to a named supplier or documented project condition.

## Context used

- Four sitemap files resolve to 10 unique page URLs: the homepage, `karpet`, `karpet/bahan`, four material pages, `berita`, `tentang-kami`, and `kontak-kami`.
- Homepage copy positions the site as a carpet and rug shop with installation support; `/karpet/`, `/pasang/`, and `/permadani/` are the principal commercial families.
- Compact tracked-route evidence adds 19 material hub/detail routes, 23 artificial-turf specification routes, seven carpet-design routes, nine functional/sport carpet routes, five room-installation routes, and five rug-origin routes.
- Representative specialist routes include `karpet/padel`, `karpet/playground-anak`, `karpet/bela-diri-tatami`, `karpet/gym-fitness`, `karpet/olahraga-indoor`, and `karpet/garasi-bengkel`.
- Repository base inspected: `01bae8624d6ad75a554277d7b994686bffb064b8` on `main`.

## Ignored template noise

- Ignored 3,951 location-swapped sales pages: 422 martial-arts, 455 garage/workshop, 446 golf, 430 gym/fitness, 444 indoor-sport, 444 padel, 431 playground, 443 running-track, and 436 yoga/aerobics variants.
- Ignored 36 news-pagination routes, 12 category archives, generator folders, feeds/comments, and 5,854 WordPress asset files as non-editorial coverage.
- Repeated product metadata, city names, sales claims, and near-identical page bodies were counted but not treated as separate knowledge intent.

## Topical map

| Topic ID | Parent topic | Reader outcome | Boundary | Article target |
|---|---|---|---|---:|
| KPT-01 | Carpet-system fundamentals | Decide whether fitted carpet is appropriate and form a usable selection brief. | Owns first-principles selection; material chemistry belongs to KPT-02 and quotations stay on `/karpet/`. | 6 |
| KPT-02 | Fibers and material behavior | Compare fibers using documented wear, moisture, stain, feel, and care properties. | Owns fiber behavior, not pile construction in KPT-03 or room styling in KPT-07. | 6 |
| KPT-03 | Construction, backing, and format | Distinguish pile types, backing systems, rolls, tiles, and modular formats. | Owns how carpet is built; substrate layers belong to KPT-04 and installation execution to KPT-05. | 6 |
| KPT-04 | Subfloor, moisture, and underlay | Assess the base and specify preparation before carpet arrives. | Owns substrate readiness and underlay; laying, seaming, and transitions belong to KPT-05. | 6 |
| KPT-05 | Installation methods and detailing | Choose and inspect a compatible installation method. | Owns installation execution and details; commercial service booking stays on `/pasang/`. | 6 |
| KPT-06 | Residential room applications | Match carpet systems to bedrooms, living rooms, stairs, and family use. | Owns room-use requirements, not color composition in KPT-07 or loose rugs in KPT-08. | 6 |
| KPT-07 | Design, color, pattern, and sizing | Build a visual specification without sacrificing function or maintenance. | Owns aesthetic decisions; system suitability belongs to KPT-01 and rug placement to KPT-08. | 6 |
| KPT-08 | Rugs and permadani | Select, size, stabilize, and care for movable rugs. | Owns loose floor coverings; wall-to-wall carpet belongs to KPT-01–KPT-07 and sales to `/permadani/`. | 6 |
| KPT-09 | Commercial and institutional carpet | Specify carpet for offices, hospitality, worship, and other high-use interiors. | Owns occupancy and operational requirements; measured performance tests belong to KPT-12. | 6 |
| KPT-10 | Indoor sports, gym, yoga, and martial arts | Select sport-specific soft flooring by movement, impact, grip, and hygiene needs. | Owns indoor activity surfaces; synthetic turf sports belong to KPT-11 and playground falls to KPT-12. | 6 |
| KPT-11 | Artificial turf, padel, golf, and running surfaces | Specify turf assemblies by sport, drainage, pile, infill, and maintenance. | Owns synthetic-grass sports systems; decorative carpet fibers belong to KPT-02 and playground surfacing to KPT-12. | 6 |
| KPT-12 | Safety and measured floor performance | Verify slip, impact, fire, acoustics, static, and accessibility requirements. | Owns testable performance criteria; health/emissions belong to KPT-13 and sport selection to KPT-10–KPT-11. | 6 |
| KPT-13 | Indoor air, allergy, and hygiene | Control dust, moisture, emissions, and sanitation risks with evidence-based routines. | Owns exposure and hygiene; ordinary stain care belongs to KPT-14 and defect diagnosis to KPT-15. | 6 |
| KPT-14 | Cleaning, stain control, and maintenance | Create routines that preserve appearance without damaging the system. | Owns preventive and routine care; repair/replacement decisions belong to KPT-15. | 6 |
| KPT-15 | Defects, repair, and replacement | Diagnose common failures and decide whether to repair, relay, or replace. | Owns observed failure response; installation prevention belongs to KPT-04–KPT-05. | 6 |
| KPT-16 | Measurement, estimating, and procurement | Calculate quantities and compare offers on a like-for-like basis. | Owns takeoff and buying controls; published prices and transactions remain on commercial routes. | 6 |
| KPT-17 | Warranty, handover, and lifecycle | Document acceptance, warranty conditions, service life, and end-of-use decisions. | Owns post-installation governance; daily maintenance belongs to KPT-14 and initial procurement to KPT-16. | 6 |

## Internal-link rule

Each KPT topic becomes a hub linking to its six briefs, and every brief links back to that hub. Selection pages link forward to the relevant material, construction, subfloor, installation, performance, maintenance, and procurement owners. Diagnostic pages link backward to prevention and forward to repair or replacement. Commercial links appear only where a reader has completed a legitimate product or installation decision. Repeated entities keep one intent owner: KPT-02 owns fiber behavior, KPT-03 construction, KPT-04 substrate readiness, KPT-05 installation, KPT-12 measured performance, KPT-13 health/hygiene, and KPT-15 defects.

## First publication wave

Publish a coherent 12-asset decision path: `KPT-01-01`, `KPT-01-02`, `KPT-02-01`, `KPT-03-01`, `KPT-04-01`, `KPT-04-02`, `KPT-05-01`, `KPT-05-02`, `KPT-12-01`, `KPT-13-01`, `KPT-14-01`, and `KPT-16-01`. Together they move a buyer from system fit and material selection through substrate checks, installation, evidence review, cleaning, and quantity calculation before a quotation is requested.
