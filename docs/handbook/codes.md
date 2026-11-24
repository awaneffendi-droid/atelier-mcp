# Building Codes for Interior Design (Indonesia)

> Sources: Permen PUPR 14/PRT/M/2017 tentang Persyaratan Kemudahan Bangunan Gedung (Lampiran II and III), Permen PU 26/PRT/M/2008 tentang Persyaratan Teknis Sistem Proteksi Kebakaran pada Bangunan Gedung dan Lingkungan (sarana penyelamatan jiwa chapter, as reproduced in the ITB *Manual Sarana Penyelamatan Jiwa pada Bangunan*), SNI 03-1746-2000, Permenkes 6/2026 tentang Rumah Sakit
> Last updated: 2026-11-24

## Purpose

This chapter is the regulatory backbone for the Interior Design Workflow MCP on Indonesian projects. It collects the minimum accessibility and fire-egress rules an interior designer cannot legally violate, with one inline citation per number so a downstream skill (`validate_dimensions`, `validate_accessibility`, `validate_egress`) can quote the source. Numbers below are floors, not targets — `spatial.md` covers comfort-driven clearances above the code minimum.

## Scope and applicability

- **Accessibility** (kemudahan) is governed nationally by Permen PUPR 14/PRT/M/2017. Lampiran II covers horizontal and vertical circulation (doors, selasar, corridors, ramps, stairs, lifts); Lampiran III covers facilities (toilets, wash basins, changing rooms, beds). Values below were read from the published Lampiran II and III text.
- **Fire egress** (sarana penyelamatan jiwa) is governed by Permen PU 26/PRT/M/2008 together with SNI 03-1746-2000. Values below come from the egress chapter as reproduced (with the Permen header) in the ITB manual; **verify each against the official Permen text and check whether a newer PU regulation or SNI edition has superseded it before using it in a submission (perlu verifikasi)**.
- **Hospitals** (rumah sakit): Permenkes 6/2026 tentang Rumah Sakit requires every hospital to provide isolation care (per Permenkes 6/2026 Pasal 15 ayat 6) and requires hospital sarana/prasarana to meet the technical requirements in the applicable regulations (per Permenkes 6/2026 Pasal 9 ayat 1). Permenkes 40/2022 (the former hospital building technical regulation) is listed among the regulations Permenkes 6/2026 revokes — confirm which hospital technical standard applies before validating clinical room sizes.
- Kabupaten/kota bangunan gedung perda and the PBG review can add stricter local requirements. Indonesian rules govern; foreign codes are not binding on an Indonesian site; Chinese GB values appear only in the comparison appendix and US codes are not used.
- National minimum room sizes for dwellings are not set in these regulations; for residential space sizing use `spatial.md` (Neufert-based comfort values) and any local rule.

## Rules

### Doors and openings

- Main entrance/exit door of a public building: effective clear opening **≥90 cm**; other doors **≥80 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II A.1.a.1).
- Clear manoeuvring space in front of a swing door: **≥152.5 cm × 152.5 cm** on the inside, **≥170 cm × 170 cm** on the outside (per Permen PUPR 14/PRT/M/2017 Lampiran II A.1.a.6–7).
- Door handle height: **≤110 cm** above finished floor (per Permen PUPR 14/PRT/M/2017 Lampiran II A.1.a.17).
- Toilet door clear width: **≥70 cm**, and **≥90 cm** for an accessible toilet (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.10).
- Egress doors and means of egress: clear width **≥915 mm** for new exits, **≥710 mm** for existing ones (per Permen PU 26/PRT/M/2008 egress chapter, ITB manual Bagian II 2.4(d); perlu verifikasi).

### Corridors, selasar and circulation widths

- Selasar (covered walkway) effective width for a wheelchair user or two people passing: **≥140 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II A.2.a.1).
- Corridor width for one wheelchair user: **≥92 cm**; two wheelchair users passing: **≥184 cm**; one wheelchair user plus one pedestrian: **≥152 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a).
- Corridor with railing: one wheelchair user **≥112 cm**; two passing **≥204 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a).
- Health facilities (puskesmas, rumah sakit) must provide a railing on at least one side of selasar and corridors (per Permen PUPR 14/PRT/M/2017 Lampiran II A.2.a.7 and A.3.a.14). Hospital corridor widths themselves are deferred to the sector regulation (per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a.15) — do not invent a bed/stretcher corridor width.

