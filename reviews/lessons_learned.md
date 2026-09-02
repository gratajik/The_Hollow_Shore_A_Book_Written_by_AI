After analyzing 15 review passes, the striking pattern is **non-convergence**: the same critical issues recur identically across passes 12-15 without ever being fixed. Most of what I see is already covered by existing rules (28a-28j, §4.3.1-4.3.2). Let me identify only what's genuinely new and would have prevented a Major+ issue.

PROPOSED: Contradictory EXCEPTION declarations across passes signal an undeclared, unresolved pattern — resolve on the pass that first oscillates
LAYER: 4
PLACEMENT: after §4.3 rule 28i (as new lesson 28k)
EVIDENCE: Across passes 12-15, the uncontracted-register and paragraph-length patterns swung from "200+ defects / M1-M2 Major violations" (pass 12) to "authorized EXCEPTION, no fix required" (passes 13-15) with no EXCEPTION block ever verifiably written to facts.md. Pass 12 demanded either an EXCEPTION or a 200-instance revert; passes 13-15 simply asserted the EXCEPTION exists ("per §4.3," "documented and approved") without the block being confirmed present. Same prose, opposite verdicts, four consecutive passes.
EXISTING COVERAGE: 28b (fabricated exceptions) and 28i (inherited honored-lists) are closest. 28b covers a reviewer inventing an exception to dismiss a violation; 28i covers uncritical inheritance of a honored-list header. Neither covers the specific oscillation where pass N flags a pattern as a mass defect and pass N+1 declares it settled style — the transition itself being the diagnostic that the EXCEPTION was asserted but never written.
EXACT TEXT:
**28k. A pattern that flips from mass-defect to settled-style between consecutive passes was never actually declared — the flip is the diagnostic.** When one pass flags a pervasive pattern (uncontracted forms, long paragraphs, a register choice) as a large-count Major/Critical defect requiring a mass revert, and the very next pass declares the identical prose "authorized settled style, no fix required" citing an EXCEPTION, the transition itself proves the EXCEPTION block does not exist verbatim in facts.md — if it existed, the earlier pass would have honored it. This is worse than 28b (a one-pass fabrication) because the pattern now toggles indefinitely: any later pass may re-flag it as a mass defect, re-triggering a 200-instance revert threat that a subsequent pass again waves off. Detection: any pattern whose manuscript-wide verdict inverts (defect↔honored) across two consecutive passes with unchanged prose. Fix: on the FIRST pass that would honor a previously-flagged mass pattern, the reviewer must confirm the `### EXCEPTION:` block exists in facts.md by quoting its verbatim title; if it does not exist, the reviewer must either write it that pass (per §4.3 format, with speech-domain scope per 28d) or reinstate the defect and route the mass revert. Asserting "per §4.3" or "documented and approved" without quoting the actual block title is not confirmation.

SKIPPED: Undefined character/place-name in dialogue ("Brazil," "Switzerland" as forms of address) — already covered by §4.3.1 (scanner false positives, corporate/place fragments) and the fix is the same declare-once-EXCEPTION mechanism.

SKIPPED: First-person "we/us" bleed into third-person narration (Ch18, Ch25) — already covered by §4.4 convergence and 28g/reviewer-instability; the passes themselves disagreed on whether it was diegetic (journal/dialogue) vs. narrator intrusion, which is a canonicity/scope question already governed by §5.3.1 and 28d.

SKIPPED: Ch25/Ch29 narration-person contradicts story bible (first vs third person) — single-manuscript structural continuity issue, not a generalizable AI reproduction pattern; also a straightforward spec-vs-prose reconciliation already implied by §5.1.1 propagation discipline.

SKIPPED: Emergent repeated phrases ("finger tapped once against," "for a long time," "her right index finger," "for twenty five years") — already fully covered by Rule 101 (emergent-fingerprint scan) and §3.6 sibling patterns.

SKIPPED: Near-duplicate passages / re-staged beats across chapters (ch04/ch06, ch30/ch31) — already covered by §6.11b (one beat, one staging) and Rule 103.

SKIPPED: Datestamp opening clusters across consecutive chapters — already covered by §6.7's opening-type CLUSTERING rule (added explicitly for exactly this three-consecutive-same-type case).

SKIPPED: Pronoun/gender mismatch for a female character (Martinez / "his voice") — single continuity slip; already covered by §5.3 grep-every-proper-noun and Pass 2 voice checks.

SKIPPED: Fused-word markup ("nor'easter") and outline-leak ("The Architect") as high-counter carry-forwards — the phenomenon (surgical single-string fix that the general fix loop can't route to, climbing counter) is already precisely covered by 28c, 28e, and 28f.

SKIPPED: "the weight of" / "there was something" flagged then cleared as false-positive across passes — already covered by 28g (pattern-count instability, deterministic counting required) and 28b (dismissal must cite a real basis).
---
APPLIED 2026-09-01: 28k added to writing-guide SKILL.md (BookForge develop) with one tightening - the flip proves the block was never read at honor time, not necessarily that it never existed; quote-to-honor resolves both. Approved by Greg.
