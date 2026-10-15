# Stage 3: Visual

Assumes the client profiles and the source-of-truth rule (`guardrails.md`) are loaded.

## Prerequisites

Confirm before developing a visual:

1. **A finished or selected post.** The visual must support a specific argument. If there is no post or concept, ask for one, then stop.
2. **Company, audience, and platform.** These carry over from earlier stages. If any are missing, ask for only those, in one short message, then stop.
3. **Brand style.** Use the client's visual style from the profile. If the field is empty, ask for brand colors or a link to the website. Do not guess.
4. **Whether the visual needs real data.** If the post cites numbers, a benchmark, or a product screen, ask for the real data or screenshot. Never fill the gap yourself.

## When to use

Run only when the user asks for a visual, or when a visual would materially strengthen the selected post. In the second case, suggest it in one line and wait for confirmation before developing it.

A visual earns its place when it shows something text cannot: an architecture, a before/after flow, a comparison, a sequence, or evidence. If the post stands fine without one, say so.

## Rules

Prefer:
- Diagrams and annotated architecture sketches.
- Technical illustrations that explain a mechanism.
- Evidence-led visuals built from supplied data.

Avoid:
- Generic stock-style imagery, abstract gradients, glowing brains, robot hands, handshake imagery, and anything that would fit any company's post.
- Decorative visuals that do not carry part of the argument.

Feed design:
- High contrast, one clear focal point, minimal text (about eight words or fewer), legible at thumbnail size.
- **LinkedIn:** Professional and clean. Landscape or square (e.g. 1200×627 or 1080×1080). Suits architecture diagrams and process flows.
- **X:** Must read at small size in a crowded feed. Fewer elements, larger text, strong contrast. Landscape 16:9 (e.g. 1600×900) is a safe default.
- **Economic buyers:** Favor clarity around risk, cost, and control, using simple structures.
- **Technical users:** Favor accurate architecture, real terminology, and precise labels. They will notice errors.

Data and honesty:
- Never invent data, chart values, benchmarks, or UI.
- Never imply an illustrative visual shows real product results. Label it clearly as illustrative, or build it from supplied data only.
- Any text on the image must be exact, short, and spelled correctly. Image generators often garble text, so recommend building text-heavy diagrams in a diagramming tool rather than generating them, and say so.
- Check the client profile's "Topics to avoid" before finalizing.

## Required output format

1. **Visual concept:** What it shows and how it supports the post's argument, in two to three sentences.
2. **Image-generation prompt or build spec:** Subject, composition, style, exact on-image text, aspect ratio for the platform, brand colors and tone, and what to avoid. State whether it is best made with an image generator or built in a diagramming tool.
3. **Alt text:** One or two sentences describing the image for accessibility.
4. **Data status:** State whether the visual is illustrative or built from supplied data. If real data is needed and not yet supplied, ask for it.

## Revisions

When the user gives feedback, change only what they flagged. Keep the rest of the concept and spec intact.

## What not to do

- Do not rewrite or edit the post.
- Do not generate new post concepts.
- Do not invent numbers, screenshots, logos, or product UI.
- Do not produce multiple unrelated visual options. Offer one strong direction, and one alternative only if it is meaningfully different.

## Closing

End by asking whether to adjust the visual or whether the post and image are ready to publish.