### Ramps, stairs and lifts

- Ramp slope: indoor **≤1:10** (6°), outdoor **≤1:12** (5°) (per Permen PUPR 14/PRT/M/2017 Lampiran II B.2.a.1).
- Ramp clear width: **≥95 cm** without edge protection, **≥120 cm** with a low curb (per Permen PUPR 14/PRT/M/2017 Lampiran II B.2.a.2).
- Ramp landing length: **≥120 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II B.2.a.4); a landing is required for every **900 cm** of ramp run (per Permen PUPR 14/PRT/M/2017 Lampiran II B.2.a.6).
- Ramp handrails: two continuous rails on both sides at **65 cm** (children) and **80 cm** (adults) (per Permen PUPR 14/PRT/M/2017 Lampiran II B.2.a.7).
- Stairs: riser **15–18 cm**, tread **≥30 cm**, handrail **65–80 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II B.1.a.4, B.1.a.5, B.1.a.11).
- Passenger lift car: **≥120 cm × 230 cm** with door opening **≥110 cm**; high-use public facilities **≥152.5 cm × 240 cm** with door **≥152.5 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran II B.3.a.4). Lift lobby depth **≥185 cm**; control panel **≤90 cm** high (per Permen PUPR 14/PRT/M/2017 Lampiran II B.3.a.3.b and B.3.a.5.a).
- Health buildings must provide passenger/patient lifts and accessible lifts (per Permen PUPR 14/PRT/M/2017 Pasal 20 ayat 2 huruf e).

### Toilets and fixtures

- Accessible toilet compartment: **≥152.5 cm × 227.5 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.8); clear space **≥152.5 cm** between the door and the front of the water closet (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.11).
- General toilet compartment: **≥80 cm × 155 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.7).
- Each men's and women's toilet group needs at least one accessible toilet and one child toilet (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.5); accessible toilets need grab rails (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.17 — rail height is not stated there; perlu verifikasi).
- Wash basin height: **75 cm** for wheelchair users, **85 cm** for adults (per Permen PUPR 14/PRT/M/2017 Lampiran III 6.3–6.4).
- Bed clearance: **≥110 cm** between bed and wall for circulation and wheelchair manoeuvring; bed height **≤50 cm** (per Permen PUPR 14/PRT/M/2017 Lampiran III 12.8–12.9).

### Fire egress

All values in this section: per Permen PU 26/PRT/M/2008 egress chapter as reproduced in the ITB manual; perlu verifikasi against the official text.

- Occupant load (beban hunian) = floor area ÷ factor. Factors in m² per person include: health care inpatient treatment areas **22.3**, inpatient sleeping areas **11.1**, outpatient **9.3**; business **9.3**; assembly without fixed seats, concentrated **0.65 net**, less concentrated **1.4**; kitchen **9.3**; classrooms **1.9 net**; retail sales on the street floor **2.8**, on two or more street floors **3.7**, on floors above the street floor **5.6**; hotels and apartments **18.6** (per Permen PU 26/PRT/M/2008 Tabel faktor beban hunian, ITB manual Bagian II 2.3).
- Minimum number of exits: **2** (per Permen PU 26/PRT/M/2008, ITB manual Bagian II 2.6).
- Corridors serving more than **30 occupants** need a 1-hour fire-rated separation (per Permen PU 26/PRT/M/2008, ITB manual Bagian II 2.1(a)).
- New health-care occupancy: dead-end corridor **≤9.1 m**; travel distance **≤61 m** with sprinklers (not applicable without sprinklers, i.e. sprinklers are expected); existing health care: travel distance **≤45 m** unsprinklered, **≤61 m** sprinklered (per Permen PU 26/PRT/M/2008 Tabel batas jarak tempuh, ITB manual p. II-18).
- Ambulatory health care (new): common path **≤23 m** unsprinklered / **≤30 m** sprinklered; dead end **≤6.1 m** / **≤15 m**; travel distance **≤45 m** / **≤61 m** (per Permen PU 26/PRT/M/2008 Tabel batas jarak tempuh, ITB manual p. II-18).

## Worked examples

**Example 1 — Accessible toilet in an outpatient wing.**
Compartment 160 cm × 230 cm ≥ 152.5 × 227.5 cm (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.8). Door clear opening 90 cm meets the accessible-toilet minimum (per Permen PUPR 14/PRT/M/2017 Lampiran III 5.10). Pass, subject to grab rails and wash basin at 75 cm.

