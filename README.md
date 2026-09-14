# Four Centres v1.1 Release Report

Status: `published`

This directory is the protected Stable Pencil v1.1 release. The source and outputs of v1.0 remain unchanged under `../final_v1_0/`; the pre-review archive remains under `../archives/pre_150_review_20260811/`.

## Release scope

- 244 student-facing questions: 137 MCQ and 107 Structured Long / Integrated.
- 60 teaching clusters and 200 displayed exact similarity groups.
- 253 permanent coordinate IDs are retained in the audit data layer.
- Seven exact duplicates are mapping-only: Q100 -> Q246, Q102 -> Q047, Q118 -> Q247, Q139 -> Q114, Q178 -> Q106, Q184 -> Q174, Q210 -> Q052.
- Q223 and Q258 remain permanent IDs with `deferred_from_v1_1` status and are excluded from the student-facing v1.1 volumes.

## Published files

- Master: `four_centres_v1_1_master.html`, `four_centres_v1_1_master.print.html`, `four_centres_v1_1_master.pdf` (874 pages).
- MCQ + Short: `four_centres_v1_1_mcq.html`, `four_centres_v1_1_mcq.print.html`, `four_centres_v1_1_mcq.pdf` (479 pages).
- Long + Integrated: `four_centres_v1_1_long.html`, `four_centres_v1_1_long.print.html`, `four_centres_v1_1_long.pdf` (402 pages).
- Each volume has a matching `*_page_map.json` containing the final global question start pages.

## Indexes

All indexes use global PDF pages only. Master has 41 index pages: Contents 1-3, Skills 4-20, Centre 21-28 and Sources 29-41. MCQ + Short has 23 index pages: Contents 1-2, Skills 3-10, Centre 11-15 and Sources 16-23. Long + Integrated has 23 index pages: Contents 1-2, Skills 3-11, Centre 12-17 and Sources 18-23.

## Diagram provenance

Exact reviewed crops are used for Q238, Q240, Q242, Q243, Q251, Q252, Q253, Q254 and Q255. Q250 and Q261 use reconstructed diagrams derived from their verified question statements and are marked reconstructed in the source data. The superseded invalid Q243 PNG is quarantined in `work_150_v1_1/checkpoints/pre_publish_rebuild_20260818/quarantined_invalid_assets/`; it is not referenced by the release.

## QA result

- Source gate: 150/150 passed.
- Bilingual parity: 150/150 passed; no open parity issues.
- Independent review/classification: all 142 release-ready active review records passed; Q223 and Q258 are mathematically recomputed but deferred because official source-answer evidence is unavailable; six exact duplicates are mapping-only. Classification audit issues: 0.
- Classification invariants: same complete techniques remain together; official/public questions precede mocks within exact groups; display order is independent of permanent Q ID.
- HTML browser and print QA: passed for all three volumes; KaTeX/font, missing-image, overflow, clipping and residue checks passed.
- PDF QA: all pages A4, no blank pages, no residue, and global page footer matches the actual page count.
- Final page-map verification: all 488 question-page entries matched the rendered PDFs with zero mismatches.
- Diagram QA: all 11 required diagram records passed source/semantic/visual checks; user-flagged and newly repaired diagram pages were inspected.
- Immutable v1.0 baseline: 410/410 checksums passed.

The release standard and schedule records this checkpoint append-only in `work_150_v1_1/FOUR_CENTRES_NOTE_STANDARD_AND_SCHEDULE.md`.
