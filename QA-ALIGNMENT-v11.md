# QA Alignment Report — v11.0

Overall verdict: **PASS**

## A. Presentation

- PASS — 116 slides; 16:9; version v11.0 appears once on the cover and matches the filename.
- PASS — general trainer template and Dr Alfred Ang profile are separate visual slides.
- PASS — visual LMS download guidance and WA-to-PP assessment-flow diagrams are present.
- PASS — concepts and worked examples are visual; click-by-click procedures are excluded from the deck.
- PASS — independent contact-sheet review found no blank, clipped, overlapping or off-slide content.
- PASS — post-review fixes corrected the one-hour lunch, enlarged process text and clarified the editable-production swimlane.
- N/A — a practice-exam slide is omitted because this is not a certification course.

## B. Assessment

- PASS — four DOCX deliverables: WA-SAQ, WA answer key, PP paper and PP answer key.
- PASS — WA contains nine open-ended questions covering K1–K9.
- PASS — PP preserves the approved three-task instrument and covers A1–A4.
- PASS — page 1 cover; page 2 candidate information, full instructions, LMS link and grading; content from page 3.
- PASS — candidate and answer-key codes match; answer keys contain no candidate-information block.
- PASS — 30-minute WA plus 30-minute PP matches the supplied approved assessment plan.

## C. Lesson Plan

- PASS — WSQ cover, version record, release-ready contents page and Page X of Y footer.
- PASS — 9:00am–6:00pm schedule, one-hour lunch excluded, 480 counted minutes including assessment.
- PASS — final slide references are generated from `slide_map.json` and match the 116-slide deck.

## D. Learner Guide

- PASS — WSQ cover, version record, release-ready contents page and Page X of Y footer.
- PASS — detailed click-by-click procedures, timing, acceptance criteria, discussion and debrief for all eight activities.
- PASS — DOCX and PDF only, in accordance with the current Learner Guide skill.

## E. Activities and workbooks

- PASS — canonical `activities/` folder; no learner-facing `labs/` folder.
- PASS — eight individual, self-contained folders.
- PASS — each folder contains instructions, checklist, synthetic CSV, formula-enabled XLSX, editable start PPTX and editable sample PPTX.
- PASS — LibreOffice recalculation found zero formula errors in all eight workbooks.

## F. Distribution boundary

- PASS — public GitHub scope excludes `.env`, `assessment/`, `reference/`, build tooling, source assets and QA renders.
- PASS — learner-visible LMS fields are limited to current courseware, the Activities folder and the two candidate assessment papers.
- PASS — answer keys are Drive-only in a separate private trainer folder; anonymous checks on both current and remediated legacy IDs return access pages rather than document bytes.
