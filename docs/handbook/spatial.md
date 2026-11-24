# Spatial Clearances and Ergonomics

> Sources: Neufert *Architects' Data* (current ed., publisher Wiley-Blackwell), *Time-Saver Standards for Interior Design and Space Planning* (Reznikoff / De Chiara, McGraw-Hill), *Human Dimension & Interior Space* (Panero & Zelnik, Whitney Library of Design 1979), Henry Dreyfuss Associates *The Measure of Man and Woman*, Edward T. Hall *The Hidden Dimension* (Doubleday 1966), GB 50096-2011 *Design Code for Residential Buildings*, Permen PUPR 14/PRT/M/2017 (Persyaratan Kemudahan Bangunan Gedung), NKBA Kitchen & Bath Planning Guidelines.
>
> Last updated: 2026-04-29

## Purpose

This chapter is the validation layer for furniture placement. Before a render is accepted, every piece of furniture in the scene must pass against the clearances below. The numbers come from authoritative public sources; where a specific page or figure number could not be verified inside time, the entry is flagged "exact figure number not verified" and points at the corroborating summary URL — the rule still holds, but the locator does not.

The audience is twofold: an automated checker that flags placement violations (e.g. sofa too close to the coffee table), and a non-designer user who wants to know *why* the rule exists.

## Furniture clearances

### Living spaces

