# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with this repository.

## Project Overview

This is a novel manuscript project: **"The Hollow Shore,"** a psychological thriller with murder mystery elements. A private investigator (Maya Chen) is drawn to a remote Maine island to investigate an apparent suicide, discovers murder, and is eventually forced to confront her own suppressed childhood trauma that connects her to the victim and a decades-long conspiracy. Author: Greg Ratajik.

The book was originally drafted using an early AI workflow (book-memory-bank system). It is being restructured into the BookForge canonical layout so the `@ReviewerAgent` can pass over it and improve it.

## Key Files

- **story.md** — Single source of truth: characters, voice cards, plot sequence, per-chapter state table, who-knows-what matrix, emotional arcs, critical requirements. **If a chapter conflicts with story.md, story.md wins.**
- **style_guide.md** — Voice & style conventions specific to this book (Maya's Southern-drawl-under-stress rule, three-author blend, present-tense flashbacks).

### BookForge Plugin (shared across projects)

- **@ReviewerAgent** — Full manuscript review (consistency, flow, publisher-readiness, AI tells, book-specific validation). Invoke with `@ReviewerAgent`.
- **writing-guide skill** — Prose rules, AI fingerprint prevention, voice system, continuity tracking. Loaded automatically.

### Project Directory Structure

- **chapters/** — Prose only (`ch01.md` through `ch28.md`)
- **matter/** — Front and back matter (`title_page.md`, `copyright.md`, `dedication.md`, `about_author.md`)
- **tracking/** — All continuity and production tracking (`stats.md`, `timeline.md`, `facts.md`, `threads.md`, `session_log.md`, `review_issues.md`)
- **reviews/** — Review pass deliverables (`review_pass_1.md`, etc.)
- **publishing/** — Final outputs (`manuscript.md`, `manuscript.docx`, `cover_prompts.md`, `kdp_package.md`, `covers/`)

## Critical Requirements (from story.md)

- Third-person limited POV, primarily Maya Chen. Brief sanctioned shifts to Eleanor, James, or Dr. Richard only. **No head-hopping within scenes.**
- Past tense for present-day narrative. **Present tense for childhood flashback sequences** — this is deliberate; the reviewer should not flag it as a drift.
- **Maya's Southern drawl is stress-correlated.** It emerges under pressure, excitement, or on the cusp of solving a case. It must not leak into her calm/baseline narration. A calm chapter with drawl is a voice-card violation.
- **Memory recovery is gradual, triggered, and sensory-first.** Never abrupt, never convenient. Smell → image → voice → scene.
- Target: ~90,000 words, 28 chapters. **Current manuscript is ~41,000 words** — reviewer should flag the chapter-length disparity (ch01 = 1,834; ch28 = 676). Late chapters carry outsized plot (international raid, Geneva climax, logic bomb, epilogue) on thin word count.
- Three-author style blend: Tana French (lyricism), Gillian Flynn (sharpness), Kate Atkinson (complex plotting). When these conflict in a scene, Flynn wins on dialogue, French wins on setting, Atkinson wins on reveal mechanics.
- Em-dashes target zero. Current manuscript has 159 — reviewer will remove.
- Forbidden dialogue tag budget is near-zero. Current manuscript has 64 — reviewer will replace with action beats.

Universal rules (em-dashes, dialogue tags, paragraph limits, AI fingerprint prevention) are enforced by the writing-guide skill and do not need to be repeated here.

## Writing Workflow

Primary workflow for this project is `@ReviewerAgent` — review/fix loop to improve existing manuscript. Do NOT use `@WriteBookAgent` (the chapters are already drafted).

For manual single-chapter edits, follow the ReviewerAgent's per-chapter fix workflow: re-read story.md, apply changes, re-run mechanical checklist on touched paragraphs, update tracking/stats.md immediately.

## Stats Tracking (CRITICAL)

**Update `tracking/stats.md` after EVERY chapter edit or fix pass, no exceptions.** This file tracks:
- Chapter word counts (re-run `wc -w` on modified chapters)
- Running total word count
- Em-dash count per chapter (target 0 manuscript-wide)
- Forbidden dialogue tag violations
- Opening type per chapter — no type used more than 3x
- Ending type per chapter — max 2-3 aphoristic endings total
- Emotional temperature — no more than 3 consecutive same temperature
- POV character per chapter (Maya for all, but track anyway)
- Banned phrase violations found and fixed

Stats drift is cumulative and becomes impossible to fix retroactively. Do not defer. Do not batch.

**Production stats** (one entry per review pass):
- Input tokens, output tokens, running totals
- Time taken (minutes)
- Estimated cost (Opus 4.7 pricing: $5/MTok input, $25/MTok output)

## Prompt & Response Logging

Log every significant interaction to `tracking/session_log.md` using the standard BookForge entry template (user prompt summary, what I did, what worked, what didn't, artifacts produced, prompt template). This data feeds the BookForge automation.

## Post-Review: Lessons Learned

After each review pass, distill generic lessons and add to the writing-guide skill:
1. Every lesson must be book-agnostic.
2. Placement matters — Golden Rules are rare.
3. Deduplicate before adding.

## Git Workflow

Commit and push after every major milestone:
- Completing a review pass (writing review_pass_N.md)
- Completing a fix pass (editing chapters to resolve issues)
- Updating tracking files

Do not ask for permission. Commit and push automatically at milestones.
