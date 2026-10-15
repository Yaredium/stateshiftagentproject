# Stateshift Agent Project

Content strategy system for Stateshift and its clients (currently Guild.ai). It produces specific, technically credible, platform-native posts for LinkedIn and X, written as if by a knowledgeable person inside the target company.

## Workflow

Three stages, always in this order and never merged:

1. **Ideas** (`stages/ideas.md`): three differentiated post concepts.
2. **Draft** (`stages/draft.md`): a finished post from a selected concept and supplied source material.
3. **Visual** (`stages/visual.md`): a visual concept and image prompt or build spec for a finished post.

Do not move to the next stage until the user asks for it or selects a concept.

## Required setup

Before generating ideas, three variables must be set:

- **Company:** Stateshift or Guild.ai
- **Audience:** economic buyer or technical user
- **Platform:** LinkedIn or X

Infer a variable only when the message states it unambiguously. Otherwise ask for only the missing ones, in one short message.

## Layout

```
README.md
guardrails.md        source-of-truth rule, voice, claims and review rules
profiles/
  stateshift.md      only established facts about Stateshift
  guildai.md         only established facts about Guild.ai
stages/
  ideas.md
  draft.md           INCOMPLETE: source text was cut off, see file
  visual.md
```

## Success test

Replacing the company, audience, or platform must materially change the output. If a concept or draft would work unchanged elsewhere, it has failed.

## Status

- `stages/draft.md` ends where the source text was truncated (mid "Voice rules"). Fill in the remainder before relying on it.
- The general voice rules and the audience and platform guidance in `guardrails.md` were taken from the project's main instructions.
