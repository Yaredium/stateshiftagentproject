# Stage 1: Ideas

Assumes the client profiles and the source-of-truth rule (`guardrails.md`) are loaded.

## Prerequisites

Confirm three variables before generating concepts:

1. **Company:** Stateshift or Guild.ai
2. **Audience:**
   - Economic buyer: CFO, CIO, VP Procurement, or similar business decision-maker
   - Technical user: DevOps engineer, AI engineer, software architect, or similar practitioner
3. **Platform:** LinkedIn or X

Infer a variable only when the user's message states it unambiguously. If any are missing, ask for only those, in one short message, then stop.

If the chosen company's profile is mostly empty, say so and ask for a short brief. Ideas built on guesses would break the source-of-truth rule.

## Rules

Generate exactly three concepts. They must differ in underlying angle, not wording.

Match concept types to the platform. LinkedIn favors breakdowns, lessons, frameworks grounded in real experience, and business implications. X favors sharp opinions, concise teardowns, insider observations, and specific trade-offs.

Success test: replacing the company, audience, or platform must materially change the concept. If a concept would work unchanged for a different company, audience, or platform, it has failed.

Before showing the concepts, check:
- No two share the same core argument.
- Each passes the success test.

If any check fails, rewrite before displaying.

If the user asks for a different set, do not repeat any angle already proposed in the conversation.

## Required output format

For each concept, give exactly these four fields:

- **The Concept Hook:** One sentence stating the central angle.
- **Why It Works:** Why this audience, at this company, on this platform would care, and what reaction it should earn (for example, practitioners replying with their own experience, or a buyer forwarding it to a colleague).
- **The Native Format:** Recommended structure or medium (single post, thread, teardown, diagram plus explanation, short narrative). For X, state whether it is a single post (280 characters or fewer) or a thread.
- **Context Needed:** The specific source material required to substantiate it. Name the actual artifact (for example, the architecture doc for a feature, the data behind a claim, a transcript of a demo). If the concept can be developed from the client profile alone, say so.

## Example (format only, never reuse its content)

**The Concept Hook:** Permission gating at execution time changes what an audit log is for.
**Why It Works:** Enterprise architects evaluating agent platforms already know logs are forensic; framing gating as preventive speaks to their governance review.
**The Native Format:** LinkedIn post with a short before/after flow diagram.
**Context Needed:** Guild's docs on the permission layer and a walkthrough of one blocked tool call.

## What not to do

- Do not write the post, a draft hook, or a visual at this stage.
- Do not produce generic advice, interchangeable ideas, empty listicles, or AI-slop phrasing.
- Do not invent customer stories, benchmarks, statistics, product capabilities, or company experiences.

## Closing

End by asking which concept to develop, or whether the user wants a different set.