**Example 2 — Occupant load of a 220 m² inpatient ward floor.**
220 m² ÷ 11.1 m²/person ≈ 19.8 → **20 occupants** (per Permen PU 26/PRT/M/2008 Tabel faktor beban hunian, rawat inap row; perlu verifikasi). Provide at least 2 exits (per Permen PU 26/PRT/M/2008), keep dead ends ≤9.1 m and travel distance ≤61 m with sprinklers.

**Example 3 — Corridor in a clinic.**
A 150 cm corridor passes one wheelchair user plus one pedestrian only if it reaches 152 cm (per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a) — widen it, and add the railing required for health facilities (per Permen PUPR 14/PRT/M/2017 Lampiran II A.3.a.14).

## Common mistakes

- **Applying a foreign code on an Indonesian site.** ADA, IBC and GB values look similar but differ (for example the Permen PU 26/2008 business factor is 9.3 m²/person, not the IBC 13.9). Cite the Indonesian rule.
- **Using the 80 cm door minimum at the main entrance.** Main entrances need 90 cm (per Permen PUPR 14/PRT/M/2017 Lampiran II A.1.a.1).
- **Inventing a hospital corridor width.** Permen PUPR 14/2017 defers it to sector regulation; find the in-force hospital technical standard first.
- **Citing Permenkes 24/2016 or 40/2022 as current.** Check the status against Permenkes 6/2026 first.

## Appendix: Chinese GB reference values (comparison only)

The values below come from the upstream Chinese edition of this handbook (GB 50096-2011, GB 50352-2019, GB 50763-2012, GB 50016-2014). They are **not binding on an Indonesian site** and are kept only because several space-type chapters compare against them (residential room minimums, kitchen aisles, bathroom stacking). When an Indonesian rule above covers the same point, the Indonesian rule governs.


#### Minimum room dimensions (residential)

- Living-room (起居室/厅) usable area minimum: **10 m²** (per GB 50096-2011 §5.2.2; soujianzhu.cn / jianbiaoku.com publication of the standard).
- Double bedroom (双人卧室) usable area minimum: **9 m²** (per GB 50096-2011 §5.2.1 item 1).
- Single bedroom (单人卧室) usable area minimum: **5 m²** (per GB 50096-2011 §5.2.1 item 2).
- Bedroom that doubles as living space (兼起居的卧室) minimum: **12 m²** (per GB 50096-2011 §5.2.1 item 3).
- Kitchen (厨房) usable area minimum: **4.0 m²** in a full bedroom + living + kitchen + bath unit; **3.5 m²** in the smallest combined unit (per GB 50096-2011 §5.3.1).
- Kitchen single-row equipment clear width: **≥1.50 m**; double-row clear distance between rows: **≥0.90 m** (per GB 50096-2011 §5.3.5).
- Bathroom (卫生间) with three fixtures (toilet + bathing + washbasin) usable area minimum: **2.50 m²** (per GB 50096-2011 §5.4.1).
- Bathroom with toilet + washbasin only: **≥1.80 m²**; toilet + bath: **≥2.00 m²**; toilet only: **≥1.10 m²** (per GB 50096-2011 §5.4.2).
- Bedroom / living-room interior net height: **≥2.40 m** (local low areas ≥2.10 m, low area ≤1/3 of usable area) (per GB 50096-2011 §5.5.2).
- Kitchen / bathroom interior net height: **≥2.20 m** (per GB 50096-2011 §5.5.4).
- Whole-unit usable area: **≥30 m²** (full layout) or **≥22 m²** (smallest combined-bedroom layout) (per GB 50096-2011 §5.1.2).

Note: §5.4.4 (bathroom may not sit directly above bedroom/living/kitchen of the unit below) is one of the **mandatory (强制性) provisions** of GB 50096-2011 — others on this list are recommended.

#### Corridor / circulation widths