- **Sofa-to-coffee-table:** 400-460 mm (per Panero & Zelnik 1979, "Living Spaces" chapter — exact figure number not verified, cf. summary at https://www.panero.us/human-dimension; corroborated by Hall's personal-distance close phase 460-760 mm at https://en.wikipedia.org/wiki/Proxemics). Below 400 mm a seated occupant cannot extend their legs; above 460 mm they cannot reach a cup without leaning forward off the seat back.
- **Sofa-to-TV (focal point):** minimum 1.8 m for typical 55" displays; see "Sight-line and viewing rules" below for the diagonal-multiplier formula.
- **Conversation circle radius:** 1.2-2.1 m between facing seats (per Hall 1966, *The Hidden Dimension*, "social distance close phase" via https://en.wikipedia.org/wiki/Proxemics). This is the upper bound of personal distance and the floor of social distance — the band where casual conversation between non-intimates feels natural.
- **Side-table-to-armchair:** 100-150 mm gap so a seated occupant can set a glass down without rotating their torso (per Panero & Zelnik 1979 — exact figure number not verified, cf. https://en.wikipedia.org/wiki/Proxemics for the underlying personal-distance basis).

### Dining

- **Chair pull-back from edge of table:** 760-915 mm total (per Architectural Graphic Standards / Time-Saver Standards for Interior Design — exact section number not verified, cf. https://en.wikipedia.org/wiki/Kitchen_work_triangle for related ergonomic norms). This is the diner's seated knee-to-back-of-chair envelope; below it the diner cannot fully sit, above it the chair drifts away from the table.
- **Server-circulation behind a pulled-out chair:** add 300-450 mm beyond the 760-915 mm pull-back zone for a person to walk behind a seated diner (per Panero & Zelnik 1979 — exact figure number not verified, cf. social-distance close phase 1.2 m at https://en.wikipedia.org/wiki/Proxemics).
- **Place setting width per diner:** 600 mm minimum at the table edge (per Neufert *Architects' Data* "Dining" chapter — exact section number not verified, cf. https://en.wikipedia.org/wiki/Ernst_Neufert).

### Kitchen

- **Single-cook work aisle:** minimum 1100 mm / 42 in (per NKBA Kitchen Planning Guidelines, summarised at https://en.wikipedia.org/wiki/Kitchen_work_triangle).
- **Two-cook work aisle:** minimum 1200 mm / 48 in (per NKBA, same summary).
- **Work-triangle leg length:** 1.2-2.7 m per leg, total perimeter 4-8 m (per NKBA via https://en.wikipedia.org/wiki/Kitchen_work_triangle, originally researched at the University of Illinois 1940s).
- **Refrigerator handle-side clearance:** 380 mm / 15 in minimum (per NKBA via https://en.wikipedia.org/wiki/Kitchen_work_triangle).
- **Cooktop side clearances:** 380 mm one side, 305 mm / 12 in other (per NKBA via https://en.wikipedia.org/wiki/Kitchen_work_triangle).
- **Sink side clearances:** 600 mm / 24 in landing zone one side, 450 mm / 18 in other (per NKBA via https://en.wikipedia.org/wiki/Kitchen_work_triangle).

### Bedroom

- **Bed-to-wall at sides:** 600-900 mm to allow making the bed and walking past (per Neufert *Architects' Data* "Bedrooms" chapter — exact section number not verified, cf. https://en.wikipedia.org/wiki/Ernst_Neufert; the lower bound is the body-pass-by minimum, the upper enables making the bed without crawling on it).
- **Bed-to-wall at foot:** 900 mm minimum if the foot wall holds a dresser, 600 mm if not (per Panero & Zelnik 1979 "Bedrooms" — exact figure number not verified, cf. https://en.wikipedia.org/wiki/Proxemics personal-distance bands).
- **Headboard wall:** 0 mm (the bed sits against it); allow 50 mm if the headboard is upholstered and shoulder-rub against paint is a concern.
- **Closet door swing or drawer-pull zone:** 900 mm clear in front of the wardrobe face (per Neufert — exact section not verified, cf. https://en.wikipedia.org/wiki/Ernst_Neufert).

### Bathroom

- **Accessible toilet compartment:** 1525 × 2275 mm minimum (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.8), with 1525 mm clear between the door and the front of the water closet (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.11) — see `codes.md`.
- **General toilet compartment:** 800 × 1550 mm minimum (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.7).
- **Wash basin height:** 750 mm for wheelchair users, 850 mm for adults (per Permen PUPR 14/PRT/M/2017 Lampiran III 6.3–6.4).
- **Toilet centerline from side wall and seat height:** not specified numerically in Permen PUPR 14/PRT/M/2017 Lampiran III; take them from the fixture manufacturer's accessible-WC data and the in-force SNI or hospital standard (perlu verifikasi) rather than a foreign code.

## Circulation widths

| Path type | Width (mm) | Source |
|---|---|---|
| Primary residential corridor | 920 minimum (one wheelchair user) | per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a |
| Secondary / single-person path | 760-900 | per Panero & Zelnik 1979 body-pass-by — exact figure number not verified, cf. https://en.wikipedia.org/wiki/Proxemics |
| Two-person passing | 1200 | per NKBA two-cook aisle (https://en.wikipedia.org/wiki/Kitchen_work_triangle), used as residential analog |
| Accessibility-grade route | 920 minimum (one wheelchair), 1520 wheelchair + pedestrian, 1840 two wheelchairs | per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a; see `codes.md` |
| Wheelchair manoeuvring space at a door | 1525 × 1525 inside, 1700 × 1700 outside | per Permen PUPR 14/PRT/M/2017 Lampiran II A.1.a.6–7 |

## Eye-level conventions

| Posture | Eye height (mm) | Source |
|---|---|---|
| Standing adult (50th-percentile mixed) | 1550-1650 | per Henry Dreyfuss Associates *The Measure of Man and Woman* — exact chart not verified, cf. https://en.wikipedia.org/wiki/Henry_Dreyfuss; corroborated by Panero & Zelnik 1979 anthropometric charts |
| Seated adult (on dining/desk chair, 450 mm seat) | 1150-1250 | per Panero & Zelnik 1979 — exact figure number not verified, cf. https://en.wikipedia.org/wiki/Henry_Dreyfuss |
| Seated adult (on lounge sofa, 380 mm seat) | 1050-1150 | per Panero & Zelnik 1979 — exact figure number not verified, cf. https://en.wikipedia.org/wiki/Henry_Dreyfuss |
| Child (8-year-old, standing) | 1150-1250 | per Dreyfuss "Joe & Josephine" anthropometric charts — exact chart not verified, cf. https://en.wikipedia.org/wiki/Henry_Dreyfuss |

**Camera-height implication:** for hero renders that read as "human-occupied space," set the camera between 1450-1600 mm — slightly below standing eye level so the room feels tall, never above 1700 mm (which reads as a real-estate listing, not editorial). For dining-room hero shots, drop to 1100-1200 mm to match a seated occupant. See `camera.md` for the full lens/height matrix.

## Sight-line and viewing rules

- **TV viewing distance — minimum (immersive/THX):** 1.2 × screen diagonal, equivalent to a 40° horizontal viewing angle (per THX recommendation, https://en.wikipedia.org/wiki/Optimum_HDTV_viewing_distance).
- **TV viewing distance — recommended (SMPTE):** 1.6 × diagonal, equivalent to a 30° viewing angle (per SMPTE EG-18, summarised at https://en.wikipedia.org/wiki/Optimum_HDTV_viewing_distance).
- **TV viewing distance — relaxed (manufacturer/retailer):** 1.6-2.5 × diagonal (per RCA/Toshiba/Best Buy/Crutchfield via https://en.wikipedia.org/wiki/Optimum_HDTV_viewing_distance). For a 55" / 1397 mm diagonal, this is 2235-3492 mm sofa-to-screen.
- **Focal-point distance from primary seating:** 2.4-3.7 m for fireplaces, art walls, or similar (per Hall 1966 *The Hidden Dimension* "social distance far phase," via https://en.wikipedia.org/wiki/Proxemics). Below this the focal point overwhelms the seat; above it, it loses presence.

## Furniture grouping (proxemics)

Hall's 1966 framework gives the load-bearing numbers for any seating arrangement (per https://en.wikipedia.org/wiki/Proxemics):

- **Intimate distance** (touching to 460 mm): for couples and family — applies to bench seating, loveseats.
- **Personal distance** (460-1220 mm): for friends — applies to corner-of-an-L-sofa configuration.
- **Social distance close phase** (1.2-2.1 m): for acquaintances — the canonical "conversation circle" radius for living-room sofa-and-armchair groupings.
- **Social distance far phase** (2.1-3.7 m): for formal interaction or focal-point distance.
- **Public distance** (3.7 m+): too far for casual residential conversation; relevant only for lecture/cafe-seated-audience layouts.

**Furniture cluster radius:** group seats inside a 2.4 m diameter circle whenever the activity is conversation-led; expand to 3.0 m when a coffee table sits in the center (per Hall social-distance far phase, https://en.wikipedia.org/wiki/Proxemics; corroborated by Panero & Zelnik 1979 "Conversation Areas" — exact figure number not verified).

## Worked examples

**Example 1 — Lounge cluster, 2× three-seat sofa facing arrangement:**

- Sofa-to-sofa face distance: 1.8 m (mid-band of Hall social-distance close phase per https://en.wikipedia.org/wiki/Proxemics).
- Coffee table between: 900 × 500 mm, centered, leaving 450 mm sofa-to-table on each side (within the 400-460 mm Panero band — exact figure not verified, cf. https://en.wikipedia.org/wiki/Proxemics).
- Behind each sofa: 760 mm passing aisle (per Panero body-pass-by — exact figure not verified, cf. https://en.wikipedia.org/wiki/Hallway 910 mm primary corridor).

**Example 2 — bar with stools:**

- Stool-to-stool centerline: 600-700 mm so adjacent shoulders don't touch (per Hall personal distance close phase 460-760 mm via https://en.wikipedia.org/wiki/Proxemics).
- Bartender side aisle: 1100 mm minimum (per NKBA single-cook aisle via https://en.wikipedia.org/wiki/Kitchen_work_triangle).
- Customer-side circulation behind stools: 1200 mm so a seated customer plus one passing person fit (per NKBA two-cook aisle https://en.wikipedia.org/wiki/Kitchen_work_triangle).

## Common mistakes

- **Coffee table jammed against the sofa.** Below 400 mm there is no leg room (per Panero — exact figure not verified, cf. https://en.wikipedia.org/wiki/Proxemics).
- **Bed shoved into a corner with one side flush to the wall.** Acceptable for a child's room, hostile for an adult — making the bed requires the 600 mm side clearance (per Neufert — exact section not verified, cf. https://en.wikipedia.org/wiki/Ernst_Neufert).
- **Camera at 1.8 m or higher for editorial shots.** Reads as a real-estate listing. Drop to 1.45-1.6 m for human-occupied feel (per Dreyfuss anthropometric standing eye height 1550-1650 mm via https://en.wikipedia.org/wiki/Henry_Dreyfuss).
- **TV at 3 m for a 32" / 813 mm display.** That is 3.7× diagonal — beyond every standard's upper bound (per https://en.wikipedia.org/wiki/Optimum_HDTV_viewing_distance which caps "relaxed" at 2.5×).
- **Dining table 600 mm from a wall on the seating side.** A pulled-out chair plus diner needs 760-915 mm minimum (per Time-Saver Standards — exact section not verified).
- **Two-cook kitchen with 1100 mm aisle.** Single-cook minimum; for two cooks step up to 1200 mm (per NKBA via https://en.wikipedia.org/wiki/Kitchen_work_triangle).

## See also

- `codes.md` — Indonesian regulatory minimums (Permen PUPR 14/PRT/M/2017 accessibility, Permen PU 26/PRT/M/2008 egress), which often set the floor below which the values here cannot drop.
- `furniture.md` — standard furniture footprints that drive these clearances.
- `camera.md` — render-camera height and lens choice; the eye-level table above ties directly into camera placement.
- `lighting.md` — fixture mounting heights also reference eye level.
