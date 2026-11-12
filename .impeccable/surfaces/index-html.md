---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface

## Scope and visitor mode

Redesign the existing web page and its analysis-to-PDF flow. Mode: Operate.

## Audience and task

Hypothesis to confirm: a job candidate preparing a resume for a specific vacancy. They provide a PDF and vacancy text or screenshots, review source-backed matches and suggestions, then decide whether to preview and download a PDF.

## Content, proof, and constraints

The proof is the exact vacancy quote paired with literal resume evidence. Screenshot transcription must be confirmed. Suggestions remain optional, unsupported skills must not be added, and the user must inspect the PDF preview. Preserve the existing local processing and API contract. Do not invent outcomes, scores, or candidate claims.

## Direction contract

THESIS: Follow one legible evidence route from source material to a user-approved PDF, refusing a dashboard of disconnected cards.

OWN-WORLD: Extend the existing navy, white, and indigo palette with its DM Sans reading voice and Manrope headings. A restrained course line and numbered checkpoints organize the work; the page is not a literal map and gains no decorative topography.

STORY: Begin with the candidate's existing resume and the vacancy, confirm screenshot text when needed, compare exact quotes with resume evidence, then let the candidate decide which suggestions to preview. The memorable moment is seeing a vacancy requirement connected to its source-backed resume evidence and an explicit next action, without invented match scores.

FIRST VIEWPORT: At desktop width, place the concise purpose and three-step evidence route beside the resume/vacancy form. Keep the primary analysis action at the form's end, after its required materials; on narrow screens, stack the route before the form and keep labels and actions full width.

FORM: Evidence route with a numbered legend, the fifth structure in the resonance ordering and the assigned lead of the surface roll; seed:47b5d8c8d1191063.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Unresolved decisions

The primary audience and its prioritized workflow pain remain unconfirmed. Keep the existing backend behavior and API responses unchanged unless implementation evidence requires a directly coupled fix.