- Civil-building corridor minimum net height (where people normally pass): **≥2.0 m** (per GB 50352-2019 §6.3.3).
- Building connector (with traffic function) net width: **≥3.0 m** above ground, **≥4.0 m** underground, **≤9.0 m** maximum (per GB 50352-2019 §4.4.4).
- Note: GB 50352-2019 is a **unified general standard** and defers specific corridor widths per building type to the specialized standard (residential → GB 50096; commercial → GB 50016 egress widths). Do not cite GB 50352 for a specific residential corridor width — it does not publish one.
- Wheelchair-accessible indoor corridor: **≥1.20 m** (large public buildings with high pedestrian flow: ≥1.80 m) (per GB 50763-2012 §3.5.1 item 1).
- Wheelchair-accessible outdoor passage: **≥1.50 m** (per GB 50763-2012 §3.5.1 item 2).
- Wheelchair lane at ticket / checkout: **≥900 mm** (per GB 50763-2012 §3.5.1 item 3).

#### Doors and openings

- GB 50352-2019 entry-vestibule rule: when both interior+exterior doors are open, the gap between them shall be **≥0.8 m**; if accessibility applies, defer to GB 50763 (per GB 50352-2019 §6.11 item 8).
- Accessible automatic door clear passing width: **≥1.00 m** (per GB 50763-2012 §3.5.3 item 2).
- Accessible swing / sliding / folding door clear passing width: **≥800 mm** (preferred ≥900 mm where conditions permit) (per GB 50763-2012 §3.5.3 item 3).
- Accessible door must have a **≥400 mm clear wall** on the latch side (per GB 50763-2012 §3.5.3 item 5).
- Accessible threshold / level change: **≤15 mm** (per GB 50763-2012 §3.5.3 item 7).

#### Fire egress

- Public-building room evacuation door to nearest safety exit, located **between two safety exits**, single/multi-story Class I/II fire resistance — generic "other" public buildings: **40 m maximum**; located on a dead-end (袋形走道) corridor: **22 m maximum** (per GB 50016-2014 §5.5.17 Table 5.5.17, "其他建筑" row, single/multi-story 一、二级耐火等级 columns; tpy119.com / jianbiaoku.com mirrors of the standard).
- Public-building hotel-specific values: high-rise hotel **30 m** between exits / **15 m** dead-end; single/multi-story hotel **40 m / 22 m** (Class I/II); the 25 % sprinklered uplift below applies (per GB 50016-2014 Table 5.5.17, hotel row).
- Sprinkler uplift: when the entire building has automatic sprinklers, the §5.5.17 distances increase by **25 %** (per GB 50016-2014 §5.5.17 Note 3; this is a strong-provision (mandatory) note).
- Open-air external corridor uplift: rooms opening onto an open exterior corridor add **+5 m** to the table value (per GB 50016-2014 §5.5.17 Note 1).
- Travel within room → room evacuation door: shall not exceed the dead-end-corridor value in Table 5.5.17 (per GB 50016-2014 §5.5.17 item 3).
- Large-room special rule (Class I/II fire resistance, ≥2 exits, theater / exhibition / restaurant / sales hall): any-point-to-nearest-exit straight-line distance **≤30 m**; sprinklered → +25 % (per GB 50016-2014 §5.5.17 item 4).
- Residential travel distance, high-rise (一、二级耐火等级 高层) — unit door to nearest safety exit, between two exits: **40 m max**; on a dead-end corridor: **20 m max** (per GB 50016-2014 §5.5.29 Table 5.5.29, high-rise row; full-building sprinklered → 50 m / 25 m via the §5.5.29 Note 3 25 % uplift).
- Residential single/multi-story (一、二级耐火等级): **40 m / 22 m** between exits / dead-end (per GB 50016-2014 Table 5.5.29).
- Residential straight-flight stair (跃层式) inside a duplex unit: stair distance counted as **1.5× horizontal projected length** (per GB 50016-2014 §5.5.29 Note, mirrored in §5.5.17 commentary).
- §5.5.29 is a **mandatory (强制性) provision** of GB 50016-2014 — the table values cannot be exceeded under any planning argument; only the documented Notes (sprinklers, exterior corridor) raise them.
- Number of safety exits: a single safety exit is allowed for a small room only when (a) area <50 m² with evacuation door net width ≥0.90 m, or (b) any-point-to-evacuation-door distance ≤15 m, area ≤200 m², and door net width ≥1.40 m; otherwise ≥2 exits (per GB 50016-2014 §5.5.15 — mandatory).


## See also

- `spatial.md` — non-code clearances that sit **above** the code minimum
- `lighting.md` — illuminance guidance
- `furniture.md` — door swing zones and furniture-clear zones at door arcs
- `space-types/` — per-space-type chapters reference these sections when validating dimensions
