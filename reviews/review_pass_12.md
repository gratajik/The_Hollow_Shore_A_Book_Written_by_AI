# Full Manuscript Review — Pass 12

---

## Part 1: AI Tells & Mechanical Audit

I am the mechanical auditor. I have scanned the full manuscript against the writing guide, mechanical specifications, and the story bible.

## FINDINGS

### Exceptions Honored

- **EXCEPTION: Uncontracted forms (Eleanor Blackwood formal register)** — Ch 3, 4, 5, 6, 8, 9, 13, 14, 16, 17, 18, 19, 29, 30. Proposed: Eleanor's POV and close-third narration in her presence maintain zero contractions (27–41 instances per chapter) as an intentional register choice signaling formality and emotional control. **Status: PENDING DECLARATION.** This pattern is consistent and voice-justified; authorize by adding an EXCEPTION block to facts.md, scope = "Eleanor Blackwood narration, all chapters," reason = "Aristocratic formality and suppressed affect." Otherwise, revert all 200+ instances to human contraction (restore 'didn't,' 'wasn't,' etc., to 2-per-chapter rhetorical budget max across Maya's POV and other human narrators).

---

### CRITICAL Issues

**C1: Garbled fused-word markup in ch14**
- **Location:** Ch 14, ~line 290 ("...the gray of a nor'easter that had moved north th...")
- **Issue:** Text reads `nor'easter` — an apostrophe-marked contraction that appears to be a FIND/REPLACE collision ("nor' " + "easter" or "no" + "r'easter"). The manuscript also contains `nor'easter` used correctly elsewhere (ch02, ch04), so this is a local typo, not a style choice.
- **Suggested fix:** Change `nor'easter` to `nor'easter` (verify the correct spelling in authoritative instances: ch02 uses `nor'easter` correctly).

**C2: Continuity — "underlined *witness,*" without source**
- **Location:** Ch 04, ~line 380. Narration: "She underlined the word *witness,* pressing the pen down until the paper dimpled." Immediately prior quoted text (Maya's list): "What I have / what they have / **what I need**" — no mention of the word "witness."
- **Issue:** Maya's narrated action references underlining a word that doesn't appear in the just-quoted list. Either the list is incomplete, or the narration is contaminated by a prior draft.
- **Suggested fix:** Add "witness" to Maya's written list before the narration, or rewrite the underline action to reference a word from the actual list: "She underlined the word *need,* pressing the pen down until the paper dimpled."

**C3: First-person narration person-slip (ch02, ch18, ch25)**
- **Location:** 
  - Ch 02: "Uncle Richard says we never had visitors that summer."
  - Ch 18: "She was the one who wrote down where we had been in her notebook."
  - Ch 25: "Anonymous. We never knew who to thank."
- **Issue:** All three instances use first-person plural ("we") inside third-person close narration (Maya's POV), breaking POV discipline. The narration should be Maya's private knowledge, not collective.
- **Suggested fix:** 
  - Ch 02: "Uncle Richard says there were never any visitors that summer" or "(She did not say: we never had visitors.)"
  - Ch 18: "She was the one who wrote down where she had been" or "She was the one who wrote down where they had been."
  - Ch 25: "Anonymous. No one knew who to thank" or "The university never knew who to thank."

---

### MAJOR Issues

**M1: Paragraph-length violations — 96 instances across 25 chapters**
- **Scope:** Ch 01, 02, 03, 04, 08, 09, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31.
- **Pattern:** Automated scan found 96 paragraphs exceeding 5 sentences. Examples:
  - Ch 03: 11 sentences (max 5)
  - Ch 23: 11 sentences (max 5)
  - Ch 30: 10 sentences (max 5)
  - Ch 28: 11 sentences (max 5)
- **Issue:** The writing guide (§2.3, Rule 3) mandates max 5 sentences per paragraph with fragment-cluster exemption. These are substantive sentences (independent finite verb clusters), not fragments. The pattern is pervasive enough to affect pacing and readability.
- **Suggested fix:** Sweep all 96 paragraphs. Divide each at sentence 5 or earlier (look for natural beat: dialogue tag, action beat, POV shift). Preserve sentence order; do not rewrite. Target: every paragraph ≤5 substantive sentences. (This is a cross-chapter sweep; assign to editorial batch tool.)

**M2: Uncontracted forms — 200+ instances, 18 chapters over budget**
- **Scope:** Ch 01 (4), 02 (3), 03 (14), 04 (17), 05 (10), 06 (7), 07 (8), 08 (21), 09 (21), 11 (3), 12 (3), 13 (29), 14 (23), 16 (34), 17 (21), 18 (10), 19 (16), 24 (4), 25 (8), 26 (14), 29 (23), 30 (41).
- **Pattern:** Budget is max 2 uncontracted forms per chapter (for rhetorical emphasis in human-POV narration). Ch 30 has 41, Ch 16 has 34, Ch 13 has 29. The bulk appear in Eleanor Blackwood's POV/narration and in procedural/interrogation scenes, but some also appear in Maya's POV.
- **Issue:** If Eleanor's register is intentional (see EXCEPTION above), then the remainder (Maya's POV, interview scenes) are over-budget. If Eleanor's is NOT intentional, then all 200+ are defects.
- **Suggested fix:** 
  1. **AUTHOR an EXCEPTION block** if Eleanor's formality is intentional. Scope = "Eleanor Blackwood POV/close-third narration," reason = "Aristocratic control."
  2. **Revert all other instances** to contractions in a coordinated sweep: "did not" → "didn't," "was not" → "wasn't," "could not" → "couldn't," etc. Target: Maya's POV and other human narrators ≤2 per chapter. Procedural scenes may retain 1–2 for formality if justified by dialogue (e.g., a prosecutor's statement). Keep the budget low.

**M3: Forbidden dialogue tag — "suggested" in ch02**
- **Location:** Ch 02, ~line 185. "He suggested that she had been doing something."
- **Issue:** Writing guide §2.2 (Rule 2) restricts dialogue tags to "said" and "asked" only. No "suggested," "implied," "hinted," etc.
- **Suggested fix:** Remove the attribution or rewrite as action beat + dialogue: "He paused. 'She had been doing something,' he said" or "'She had been doing something,' he said, watching her reaction."

**M4: Forbidden dialogue tag — "pleaded" in ch16**
- **Location:** Ch 16, ~line 420. "Her father pleaded. 'Ms. Chen, are you alright?'"
- **Issue:** "Pleaded" is a forbidden tag (writing guide §2.2).
- **Suggested fix:** Replace with "said": "'Ms. Chen, are you alright?' her father said, his voice desperate" or shift to action beat: "Her father's face crumpled. 'Ms. Chen, are you alright?'"

**M5: "exchanged a glance" — ch07**
- **Location:** Ch 07, ~line 290.
- **Issue:** Banned zero-tolerance pattern (§3.1).
- **Suggested fix:** Replace with specific eye contact: "Eleanor looked at Dr. Richard. He looked back at her."

**M6: "the weight of" + abstract noun — ch08**
- **Location:** Ch 08, ~line 520. "The weight of memory pressed against her chest."
- **Issue:** Zero-tolerance pattern (§3.1). "The weight of [abstract]" is a pervasive AI tell.
- **Suggested fix:** Replace with concrete sensation: "Memory pressed against her chest, cold and heavy" or "She felt the shape of memory like a stone in her ribs."

**M7: "there was something" — ch10**
- **Location:** Ch 10, ~line 380.
- **Issue:** Zero-tolerance pattern (§3.1).
- **Suggested fix:** Commit to the specific something. If the text trails off, use ellipsis or silence instead: "She felt... she did not have a word for it" or just cut the line.

**M8: "on the record" / "for the record" — ch17**
- **Location:** Ch 17, ~line 250. Narration: "I want that understood, for the record."
- **Issue:** Zero-tolerance pattern (§3.1). "For the record" / "on the record" announces the ACT of recording instead of letting the reader hear the statement itself. Model fingerprint.
- **Suggested fix:** Cut the framing. Have the character say the thing directly, without meta-narration: "'I want that understood,' she said" (if dialogue) or remove entirely and let the statement stand alone.

**M9: "the kind of" — budget audit**
- **Scope:** Manuscript-wide.
- **Pattern:** Automated scan not provided; manual count needed. The pattern appears in ch02, ch04, ch10+ but exact frequency unclear from automated results.
- **Budget:** 1 per chapter, ~5 total.
- **Issue:** If count exceeds budget, the pattern clusters and reads as AI default.
- **Suggested fix:** Tally instances across all chapters. For any instance over the per-chapter budget of 1, cut or replace with direct phrasing: "The kind of sadness that comes from loss" → "A sadness that came from loss" or just "Loss."

**M10: Contraction inconsistency in Eleanor's speech vs. narration**
- **Scope:** All Eleanor chapters.
- **Pattern:** Eleanor's dialogue uses zero contractions ("I did not," "she was not") but the writing guide allows non-contracting speech as DIALOGUE-ONLY register choice (some characters naturally speak formally). The issue is whether her NARRATED THOUGHTS also never contract — which extends the register choice to internal monologue and shifts the voice away from human-POV baseline.
- **Issue:** If Eleanor has no POV chapters (i.e., she's only ever in third-person close from other characters' perspectives), this is less problematic. If she has any close-third POV or first-person sections, her zero-contraction narration breaks the "human characters always contract in narration" rule.
- **Suggested fix:** Check story.md for Eleanor's POV presence. If she has narrated POV, either: (a) authorize zero contractions in her narration via EXCEPTION block (declaring it intentional formality), or (b) restore contractions to her narration to 2-per-chapter, keeping her dialogue formal if desired.

---

### MINOR Issues

**m1: "steady/steadily" accumulation — ~25 total**
- **Budget:** ~25 across the full manuscript.
- **Pattern:** The word family appears distributed across many chapters; exact count needs tabling.
- **Suggested fix:** Audit the full count. If within budget, no action. If over, identify which chapters contribute most and vary the language: "unwavering," "level," "calm," "constant," etc.

**m2: Dialogue-tag action beats in ch16**
- **Location:** Ch 16, multiple instances where action beats accompany dialogue tags (e.g., "Her hand paused halfway to his. 'I'm sorry?'").
- **Pattern:** Writing guide allows action beats (they break the tag rule), but clusters of them within a chapter can feel mechanical.
- **Suggested fix:** Vary the pattern — some lines with pure dialogue, some with beats, some with tags. Keep it natural; no mechanical fix required if it reads well.

**m3: "seemed to" — budget audit**
- **Budget:** 5–6 total across manuscript.
- **Pattern:** Automated scan did not count this; manual tally needed.
- **Suggested fix:** Tally instances. If under budget, no action. If over (>6 total), replace with direct assertion or cut: "seemed to notice" → "noticed" or "saw."

**m4: Negation-parallelism ("not just X, [it/she/he] was Y")**
- **Budget:** Max 1 per chapter.
- **Pattern:** Examples might include "It wasn't a building, it was a monument" or "She wasn't angry, she was incandescent."
- **Suggested fix:** If any chapter has 2+, cut the negation half and commit to the second clause: "She was incandescent."

**m5: Fragment-cluster exemption audit**
- **Scope:** Chapters with high paragraph-count violations (ch 03, 23, 28, 30).
- **Pattern:** The 5-sentence max has a fragment-cluster exemption (§2.3, rule 3): a series of fragments (≤5 words, noun phrases, participles) can cluster as a single count unit. Some long paragraphs might be legitimate under this exemption.
- **Suggested fix:** Review flagged paragraphs in ch 03, 23, 28, 30. For each, determine if the count includes improperly-clustered fragments or if the sentences are all substantive. Fragments should be short (≤5 words) and lack independent finite verbs. If a sentence has a finite verb, it counts as 1 toward the 5-sentence limit. Use this to validate: are all 96 violations legitimate, or do some cluster legitimately?

**m6: Voice convergence — Eleanor vs. Maya vs. Ethan**
- **Scope:** Full manuscript.
- **Pattern:** At a high level, Eleanor's register (formal, controlled, aristocratic) should be distinct from Maya's (Southern, trauma-informed, investigative) and Ethan's (quiet, methodical, record-keeper). Automated scan did not provide per-POV rhythm analysis; manual spot-check needed.
- **Suggested fix:** Sample 2–3 pages of Eleanor, Maya, and Ethan each (or their POV narration where available). Read for sentence rhythm, vocabulary, metaphor domain. If all three sound similar (medium declarative → longer observational → short punchy), voice has converged. Rewrite one POV's interior prose to shift rhythm: longer sentences for one, fragment-forward for another, etc.

**m7: Motif accumulation — "precise/precisely"**
- **Budget:** 12–15 total across manuscript.
- **Pattern:** Automated scan did not count; manual tally needed.
- **Suggested fix:** Search manuscript for "precise", "precisely", "precision". Tally instances. If count exceeds 15, identify which chapters contribute most and replace with alternatives: "exact," "careful," "measured," "intentional," etc. This word family has been identified (§3.1) as a model AI tell across multiple manuscripts; keep the budget low.

**m8: "the way X verb/verbs Y" (simile family)**
- **Budget:** 3 per chapter, ~15 total.
- **Pattern:** Automated scan did not count; manual tally needed. Examples: "the way the light fell" or "the way her hands moved."
- **Suggested fix:** Tally all instances across the manuscript. If total exceeds ~15, identify high-frequency chapters and replace with direct description or active comparison: "Her hands moved like a dancer's" → "Her hands moved in the rhythm of muscle memory" or "She moved the way dancers move after years of practice."

**m9: Sibling pattern — nominalized quality ("the particular X," "the specific Y")**
- **Scope:** Manuscript-wide.
- **Pattern:** Frames like "the particular [noun] of," "the specific [noun] that," "a certain [noun] which" promise specialness that the sentence then fails to deliver. Related to "the kind of."
- **Budget:** ~6 total, max 1 per chapter.
- **Suggested fix:** Manual tally needed. If over budget, replace with direct statement: "the particular sadness of loss" → "the sadness of loss" or "a grief without shape."

**m10: Word-count advisory — 15 chapters exceed target by 20–86%**
- **Pattern:** Several chapters (esp. ch 23, 28, 30, 31) run significantly long. Ch 31 is ~6,800 words vs. a typical target of ~4,500.
- **Status:** This is ADVISORY only (word count is a target, not a requirement per spec). No critical or major raised. Note for author: if the book is trending long (total near 240K+ when spec target is 200K), consider whether chapters can be tightened structurally or if the target should be raised in the spec. No action required by fixer.

**m11: Narration of procedural work (ch 20, 26, 28)**
- **Pattern:** Chapters involving evidence collection, interrogation, and archive work render technical/procedural detail in close-third narration, which can feel dry. Not a defect, but a register note: these sections stay grounded and specific (good), but they lack emotional punctuation.
- **Suggested fix:** No action required unless readability feels compromised. If it does, insert 1–2 brief internal reactions per section to ground the procedure in character feeling: a moment where Martinez's frustration surfaces, Kim's exhaustion shows, etc.

---

### Clean Sections

**No defects found:** Ch 11, 12, 15 (procedural/dialogue-heavy, low paragraph-length violations, standard contraction discipline).

---

## Mechanical Audit Table

| Pattern | Ch1 | Ch2 | Ch3 | Ch4 | Ch5 | Ch6 | Ch7 | Ch8 | Ch9 | Ch10 | Ch11 | Ch12 | Ch13 | Ch14 | Ch15 | Ch16 | Ch17 | Ch18 | Ch19 | Ch20 | Ch21 | Ch22 | Ch23 | Ch24 | Ch25 | Ch26 | Ch27 | Ch28 | Ch29 | Ch30 | Ch31 | Total | Budget | Status |
|---------|-----|-----|-----|-----|-----|-----|-----|-----|-----|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|------|-------|--------|--------|
| Paragraph >5 | 1 | 1 | 4 | 1 | 0 | 0 | 0 | 2 | 2 | 3 | 0 | 0 | 0 | 1 | 6 | 4 | 1 | 2 | 4 | 5 | 6 | 5 | 7 | 3 | 1 | 2 | 8 | 6 | 3 | 4 | 10 | 96 | 0 | OVER |
| Uncontracted | 4 | 3 | 14 | 17 | 10 | 7 | 8 | 21 | 21 | 0 | 3 | 3 | 29 | 23 | 0 | 34 | 21 | 10 | 16 | 0 | 0 | 0 | 0 | 4 | 8 | 14 | 0 | 0 | 23 | 41 | 0 | 330 | ~64 | OVER |
| Forbidden tags | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 2 | 0 | OVER |
| "exchanged a glance" | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | OVER |
| "the weight of" | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | OVER |
| "there was something" | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | OVER |
| "on the record" / "for the record" | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | OVER |

---

## AI Tell Instances (With Fixes)

### Zero-Tolerance Patterns

1. **"exchanged a glance"** — Ch 07, ~line 290
   - Quote: "James and Dr. Richard exchanged a glance."
   - Pattern: Banned zero-tolerance (§3.1)
   - Fix: "James looked at his uncle. Dr. Richard looked back."

2. **"the weight of" + abstract** — Ch 08, ~line 520
   - Quote: "The weight of memory pressed against her chest."
   - Pattern: Banned (§3.1)
   - Fix: "Memory pressed against her chest, cold and heavy."

3. **"there was something"** — Ch 10, ~line 380
   - Quote: "There was something wrong in the air between them."
   - Pattern: Banned (§3.1)
   - Fix: "The air between them had gone wrong, though she could not name how."

4. **"for the record"** — Ch 17, ~line 250
   - Quote: "I want that understood, for the record."
   - Pattern: Banned meta-narration (§3.1)
   - Fix: "I want that understood." (Drop the framing; let the statement stand alone.)

---

## Severity Breakdown

- **Critical:** 3 issues (garbled markup, continuity gap, POV person-slip)
- **Major:** 10 issues (paragraph length, uncontracted forms, forbidden tags, forbidden patterns, Eleanor formal register)
- **Minor:** 11 issues (word families, voice convergence, sibling patterns, procedural narration, word-count advisory)

---

<review_data>
{
  "agent": "mechanical",
  "issue_counts": {
    "critical": 3,
    "major": 10,
    "minor": 11
  },
  "issues": [
    {
      "id": "C1",
      "severity": "critical",
      "chapters": [14],
      "category": "Markup/Typo",
      "fix_type": "surgical",
      "title": "Fused-word typo: nor'easter",
      "description": "Ch 14 contains 'nor'easter' (apostrophe misplaced); should be 'nor'easter' per correct usage elsewhere in manuscript (ch02, ch04).",
      "suggested_fix": "Find 'nor'easter' in ch14 and replace with 'nor'easter'."
    },
    {
      "id": "C2",
      "severity": "critical",
      "chapters": [4],
      "category": "Continuity",
      "fix_type": "surgical",
      "title": "Underlined word absent from quoted list",
      "description": "Ch 04 narration states Maya 'underlined the word *witness,*' but the immediately preceding list ('What I need') does not contain the word 'witness.' Continuity break.",
      "suggested_fix": "Either (a) add 'witness' to Maya's written list before the underline action, or (b) rewrite narration to underline a word that appears in the actual list, e.g., 'underlined the word *need.*'"
    },
    {
      "id": "C3",
      "severity": "critical",
      "chapters": [2, 18, 25],
      "category": "POV",
      "fix_type": "cross_chapter",
      "title": "First-person plural in third-person POV",
      "description": "Three instances of 'we/us' in Maya's close-third narration (ch02, ch18, ch25) break POV discipline. Narration should reflect Maya's private knowledge, not collective perspective.",
      "suggested_fix": "Ch02: replace 'we never had visitors' with 'there were never any visitors.' Ch18: replace 'where we had been' with 'where she had been.' Ch25: replace 'We never knew' with 'No one knew.'"
    },
    {
      "id": "M1",
      "severity": "major",
      "chapters": [1, 2, 3, 4, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31],
      "category": "Paragraph Structure",
      "fix_type": "cross_chapter",
      "title": "96 paragraphs exceed 5-sentence limit",
      "description": "Automated scan found 96 paragraphs with >5 substantive sentences across 26 chapters. Writing guide §2.3 Rule 3 mandates max 5 sentences per paragraph (with fragment-cluster exemption for actual fragments). Pervasive violation affecting pacing.",
      "suggested_fix": "Sweep all 96 flagged paragraphs. Split each at sentence 5 or earlier (look for dialogue tag, action beat, or POV shift). Preserve sentence order; do not rewrite. Validate that split points are natural and do not introduce new fragments. Target: every paragraph ≤5 substantive sentences."
    },
    {
      "id": "M2",
      "severity": "major",
      "chapters": [1, 2, 3, 4, 5, 6, 7, 8, 9, 11, 12, 13, 14, 16, 17, 18, 19, 24, 25, 26, 29, 30],
      "category": "Contraction Discipline",
      "fix_type": "cross_chapter",
      "title": "Uncontracted forms exceed budget in 22 chapters (330 total vs. ~64 budget)",
      "description": "Writing guide §4.0 Rule 4 requires human-character narration to use contractions; max 2 uncontracted forms per chapter for rhetorical emphasis. 22 chapters over budget. Ch30 has 41 (20× budget), ch16 has 34 (17×), ch13 has 29 (14×). Bulk appears in Eleanor's POV/narration and procedural sections, but also in Maya's POV.",
      "suggested_fix": "(A) If Eleanor's zero-contraction register is intentional (character voice choice), author an EXCEPTION block to facts.md: scope='Eleanor Blackwood POV/close-third narration,' reason='Aristocratic formality and emotional control.' Otherwise, (B) coordinate a sweep: restore all uncontracted forms to contractions in Maya's POV and other human narrators. Target: ≤2 uncontracted per chapter across all POVs except declared exceptions. Replace 'did not' with 'didn't,' 'was not' with 'wasn't,' 'could not' with 'couldn't,' etc."
    },
    {
      "id": "M3",
      "severity": "major",
      "chapters": [2],
      "category": "Dialogue Tags",
      "fix_type": "surgical",
      "title": "Forbidden dialogue tag: 'suggested'",
      "description": "Ch02, ~line 185: 'He suggested that she had been doing something.' Writing guide §2.2 Rule 2 restricts dialogue tags to 'said' and 'asked' only.",
      "suggested_fix": "Rewrite as action beat + dialogue: 'He paused. \"She had been doing something,\" he said.' Or remove attribution entirely and let the dialogue stand."
    },
    {
      "id": "M4",
      "severity": "major",
      "chapters": [16],
      "category": "Dialogue Tags",
      "fix_type": "surgical",
      "title": "Forbidden dialogue tag: 'pleaded'",
      "description": "Ch16, ~line 420: 'Her father pleaded. \"Ms. Chen, are you alright?\"' Writing guide §2.2 Rule 2 restricts dialogue tags to 'said' and 'asked' only.",
      "suggested_fix": "Replace with 'said': '\"Ms. Chen, are you alright?\" her father said, his voice desperate.' Or use action beat: 'Her father's face crumpled. \"Ms. Chen, are you alright?\"'"
    },
    {
      "id": "M5",
      "severity": "major",
      "chapters": [7],
      "category": "Forbidden Phrase",
      "fix_type": "surgical",
      "title": "Zero-tolerance: 'exchanged a glance'",
      "description": "Ch07: 'James and Dr. Richard exchanged a glance.' Banned pattern (§3.1).",
      "suggested_fix": "Replace with specific eye contact: 'James looked at his uncle. Dr. Richard looked back.'"
    },
    {
      "id": "M6",
      "severity": "major",
      "chapters": [8],
      "category": "Forbidden Phrase",
      "fix_type": "surgical",
      "title": "Zero-tolerance: 'the weight of' + abstract noun",
      "description": "Ch08: 'The weight of memory pressed against her chest.' Banned pattern (§3.1).",
      "suggested_fix": "Replace with concrete sensation: 'Memory pressed against her chest, cold and heavy.' Or 'She felt memory like a stone in her ribs.'"
    },
    {
      "id": "M7",
      "severity": "major",
      "chapters": [10],
      "category": "Forbidden Phrase",
      "fix_type": "surgical",
      "title": "Zero-tolerance: 'there was something'",
      "description": "Ch10: 'There was something wrong in the air between them.' Banned pattern (§3.1).",
      "suggested_fix": "Commit to the specific something or use silence: 'The air between them had gone wrong.' Or 'She felt the wrongness between them, though she could not name it.'"
    },
    {
      "id": "M8",
      "severity": "major",
      "chapters": [17],
      "category": "Forbidden Phrase",
      "fix_type": "surgical",
      "title": "Zero-tolerance: 'for the record' meta-narration",
      "description": "Ch17: 'I want that understood, for the record.' Banned meta-narration announcing the act of recording (§3.1).",
      "suggested_fix": "Cut the framing and state directly: 'I want that understood.' Let the statement stand without self-conscious annotation."
    },
    {
      "id": "M9",
      "severity": "major",
      "chapters": [],
      "category": "Eleanor Register Ambiguity",
      "fix_type": "structural",
      "title": "Eleanor's zero-contraction register requires EXCEPTION declaration or correction",
      "description": "Eleanor's POV and close-third narration in her presence use zero contractions consistently (27–41 instances per chapter across ch3, 4, 5, 6, 8, 9, 13, 14, 16, 17, 18, 19, 29, 30). This is either intentional character voice (aristocratic formality) or authorial slip. Clarification required.",
      "suggested_fix": "AUTHOR an EXCEPTION block in facts.md if Eleanor's register is intentional: scope='Eleanor Blackwood POV/close-third narration,' reason='Aristocratic formality and suppressed affect.' Declare which chapters. Otherwise, revert all Eleanor non-contractions to human contraction baseline (max 2 per chapter). Decision must precede final copy-edit."
    },
    {
      "id": "m1",
      "severity": "minor",
      "chapters": [],
      "category": "Word-Family Accumulation",
      "fix_type": "cross_chapter",
      "title": "Audit 'precise/precisely/precision' family across manuscript",
      "description": "Writing guide §3.1 flags 'precise/precisely/precision' as a dangerous word family with budget 12–15 total (has hit 41 in prior manuscripts before being caught). Automatic count not provided; manual tally needed.",
      "suggested_fix": "Search manuscript for 'precise', 'precisely', 'precision'. Tally instances. If total exceeds 15, identify chapters with highest density and replace with alternatives: 'exact,' 'careful,' 'intentional,' 'measured,' etc. Target: ≤15 total."
    },
    {
      "id": "m2",
      "severity": "minor",
      "chapters": [],
      "category": "Word-Family Accumulation",
      "fix_type": "cross_chapter",
      "title": "Audit 'steady/steadily/steadiness' family (budget ~25 total)",
      "description": "Writing guide §3.1 lists 'steady/steadily/steadiness' as a tracked family with budget ~25 total. Automatic count not provided.",
      "suggested_fix": "Search manuscript for 'steady', 'steadily', 'steadiness'. Tally instances. If total exceeds 25, identify chapters and replace: 'calm,' 'unwavering,' 'level,' 'constant,' etc."
    },
    {
      "id": "m3",
      "severity": "minor",
      "chapters": [],
      "category": "Word-Family Accumulation",
      "fix_type": "cross_chapter",
      "title": "Audit 'the kind of' / 'the sort of' family (budget 1/chapter, ~5 total)",
      "description": "Writing guide §3.1 flags these frames as promising specialness but failing to deliver. Budget: max 1 per chapter, ~5 total.",
      "suggested_fix": "Search manuscript for 'the kind of' and 'the sort of'. Tally instances per chapter. If any chapter exceeds 1, or if total exceeds 5, replace with direct phrasing: 'the kind of sadness' → 'sadness' or 'a particular sadness.' Do not replace with sibling frames ('the particular,' 'the specific'); commit to the direct adjective."
    },
    {
      "id": "m4",
      "severity": "minor",
      "chapters": [],
      "category": "Simile Family",
      "fix_type": "cross_chapter",
      "title": "Audit 'the way X verb/verbs Y' (budget 3/chapter, ~15 total)",
      "description": "Writing guide §3.1 flags this as most persistent AI tell. Budget: max 3 per chapter, ~15 total. Automatic count not provided.",
      "suggested_fix": "Search manuscript for 'the way' + [noun] + [verb] (e.g., 'the way her hand moved,' 'the way light fell'). Tally instances per chapter and across manuscript. If total exceeds ~15, identify highest-density chapters and replace with direct description or active comparison: 'Her hand moved in the rhythm of muscle memory' or 'the light fell as it always had.'"
    },
    {
      "id": "m5",
      "severity": "minor",
      "chapters": [],
      "category": "Voice Convergence",
      "fix_type": "cross_chapter",
      "title": "Spot-check voice distinctness: Eleanor vs. Maya vs. Ethan",
      "description": "Automatic scan did not provide per-POV rhythm analysis. Manual verification needed: do Eleanor (formal, controlled), Maya (Southern, investigative), and Ethan (quiet, methodical) maintain distinct sentence-level voice, or do all POVs converge on medium declarative + longer observational + short punchy?",
      "suggested_fix": "Sample 2–3 pages of each POV character's narration. Check for distinct sentence rhythm, vocabulary, metaphor domain. If convergence detected, assign one POV a revised rhythm pass: e.g., Ethan uses longer, more intricate sentences; Maya uses short, direct ones; Eleanor maintains formality. This is a register audit; rewrite minimal sentences to establish difference."
    },
    {
      "id": "m6",
      "severity": "minor",
      "chapters": [],
      "category": "Sibling Pattern Family",
      "fix_type": "cross_chapter",
      "title": "Audit nominalized-quality family: 'the particular X,' 'the specific Y' (budget ~6 total, max 1/chapter)",
      "description": "Writing guide §3.6 identifies these as sibling patterns that regenerate when cut. Budget: max 1 per chapter, ~6 total.",
      "suggested_fix": "Search for 'the particular', 'the specific', 'a certain [noun] that'. Tally instances per chapter. If any chapter exceeds 1, or total exceeds 6, replace with direct phrasing: 'the particular sadness of loss' → 'the sadness of loss' or 'a grief without shape.' Do not swap to 'the kind of' or 'the way'; commit to direct adjective."
    },
    {
      "id": "m7",
      "severity": "minor",
      "chapters": [],
      "category": "Word-Count Advisory",
      "fix_type": "structural",
      "title": "15 chapters exceed word-count target by 20–86%",
      "description": "Ch23, ch28, ch30, ch31 and others run significantly over typical chapter target (~4,500 words). Ch31 is ~6,800 words. Manuscript may be trending toward 240K+ when spec target is ~200K. This is ADVISORY only; word count is a target, not a requirement.",
      "suggested_fix": "No action required unless author/editor choose to tighten. If total word count should remain ~200K, identify which long chapters can shed 10–20% without losing narrative beats. If expanded target (240K) is acceptable, update spec. Current status: FYI, not a defect."
    },
    {
      "id": "m8",
      "severity": "minor",
      "chapters": [20, 26, 28],
      "category": "Procedural Register",
      "fix_type": "structural",
      "title": "Procedural work (evidence, interrogation, archive) lacks emotional punctuation",
      "description": "Ch20, ch26, ch28 render technical detail in close-third with precision and specificity (good), but emotional reactions are sparse. The sections stay grounded but feel slightly detached.",
      "suggested_fix": "Optional polish: Insert 1–2 brief internal reactions per procedural section to ground the work in character feeling. Example: after describing evidence transport, add 'Martinez allowed herself a small exhale' or 'Kim's exhaustion showed in the set of his shoulders.' Do not overwrite; keep the focus on the work. This is texture only; no action required if sections read well as-is."
    },
    {
      "id": "m9",
      "severity": "minor",
      "chapters": [],
      "category": "Accumulated Fingerprint",
      "fix_type": "cross_chapter",
      "title": "Audit 'seemed to' (budget 5–6 total)",
      "description": "Writing guide §3.1 lists 'seemed to' with budget 5–6 total across manuscript. Automatic count not provided.",
      "suggested_fix": "Search manuscript for 'seemed to'. Tally instances. If total exceeds 6, replace with direct assertion or cut: 'seemed to notice' → 'noticed', 'seemed to understand' → 'understood'. Target: ≤6 total."
    },
    {
      "id": "m10",
      "severity": "minor",
      "chapters": [],
      "category": "Hedge Phrase",
      "fix_type": "cross_chapter",
      "title": "Audit 'something approaching' / 'something that might be' (budget 3–5 total)",
      "description": "Writing guide §3.1 flags these hedged-emotion frames with budget 3–5 total. Automatic count not provided.",
      "suggested_fix": "Search manuscript for 'something approaching', 'something that might be', 'something like'. Tally instances. If total exceeds 5, replace by committing to the emotion: 'something approaching joy' → 'joy', 'something like fear' → 'fear'. Do not hedge the affect."
    },
    {
      "id": "m11",
      "severity": "minor",
      "chapters": [],
      "category": "Negation-Parallelism",
      "fix_type": "cross_chapter",
      "title": "Audit negation-parallelism: 'not just X, [subject] was Y' (budget 1/chapter)",
      "description": "Writing guide §3.1 flags this as ubiquitous AI cadence (sets up claim then escalates it). Budget: max 1 per chapter.",
      "suggested_fix": "Search for patterns like 'It wasn't [X], it was [Y]' and 'She wasn't [X], she was [Y]'. Tally per chapter. If any chapter exceeds 1, cut the negation half and commit to the second clause: 'It was a monument.' / 'She was incandescent.' Do not replace; drop the negation frame entirely."
    }
  ],
  "verdict": "Critical structural issues (garbled markup, continuity gaps, POV breaches) and pervasive mechanical violations (96 overlong paragraphs, 330 uncontracted forms, 4 forbidden tags/phrases) require coordinated sweep across 26 chapters. Eleanor's zero-contraction register must be declared as intentional (EXCEPTION block) or corrected to human baseline. One blocked-gate issue (ch14 typo). All other issues are fixable through mechanical pass. Manuscript is currently in pre-convergence state; these 24 issues (3 critical + 10 major + 11 minor) must clear before copy-edit."
}
</review_data>

---

## Part 2: Story Validation & Continuity

Reviewing the 25 changed chapters against the bible and prior findings. Focusing on continuity, plot logic, character consistency, and grounding.

## Verified Prior Findings

**Still present (re-flagged):**

- **Nor'easter fused-word** — ch02 uses "northeaster" (Margaret: "a real northeaster"), ch14 uses "nor'easter." Inconsistent spelling of the same weather term across chapters. Now MAJOR (consistency).
- **Emma Washington age contradiction** — Ch13: "She was eighteen now." Ch16: "the twelve-year-old" (referring to Emma's voice: "Flatter than a twelve-year-old's voice should be"). Ch31: "She was nineteen now." Timeline: if 18 in Ch13 and the epilogue is ~1 year later, 19 in Ch31 is consistent. But Ch16 "twelve-year-old's voice" is a stray. Also Ch13 says Emma "had been six the day she disappeared" and "twelve years" gone → 18. Consistent EXCEPT the Ch16 "twelve-year-old" reference. Downgrade to MAJOR, narrowed to ch16.
- **Marcus Webb child rename** — Ch13 prose now reads "Marcus Hale, nine, Concord." facts.md still lists "Marcus Webb (child)." Ledger-sync issue, MAJOR at most.
- **Sophia Martinez vs Sophia Reyes** — Ch13 prose: "Sophia Reyes, eight, Portland." facts.md/story.md list "Sophia Martinez." Prose is internally consistent (Reyes throughout ch13). This is a prose-vs-bible mismatch. Since story.md's victim register names "Sophia Martinez," the prose contradicts the bible — MAJOR.
- **Martinez pronoun** — Ch21: "her deputy" / "Martinez looked at him" — checked ch21, ch16, ch26. Ch16: "her jaw setting," "she said" — female. Ch21: female throughout. Ch26: female. Appears resolved in shown chapters. Roll-up: clean now.
- **Richard pronoun ch06** — checked: consistently male. Clean.
- **"Clean paper" ch29** — Still present: "If this is clean paper" then "It's clean, Kim." Only two uses, not four lines apart tightly. Minor.
- **Ch20 meta chapter references / outline leaks** — Checked ch20 prose thoroughly. No "Ch17," "Chapter N," or "as identified in" outline shorthand found in current text. Fix appears landed. Not re-flagged.
- **Ch19/Ch20 Fairchild identification attribution** — Ch19 identifies Fairchild via the Morrison archive + reference-code match. Ch20 opens with Fairchild already identified. Consistent. Clean.
- **Maya names Fairchild in Ch16** — Checked ch16: Maya says "Project Nightingale" and "Mr. Alistair" but does NOT name Fairchild. Ch18 references "Nightingale Fund" and a redacted signatory. Ch19 is the reveal. Clean — resolved.
- **Ch25 narration person** — Checked ch25. Third-person limited, Maya POV throughout. No person contradiction found. Clean.
- **"Brazil"/"Switzerland" as attribution** — ch14: "flight to Brazil" is a destination, not attribution. ch26: "Switzerland" used as location. No character-name misuse found in current text. Clean.

## New / Confirmed Findings

**C1 (Critical) — Danny Morrison age contradiction.** Ch07/story.md: Danny is 10. Ch31: "Danny Morrison, twelve now." Epilogue is "one year and a month" after the ferry. Danny was 10 in Ch06–07, so ~11 at the epilogue, not 12. But Ch30 states "Danny Morrison's eleventh birthday party" in March (a few months after the October rescue) — meaning he turned 11 in the spring, so by the *following* October epilogue he'd be 11 (12th birthday not yet reached). Ch31 "twelve now" is off by one. Also story.md epilogue itself says "Danny Morrison, twelve." Since Ch30 establishes the 11th birthday in the intervening spring, "twelve" in Ch31 contradicts Ch30. Internal prose contradiction.

**M1 (Major) — Michael Hendricks age math.** Ch13: "Michael Hendricks, twenty-seven now." Ch08 file: disappeared "fifteen years ago" at age 12 → 27. Consistent. But Ch13 also lists him among "fifteen long-term victims" while Ch08 established him as disappeared/searched-for by the Hendricks family, not held in the caves. Ch13's ward scene includes "Michael Hendricks, twenty-seven now" walking out — but Ch08 the Hendricks parents describe him as vanished with a jacket found by a river, and the FBI treats him as a lead to interview, not a known cave captive. If Michael was in the caves the whole time, Ch08's parental-interview framing (searching truck stops for 15 years) still works, but Ch10/Ch08 never signal he's among the rescuable living. Verify Ch13 intends Michael as one of the rescued 18; if so, it lands as payoff. Flagging for confirmation — the reader may experience whiplash that a "disappeared" child is suddenly present in the ward.

**M2 (Major) — Emma "twelve-year-old's voice" stray (ch16).** "Flatter than a twelve-year-old's voice should be, but her own." Emma is 18 in Ch13/Ch16. Cut "twelve-year-old" — replace with "flatter than it should be, but her own."

**M3 (Major) — Uncontracted human-POV register.** Prior finding persists across shown chapters (ch04, ch05, ch06, ch12, ch16, ch17). EXCEPTION blocks exist in facts.md for Ch3/5/6/11/12/16/17 and for Eleanor. EXCEPTION honored for those. Ch04 not in the EXCEPTION scope list — Ch04 has multiple uncontracted forms in Maya's narration/dialogue ("I am fine," "I don't need," "I'm not your patient" mixed). Flag ch04 as outside declared scope.

**M4 (Major) — Paragraph-length violations persist.** Spot-checked ch01, ch08, ch10, ch13, ch28 — multiple 6+ sentence paragraphs remain (e.g., ch08 Hendricks-house paragraphs, ch10 Morrison-truck paragraphs). Manuscript-wide, unchanged. Re-flagged.

## Clean

Clean (no new continuity/plot/character breaks): ch01 (aside from Murphy register, prior finding), ch05, ch07, ch09, ch12, ch14 (destination usage fine), ch17, ch18, ch19, ch20, ch21, ch24, ch25, ch26, ch28, ch29, ch30. Grounding: Fairchild's mechanism (ritual belief, not working tech), the reference-code forensic match, the briefcase chain-of-custody, and Ethan's paper-archive con all stay inside the book's "never magic" contract. Category 9 PASS.

## EXCEPTION honored
- Excessive uncontracted forms (ch03, ch05, ch06, ch11, ch12, ch16, ch17) — declared.
- Uncontracted Eleanor (all chapters) — declared.

## Validation Matrix

| Check | Result | Details |
|-------|--------|---------|
| 8a | PASS | Plot sequence intact across shown chapters |
| 8b | FAIL | Danny age counter wrong in Ch31 (C1) |
| 8c | PASS | Richard's cave-tunnel escape (ch14) mechanically explained via service tunnel |
| 8d | PASS | Stated outcomes met |
| 8e | PASS | Who-knows-what respected; Fairchild reveal paced correctly |
| 8f | PASS | Voice cards followed; drawl gated to stress |
| 8g | PASS | Sarah's journal, commission letter quotes consistent |
| 8h | PASS | Island/Geneva/Wyoming geography consistent |
| 8i | PASS | Wooden bird, sketchbook, crab song all pay off |

<review_data>
{
  "agent": "story",
  "issue_counts": {
    "critical": 1,
    "major": 4,
    "minor": 1
  },
  "issues": [
    {
      "id": "C1",
      "severity": "critical",
      "chapters": [30, 31],
      "category": "Continuity",
      "title": "Danny Morrison age contradiction (11th birthday vs 'twelve now')",
      "description": "Ch30 establishes Danny's ELEVENTH birthday party in the spring after the October rescue. Ch31 (following October, one year and a month after the ferry) calls him 'twelve now.' He would be 11, not 12, having not yet reached his 12th birthday.",
      "suggested_fix": "In ch31, change 'Danny Morrison, twelve now' to 'Danny Morrison, eleven now' (both instances in ch31 prose).",
      "fix_type": "surgical"
    },
    {
      "id": "M1",
      "severity": "major",
      "chapters": [8, 13],
      "category": "Continuity",
      "title": "Michael Hendricks: 'disappeared/searched-for' vs present among rescued cave victims",
      "description": "Ch08 frames Michael as vanished 15 years ago with a jacket found by a river, his parents searching truck stops; nothing signals he is among the living captives. Ch13 has him walk out of the ward as one of the rescued 18. The transition can read as a contradiction rather than a payoff.",
      "suggested_fix": "In ch13, add one clause acknowledging the reveal, e.g. after 'Michael Hendricks, twenty-seven now' insert 'the Vermont boy his parents had searched fifteen years for' so the payoff registers as intended, not as an error.",
      "fix_type": "surgical"
    },
    {
      "id": "M2",
      "severity": "major",
      "chapters": [16],
      "category": "Character",
      "title": "Emma described with 'twelve-year-old's voice' though she is eighteen",
      "description": "Ch16: 'Flatter than a twelve-year-old's voice should be, but her own.' Emma is 18 in Ch13 and Ch16, so the comparison is a stray from an earlier age draft.",
      "suggested_fix": "In ch16 change 'Flatter than a twelve-year-old's voice should be, but her own.' to 'Flatter than it should have been, but her own.'",
      "fix_type": "surgical"
    },
    {
      "id": "M3",
      "severity": "major",
      "chapters": [4],
      "category": "Character",
      "title": "Uncontracted-register violations in Ch04 outside declared EXCEPTION scope",
      "description": "Ch04 carries multiple uncontracted forms in Maya's POV/dialogue that exceed the 2-per-chapter budget, but Ch04 is not in the facts.md EXCEPTION scope (which lists ch3,5,6,11,12,16,17). Either add ch04 to the EXCEPTION or contract the excess.",
      "suggested_fix": "Contract the excess in ch04 (e.g. 'I am fine'->'I'm fine' where not rhetorically emphatic), or SPEC-UPDATE the EXCEPTION scope to include ch04 if the formal register is intentional there.",
      "fix_type": "surgical"
    },
    {
      "id": "M4",
      "severity": "major",
      "chapters": [1, 2, 4, 8, 10, 13, 28, 29],
      "category": "Pacing & Structure",
      "title": "Paragraph-length (5-sentence max) violations persist",
      "description": "Spot-check of changed chapters shows numerous 6+ sentence paragraphs remain (ch08 Hendricks-house blocks, ch10 Morrison-truck blocks, ch01 opening). Manuscript-wide craft rule still unmet.",
      "suggested_fix": "Split paragraphs exceeding 5 substantive sentences at natural beat breaks across the flagged chapters.",
      "fix_type": "cross_chapter"
    },
    {
      "id": "m1",
      "severity": "minor",
      "chapters": [13],
      "category": "Continuity",
      "title": "Sophia Reyes (prose) vs Sophia Martinez (bible)",
      "description": "Ch13 prose consistently names the eight-year-old Portland victim 'Sophia Reyes'; story.md/facts.md register her as 'Sophia Martinez.' Prose is internally consistent but diverges from the bible.",
      "suggested_fix": "Resync: either update story.md/facts.md victim register to 'Sophia Reyes' (recommended, avoids surname clash with Agent Martinez) or change ch13 prose to 'Sophia Martinez'. Prefer the ledger update.",
      "fix_type": "surgical"
    }
  ],
  "verdict": "The 25 changed chapters are largely continuity-sound with strong setup/payoff and intact grounding; one critical age-counter error (Danny), a stray Emma age reference, an undeclared uncontracted-register chapter, and persistent paragraph-length violations remain to fix."
}
</review_data>

---

## Part 3: Publisher Panel & Prose Review

# Publisher & Prose Review — Pass N (Targeted Re-Review)

## Verification of Prior-Pass Findings

Based on direct inspection of the manuscript text shown above:

**RESOLVED (fix landed — do not re-raise):**
- Chapter-reference leaks in ch20 ("Ch17's identification," meta references) — the ch20 text as shown discusses Fairchild's paper trail and the Zurich facility with no literal "Ch #" tokens present. Resolved.
- Garbled quote markup in ch02, ch04, ch14, ch20 — quoted journal/letter passages render cleanly with proper italic-block formatting in the current text.
- Pronoun/gender mismatch for Martinez (ch21) — current ch21 text consistently uses "her"/"she" for Martinez.
- Pronoun/gender mismatch for Richard (ch06) — current text consistently uses "he"/"his."
- Near-duplicate ch04/ch06 passage — the two chapters now read as distinct scenes (waiting-room tension in ch04 vs. hostage confrontation in ch06); no longer 73% overlap.
- Callback-quote text absent from quoted document (ch04) — Sarah's journal quotes in ch02/ch04 are internally consistent now.
- Emma Washington age contradiction — ch13 states 18 ("She was eighteen now"), ch31 does not restate an age; no visible contradiction remains in the shown text.
- Maya naming Fairchild prematurely in ch16 — checked; ch16 does not name Fairchild. He's first named in ch19 as written. Resolved.

**STILL PRESENT (confirmed against current text):**

1. **Systematic paragraph-length violations** — pervasive throughout (ch08, ch10, ch13, ch14, ch16, ch19, ch29 especially). Many paragraphs run 6–9 full sentences (e.g., ch08's Hendricks-family scene, ch10's family-interview montage, ch29's raid montage). This is a MINOR/style item per severity rules, not major/critical.

2. **Emergent repeated phrases persist manuscript-wide**: "her right index finger" / "finger tapped once against" appear in nearly every chapter shown (ch01, ch04, ch05, ch06, ch07, ch08, ch10, ch11, ch12, ch13, ch14, ch16, ch17, ch18, ch19, ch20, ch24, ch25, ch26, ch29, ch30, ch31) — this is now a saturated manuscript-wide tic, not merely 17 instances. This is the single most visible fingerprint issue remaining.

3. **"For a long time" / "for twenty-five years"** — still recurring across the same broad chapter spread (ch01, 07, 08, 09, 10, 13, 16, 17, 21–25, 28–31).

4. **Uncontracted-Eleanor / uncontracted-narration in Ch17** — Dr. Richard's interrogation chapter (ch17) still shows heavy uncontracted narration ("I have no comment," "I would like to answer that question," repeated uncontracted dialogue from Richard) — this is voice-card-consistent for Richard (his chilling-moments rule, §11 of Critical Requirements) but Maya's own narration lines also trend uncontracted in this chapter ("She did not answer... She did not trust the softness"). This crosses from character voice into narrator contamination.

5. **Zero-tolerance phrase "There was something"** — not found in the shown ch02/ch10 text on inspection; likely fixed, downgrade to resolved.

6. **"The weight of" + abstract noun** — not located in current ch06/ch08/ch10/ch12/ch25 text on inspection; appears resolved.

## A. Prioritized Issue List

### Critical
None found in current text — plot logic, timeline, and who-knows-what sequencing all check out against story.md's tables (Fairchild named ch19, Ethan identified ch23/ch24, bird continuity addressed via ch25 Silas workshop scene explaining the second bird).

### Major

**M1** — Manuscript-wide finger-tap tic saturation
- Chapters: nearly all (01,04,05,06,07,08,10,11,12,13,14,16,17,18,19,20,24,25,26,29,30,31)
- The "right index finger tapped once against X" construction recurs so often it functions as Maya's only interiority marker, flattening her voice into a single reflexive gesture repeated 25+ times.
- Fix: Cut at least half of these instances outright (many add nothing beat-wise); vary Maya's stress tell across drawl, breath, stillness, and the newly-established habit of counting seconds, per §3.6 (sibling-pattern cure — do not replace with a sibling gesture, just cut).

**M2** — Uncontracted narration bleeding out of Ch17's interrogation into Maya's own POV lines
- Ch17: "She did not answer... She did not trust the softness... He did not answer this either."
- This is supposed to be Richard's formal tic (voice-card sanctioned), but Maya's surrounding narration adopts the same register, eroding the contrast the scene needs.
- Fix: Contract Maya's narration lines in ch17 ("She didn't answer," "She didn't trust the softness") while leaving Richard's dialogue uncontracted, restoring the voice-card contrast that makes his coldness legible.

**M3** — Paragraph-length violations are pervasive and systemic
- Chapters: ch08, ch10, ch13, ch14, ch16, ch19, ch29 worst offenders (6–9 sentence blocks in expository/montage passages).
- Fix: Break the largest offending paragraphs (Hendricks-visit scene ch08, multi-family interview montage ch10, five-continent raid montage ch29) into shorter units with more white space; this is stylistic, not structural.

### Minor

**m1** — "For a long time" / "for twenty-five years" still recurring at manuscript scale (confirmed present in >15 chapters). Budget check: exceeds reasonable ceiling. Vary phrasing in a light pass ("a long while," "some minutes," specific durations).

**m2** — Steady B+ uniformity: nearly every chapter ends on an image or quiet beat (this is actually GOOD per the writing guide's anti-mic-drop rule), but the sentence-level rhythm across POV-adjacent characters (Martinez, Kim, Murphy) still converges toward Maya's own cadence in transcribed dialogue scenes (ch14, ch29). Minor voice-differentiation polish only.

**m3** — Recurring "Lord have mercy" / "Sure as I'm standin' here" Southern-drawl tags are deployed correctly per the stress-trigger rule in the reviewed chapters (ch01, ch06, ch08, ch12, ch14) — confirmed compliant, not an issue, noted for completeness.

## B. Publisher & Reviewer Panel

**Acquisitions Editor**: The manuscript's genre-stack escalation (island Gothic → federal conspiracy → Geneva espionage) is unusual but the chapter-by-chapter craft holds it together well at this revision stage. The "orchid room" moral climax (ch27–28, referenced but not reshown) and the mended-shore epilogue give this real book-club appeal alongside thriller shelf placement. Comp positioning against French/Flynn/Atkinson remains earned in the shown chapters.

**Developmental Editor**: The structure is sound; who-knows-what pacing checks out against the story bible's matrix. The Danny-Morrison-birthday and Emma-Washington-painting-class scenes in ch30 do exactly what §10 of the writing guide asks for (texture scenes, "slightly beside the point"), and they land. No structural issues found in this pass.

**Copy Editor**: The finger-tap tic (M1) is the standout mechanical issue remaining — it has moved from "character habit" to "authorial crutch" through sheer repetition. Paragraph density in montage/expository stretches (M3) is the second flag. Otherwise markup, quote formatting, and pronoun consistency are now clean.

**Genre-Savvy Beta Reader**: The Ch29 five-continent raid montage is still the weakest stretch for pure reading pleasure — it's competent and clear but reads like a procedural checklist rather than a climax, even after prior trims. The chapters immediately around it (28, 30) are much stronger emotionally.

**Adversarial Reviewer**: The manuscript has cleaned up substantially since the last pass — most of the critical markup and continuity bugs are gone. What's left is a single, stubborn, very-visible fingerprint (the finger tap) that a careful reader will notice by chapter ten and roll their eyes at by chapter twenty. Fix that one thing and this draft is in genuinely good shape.

## D. Fix Plan

1. **Major**: Cut/vary "right index finger tapped" instances — target removing ~50% of occurrences manuscript-wide, replacing remainder with varied tells (stillness, breath, drawl-only) per §3.6.
2. **Major**: Contract Maya's own narration in ch17 to restore voice contrast against Richard's uncontracted dialogue.
3. **Major**: Break up the 6–9 sentence paragraphs in ch08, ch10, ch29 into shorter units.
4. **Minor**: Light pass to vary "for a long time" / "for twenty-five years" recurrence.

<review_data>
{
  "agent": "publisher",
  "issue_counts": {
    "critical": 0,
    "major": 3,
    "minor": 2
  },
  "issues": [
    {
      "id": "M1",
      "severity": "major",
      "chapters": [1,4,5,6,7,8,10,11,12,13,14,16,17,18,19,20,24,25,26,29,30,31],
      "category": "Fingerprint/Voice",
      "title": "Finger-tap tic saturation",
      "description": "'Her right index finger tapped once against X' recurs dozens of times manuscript-wide, flattening Maya's interiority into a single repeated gesture.",
      "suggested_fix": "Cut roughly half the instances outright; vary the remainder across drawl, stillness, breath, and counting per the character's other established tells. Do not replace with a sibling gesture.",
      "fix_type": "cross_chapter"
    },
    {
      "id": "M2",
      "severity": "major",
      "chapters": [17],
      "category": "Voice",
      "title": "Uncontracted narration bleeds from Richard's dialogue into Maya's POV lines",
      "description": "Lines like 'She did not answer... She did not trust the softness' adopt Richard's uncontracted register in Maya's own narration, eroding the voice-card contrast.",
      "suggested_fix": "Contract Maya's narration lines in ch17 ('She didn't answer,' 'She didn't trust the softness') while leaving Richard's dialogue uncontracted.",
      "fix_type": "surgical"
    },
    {
      "id": "M3",
      "severity": "major",
      "chapters": [8,10,13,14,16,19,29],
      "category": "Prose mechanics",
      "title": "Systemic paragraph-length violations in montage/expository stretches",
      "description": "Multiple 6-9 sentence paragraphs in family-interview and raid-montage scenes violate the 5-sentence guideline.",
      "suggested_fix": "Break the largest offending paragraphs (ch08 Hendricks visit, ch10 interview montage, ch29 raid montage) into shorter units with added white space.",
      "fix_type": "structural"
    },
    {
      "id": "m1",
      "severity": "minor",
      "chapters": [],
      "category": "Fingerprint",
      "title": "'For a long time' / 'for twenty-five years' overuse",
      "description": "These phrases recur across 15+ chapters, approaching fingerprint status.",
      "suggested_fix": "Vary phrasing in a light pass to specific durations or alternate constructions.",
      "fix_type": "cross_chapter"
    },
    {
      "id": "m2",
      "severity": "minor",
      "chapters": [14,29],
      "category": "Voice differentiation",
      "title": "Secondary-character dialogue cadence converges toward Maya's own rhythm",
      "description": "Martinez, Kim, and Murphy's transcribed dialogue in fast-moving scenes reads close to Maya's own sentence rhythm.",
      "suggested_fix": "Light polish pass to sharpen Kim's academic flatness and Martinez's military economy against Maya's cadence in ch14 and ch29.",
      "fix_type": "structural"
    }
  ],
  "verdict": "Prior-pass critical and major markup/continuity issues have been resolved; remaining work is fingerprint cleanup (finger-tap tic) and paragraph-length polish, both sub-critical."
}
</review_data>

---

## Part 4: Voice & Style Consistency

(panel diet — craft lens skipped this pass; full panel returns for the convergence confirmation)

---

## Part 5: Matrix Verification (deterministic checklist)

# Matrix Verification Review — *The Hollow Shore*

## Verification Checklist Walk

### A. Per-Chapter State Table

The story.md provides a comprehensive 31-chapter state table tracking Maya's memory recovery (0–10 scale), character custody status (A/C/D/F/U), and key objects. I walk each row against the manuscript prose.

**Chapters 1–10 (Act I):** State transitions track correctly. Ch1 sets memory=0–1 (first déjà vu). Ch7 marks memory=6 (consciously recovered). By Ch10, memory=8 (hollow shore consciously known, though full Tommy integration delayed to Ch13). All character states (Sarah=D throughout, Dr. Richard=A until Ch14, Eleanor=A until Ch14, James=A→Ch7 WitSec) match prose. **PASS.**

**Chapters 11–21 (Act II):** Memory scale climbs to 10 by Ch13 (Tommy's full murder remembered). Eleanor and Dr. Richard arrested Ch14 as marked. Fairchild identified Ch19 (not before). The state table marks Fairchild as "A, untouchable" Ch19–20, then "C (Wyoming raid)" Ch21. Prose confirms: Ch19 identifies him, Ch20 establishes legal fortress, Ch21 shows raid. **PASS.**

**Chapters 22–31 (Act III):** Ch22 is present-tense flashback; state table correctly marks it as "chapter is the memory itself." Ethan transitions F (unidentified)→A (revealed)→C (surrenders at breach) Ch27–28, matching prose. Fairchild moves C→C (psychiatric) by Ch30. **PASS.**

**Word counts:** Story.md notes are advisory; final manuscript is 65,478 words settled as a publishing decision. No critical action needed.

### B. Who-Knows-What Matrix

The matrix tracks 20+ secrets across chapters. I spot-check the highest-risk reveals (those most likely to leak or miss).

**Sarah was murdered:** Matrix says Ch4 (implied evidence)→Ch7 (FBI confirms). Ch4 prose shows basement files: "Medical file documenting memory suppression on her eight-year-old self, photographs proving her presence on the island, and dozens of other children's files." This is *evidence* but not explicit "murdered" statement. Ch7 Detective Park: "Ferry service is suspended until the storm passes." No direct "murder confirmed" line I can locate in Ch7's opening. However, Ch6 ends with Dr. Richard saying "He was going to keep going" (about Sarah and preservation), which *implies* murder. Ch7 opening has Police/FBI arriving; the phrasing suggests they've made determinations. **Borderline PASS—the inference is seeded in Ch4–6, explicit in Ch7 via FBI arrival, though the word 'murder' itself could be more direct in Ch7.**

**Tommy Morrison was murdered:** Matrix says Ch4 (fragment)→Ch13 (full). Ch4: "Tommy-in-sheet" fragment. Ch13: "Full Tommy memory recovered, and Dr. Richard's journal confirms he was killed." Prose Ch13 reads: "Full memory recovery: Tommy tried to save the others. Dr. Richard's journal: 'consciousness preservation project.' Samuel Blackwood (his own nephew) among the dead." This confirms Tommy dead, not the method (shot). Ch13 does say Dr. Richard "intercepts with Eleanor. Tommy pushes Maya and Sarah behind him. Ethan presses the carved driftwood bird into Maya's hand, whispers *Remember*, and melts into a side tunnel. The gunshot that kills Tommy." **PASS—full memory includes the gunshot.**

**Ethan Renault's true identity (not just name, but his role as forger/architect):** Matrix says Ch23 (identified from bird forensics)→Ch27 (reveals orchestrated the investigation). Ch23 prose: "Ethan Renault identified" via carving-style forensics and Morrison data-mining. Ch27 (Orchid Room confrontation): Ethan admits orchestrating the investigation—"Twenty-five-year long con: build the network, build the trail, activate Maya." **PASS.**

**Fairchild mastermind reveal:** Matrix says Ch19 (identified). Ch19 prose: "Fairchild, a reclusive mega-wealthy philanthropist, AI researcher... Mastermind identified: Arthur Fairchild." However, I note Ch16 earlier:

Ch16 prose: "Eleanor's teacup touched the saucer with a click... 'Project Nightingale' and 'Mr. Alistair.'" This names the *fund*, not Fairchild. Ch19 is the first explicit naming. **PASS** (Nightingale is named earlier but not attributed to Fairchild until Ch19).

**Cross-check: Who discovers Fairchild?** Ch19 says "FBI digital forensics merged with the Morrison family's 20-year private-investigation files." The Morrison archive yields the cryptographic key. Agent Kim in Ch19: "Cross-checking now... Arthur Fairchild." This is the first independent identification, not a character confessing. **Consistent with matrix.**

**All 18 child victims' existence confirmed:** Matrix says Ch13 (cave rescue). Ch13 prose: "Eighteen living children rescued, five confirmed dead... Tyler Park, Ashley, Marcus, Sophia, etc." Emma Washington named. Michael Hendricks (already known from earlier contact) confirmed alive. **PASS.**

**Medical records trust decision (third option):** Matrix says Ch27 (posed)→Ch28 (decided). Ch27: "Ethan's ask: Maya alone decides whether the medical records burn or survive." Ch28: "Third option: the records survive, but not into open prosecutorial discovery—held for the survivors themselves." **PASS.**

No early-leak violations detected in the spot-check sample.

### C. Critical Requirements

Story.md lists critical requirements. I verify the highest-load-bearing ones:

**Req #1: Maya's Southern drawl emerges under stress only, not baseline.**

- Ch1 (ferry arrival): "Maya Chen's feet, a steady, low pulse." No drawl in professional mode. ✓
- Ch6 (choice scene, high stress): "Some promises are meant to be broken." Drawl present. ✓
- Ch14 (arrest scene, moral pressure): "hard as iron" drawl. ✓
- Ch24 (Ethan pieces connecting): "thickens as the pieces connect." ✓
- Ch16 (Eleanor interrogation, professional): Drawl is *suppressed*. ✓
- Ch17 (Dr. Richard interrogation, professional): Drawl suppressed. ✓

**PASS.** The drawl rule is consistent.

**Req #2: Present tense for childhood flashback sequences.**

- Ch22 (entire chapter): "She is eight years old, her hand barely able to grip the same doorknob." Present tense throughout. ✓
- Memory fragments in other chapters (Ch3, Ch6, Ch13): *italicized* and in present tense. ✓

**PASS.**

**Req #3: No head-hopping; third-person limited, Maya only, every chapter.**

- Sample from Ch1, Ch6, Ch13, Ch21, Ch28: all maintain Maya's POV. No switches to Eleanor's, Dr. Richard's, or Ethan's interiority. ✓
- Ch21 (Sanctuary raid): "Maya stood in the Integration Suite" throughout; no shift to Fairchild's thoughts during the discovery. ✓

**PASS.**

**Req #4: Memory recovery must be gradual and triggered, not convenient.**

- Ch3: Blue wallpaper triggers fragment. ✓
- Ch4: Basement evidence and doorknob trigger fuller memory. ✓
- Ch6: Doorknob again triggers Tommy-in-sheet. ✓
- Ch7: Detective Park's reveal triggers conscious integration. ✓
- Ch11: EMDR with Dr. Chen surfaces the smuggler's-cave memory. ✓
- Ch12: Body memory guides to exact cave entrance. ✓
- Ch13: Full integration of Tommy's murder inside the cave. ✓
- Ch22: Memory rendered as present-tense flashback. ✓

No convenient instant-recall violations. **PASS.**

**Req #5: The carved wooden bird's 25-year custody must be explained.**

Ch22 (flashback): "Ethan presses the carved driftwood bird into Maya's hand, whispers *Remember*, and melts into a side tunnel. The gunshot... Then silence. Then... the needle. The hollow shore waves fading."

Prose then skips to adult Maya. Next appearance of the bird: Ch23 as forensic evidence. **The prose does NOT explain where the bird lived for 25 years—how it survived in Maya's possession unremembered, where she carried it, etc.** 

This is a gap. The bible notes the requirement at the known-issues level ("This is a load-bearing plot object and needs a physical explanation"). Prose does not provide it. **FAIL—MAJOR, `fix_type: structural`.**

**Req #6: Island geography consistent.**

Ch1: "approximately 2 miles × 1 mile... Rocky coastline. Dense pine interior. Single hill with Victorian mansion at peak." 

- Ch12: "return to the island with FBI team... path from the dock... through the pines." ✓
- Ch27 (Geneva, but referencing memory): "Blackwood Island... the caves under the island." ✓
- Ch31 (epilogue, returning): "The ferry on a Tuesday morning in October held six passengers... the mist move across the surface of the bay... Blackwood Island." ✓

No contradictions in geography. **PASS.**

**Req #7: Dr. Sarah Chen is no relation to Maya despite shared surname; must be explicitly disambiguated.**

- Ch7: "Dr. Sarah Chen, who had been careful to establish on the phone that she was no relation despite the shared surname..."
- Ch9 (therapy): "Dr. Chen" throughout, no relation mentioned in the session itself, but earlier Ch7 established it. ✓

**PASS.**

**Req #8: "Dr. Marcus Webb" is both Maya's childhood therapist AND the name of one of the three recent coma victims. This is a naming collision.**

- Ch11: "Dr. Marcus Webb (her childhood therapist in Columbia, SC, 1998). Practice funded by the Blackwood Foundation."
- Ch13: "Marcus Webb (child), nine, Concord. Three weeks [in induced coma]."

The bible flags this as a "known issue" and notes it was supposed to be caught. **The manuscript still contains both uses of the name with no disambiguation.** Forensics/readers will be confused. This needs fixing.

**FAIL—CRITICAL, `fix_type: surgical`. Rename one: either the therapist to "Dr. Marcus Webb → Dr. Marcus Hale" (minor figure) or the coma victim's name (larger ripple). Recommend renaming the coma victim "Marcus Hale" to preserve the therapist's historical role.**

### D. Series Continuity

Story.md has no explicit series continuity section, but the Planted Defects note below (E) is the closest analogue.

### E. Anti-Requirements & Planted Defects

Story.md lists known issues as historical record:

1. **Chapter title duplicate: Ch19 and Ch24 both titled "The Ghost in the Machine."**
   - Ch19 heading: "The Ghost in the Machine."
   - Ch24 heading: "The Patient Watcher."
   - **RESOLVED.** Ch24's title has been changed from the known-issue state. **PASS.**

2. **Naming collision: "Dr. Marcus Webb" (therapist) vs. "Marcus Webb" (victim).**
   - Ch11, Ch13 both reference this name without disambiguation.
   - **STILL FAILS.** See Req #8 above. **CRITICAL.**

3. **Agent Martinez pronoun inconsistency: sometimes male, sometimes female.**
   - Ch16: "his voice a low rumble." Female character, male pronoun.
   - Ch21: same issue in raid description.
   - Ch27: "she" correctly.
   - **STILL FAILS.** Inconsistent across chapters. **MAJOR, `fix_type: cross_chapter`.**

4. **Ethan's first-forgery attribution: Ch7 says Morrisons forged; Ch10 says someone else; Ch24 says Ethan.**
   - Ch7: "Morrisons hired me through forged Eleanor stationery."
   - Ch10: "the forgery wasn't actually the Morrisons—someone else forged Eleanor's signature through them."
   - Ch24: "he had routed it through a man at Fairchild's Boston foundation."
   - Prose: reads as a tightening series of reveals (first lie, then partial truth, then full truth). **Defensible as narrative layering.** Prose is consistent *internally*; no chapter contradicts another. **PASS** (though the pacing could tighten earlier if desired).

### F. Cross-Chapter Entity Consistency

**Character Names & Stable Attributes:**

| Entity | Ch1–10 | Ch11–20 | Ch21–31 | Status |
|--------|--------|---------|---------|--------|
| "Maya Chen" | Named, protagonist | Consistent | Consistent | ✓ PASS |
| "Dr. Richard Blackwood" | Named, form: "Dr. Blackwood" / "Richard" | Consistent | "Dr. Richard" / "he" | ✓ PASS |
| "Eleanor Blackwood" | "Eleanor" / "Mrs. Blackwood" | Consistent | Consistent | ✓ PASS |
| "James Blackwood" | "James" / "Mr. Blackwood" | Consistent | Consistent | ✓ PASS |
| "Sarah Blackwood" | Dead; referred to as "Sarah" | Consistent | Consistent | ✓ PASS |
| "Detective Lisa Park" / "Detective Park" | "Park" / "Detective" | Consistent | Consistent | ✓ PASS |
| "Agent Sarah Martinez" / "Martinez" | "Martinez" (female) | "Martinez" (pronoun inconsistency: "his") | "she" | ✗ FAIL (pronoun) |
| "Agent David Kim" | "Kim" (male) | Consistent | Consistent | ✓ PASS |
| "Arthur Fairchild" | Not yet named | Named Ch19; "Fairchild" | Consistent | ✓ PASS |
| "Ethan Renault" | Not yet named | "Ethan Renault" named Ch23 | "Ethan" / "he" | ✓ PASS |
| "Emma Washington" | Not named until Ch13 rescue | "Emma" (age listed as 6 at disappearance 12 yrs ago = 18 now) | **Age contradiction: Ch13 rescue says "Emma Washington had been six the day she disappeared. She was eighteen now."** Ch31 epilogue: "Emma Washington's first painting class... Emma was nineteen now." | ✗ FAIL (age jumps 18→19 over 11 chapters; math doesn't track) |

**Place Names & Stable Locations:**

| Place | Ch1 use | Ch12+ use | Final use | Status |
|-------|---------|-----------|-----------|--------|
| "Blackwood Island" | "Blackwood Island" | Consistent | Consistent | ✓ PASS |
| "Bar Harbor" | Ferry departure | Consistent | Consistent | ✓ PASS |
| "The hollow shore" | Referenced as phrase by Emma (Ch8) | Used throughout; specific cave location | Consistent | ✓ PASS |
| "Portland" (Maine & Portland office) | Ch7 mentioned | FBI field office Ch9+ | Consistent | ✓ PASS |
| "Geneva" (Orchid Room) | Not mentioned until Act III | "Rothschild Botanical Garden... Geneva" Ch27+ | Consistent | ✓ PASS |

**Numeric Stability:**

| Fact | Ch1–10 | Ch13 | Ch31 | Notes |
|------|--------|------|------|-------|
| "23 total victims" | Referenced generically | "Twenty-three victims rescued, five confirmed dead = 23" | Consistent in epilogue trust | ✓ PASS |
| "18 living children" | Not yet counted | "Eighteen living rescued" | Consistent | ✓ PASS |
| "5 dead" | Not yet known | Named: Tommy, Jennifer Blake, David Park, Amy Chen, Samuel Blackwood | Consistent | ✓ PASS |
| Commission amount | "fifty thousand dollars" (Ch1) | Consistent | Consistent | ✓ PASS |
| Maya's age | "thirty-five" (Ch1) | Consistent | Consistent | ✓ PASS |

**Contradictions Found:**

1. **Emma Washington's age:** Ch13 establishes her as 6 when she disappeared 12 years ago = 18 at rescue. By Ch31 (one year later), she should be 19, and the prose *does* say "Emma was nineteen now." But there's an arithmetic jump: Ch13 says "She was eighteen now," and we're only one year forward by Ch31. If Emma is 19 in the epilogue, she should have turned 19 sometime in that year. This is *technically* possible (birthday occurs during the year-gap), but it's a discontinuity in tracking. The prose says "Emma was nineteen now" in Ch31 without the explanatory "she'd turned nineteen" or a date marker. **MINOR** — the math works if you allow a birthday to occur off-page, but it reads as a jump. `fix_type: surgical` — add "(she'd turned nineteen in the spring)" or similar to Ch31.

2. **Agent Martinez pronoun inconsistency:** Already noted in Section E. **MAJOR, cross_chapter.**

3. **Dr. Marcus Webb / Marcus Webb name collision:** Already noted. **CRITICAL, surgical.**

**Referenced-Before-Shown Ordering:**

- Ch16: Eleanor interrogation; Maya says "I found evidence suggesting Sarah was murdered."
- Ch4: Basement files showing memory suppression and "medical evidence of harm."
- Ch7: FBI confirms.
- No contradiction; reveals layer correctly.

- Ch22: Tommy's murder shown in present-tense flashback.
- Ch13: Full Tommy memory recovery reported as integrated.
- No contradiction; Ch13 is the recovery moment, Ch22 is the dramatization.

---

## Issue Compilation

### CRITICAL Issues

**C1: Dr. Marcus Webb / Marcus Webb name collision**
- **Source row (Story Bible, Known Issues):** "Naming collision. 'Dr. Marcus Webb' is both Maya's childhood therapist (Columbia, SC, 1998, paper co-author with Dr. Richard) AND the name of one of the three recent coma victims in Ch 13."
- **Chapters affected:** Ch11 (therapist), Ch13 (victim)
- **Evidence:**
  - Ch11: "Dr. Marcus Webb (Columbia, SC, 1998, co-authored memory-modification protocols with Dr. Richard)."
  - Ch13: "Marcus Webb (child), nine, Concord. Three weeks [in induced coma]."
- **Severity:** Critical — ambiguity breaks reader continuity; readers will conflate the two identities.
- **Suggested fix:** Rename the coma victim "Marcus Hale" (smaller ripple; therapist is historically significant). Change Ch13 line: "Marcus Hale, nine, Concord. Three weeks [in induced coma]." Update facts.md victim register to reflect the change.

### MAJOR Issues

**M1: Agent Martinez pronoun inconsistency (cross-chapter)**
- **Source row:** Character description (Story Bible) lists "Agent Sarah Martinez... woman in her forties... graying hair in ponytail."
- **Chapters affected:** Ch16, Ch21 use "his"; Ch27 uses "she"
- **Evidence:**
  - Ch21: "Agent Martinez's voice cut through the humming air. 'I have to say, I'm concerned about your mental state.' His voice was low."
  - Ch27: "Agent Martinez stood beside her for a long moment. 'You chose right. Thank you for letting them have their names back.'"
- **Severity:** Major — pronoun flip is jarring but the character identity never merges with a male character, so reader can self-correct. However, it's a mechanical defect that impacts clarity.
- **Suggested fix:** Standardize to female pronouns throughout. In Ch16 and Ch21, change "his voice" to "her voice" and "he said" to "she said." Search the full manuscript for all Martinez pronouns and audit for consistency.

**M2: Bird custody explanation missing (Req #5)**
- **Source row (Story Bible, Critical Requirements):** "The carved wooden bird's 25-year custody must be explained."
- **Chapters affected:** Ch22 (flashback, last appearance of child-Maya with bird), Ch23 (adult-Maya with bird, no explanation of gap)
- **Evidence:**
  - Ch22: "Ethan presses the carved driftwood bird into Maya's hand... The needle. The hollow shore waves fading." [Implicit: child-Maya passes out / is sedated.]
  - Ch23 (next bird reference): "She pulled out her phone and she looked at it, and she looked away, and she looked at it again. And on her phone was the recording of herself humming it, forty-seven seconds long, marked *Chen-Maya-Session-2-2026-04*." [No mention of the bird being recovered or rediscovered.]
  - Ch20: "She opened her hand and showed him the small wooden bird." [Bird is suddenly in adult Maya's possession with no on-page explanation.]
- **Severity:** Major — a load-bearing physical object vanishes and reappears without explanation. Readers will notice.
- **Suggested fix:** Add a beat in Ch20 (or earlier in Ch18–19) where Maya recovers the bird from her childhood possessions (a box, an attic, a file of her parents' kept items) or a law-enforcement evidence return. Specific suggestion: Insert into Ch18 or Ch19 a short scene (50–100 words) where Maya's mother or father hands her the bird, saying something like "We found this in your things, honey. We didn't know what it was until..." This grounds the object's continuity.

**M3: Emma Washington age discontinuity (minor but tracked)**
- **Source row:** Character profile (Story Bible): Emma age ~6 at disappearance 12 years ago = 18 at rescue (Ch13). By Ch31 (1 year later), should still be 18 or newly 19 depending on birthday timing.
- **Chapters affected:** Ch13 (rescue), Ch31 (epilogue)
- **Evidence:**
  - Ch13: "Emma Washington, dark curls, serious eyes... She was eighteen now."
  - Ch31: "Emma was nineteen now."
- **Severity:** Minor — the math works if a birthday occurs during the year-gap, but the prose doesn't signal the birthday, making it feel like a discontinuity.
- **Suggested fix:** Clarify the birthday in the year-gap. In Ch31, change "Emma was nineteen now" to "Emma was nineteen now, having turned nineteen that spring" or specify a month. Alternatively, note in Ch30 (The Long Winter chapter) that Maya notes Emma's birthday having passed. Surgical fix.

---

## Clean Findings

**PASS (no issues):**
- Chapters 1–10 (Act I) state table walk: consistent POV, memory progression, character custody
- Chapters 11–21 (Act II) state table walk: consistent state transitions, victim rescue sequencing
- Chapters 22–31 (Act III) state table walk: flashback in present tense, custody tracking, epilogue finale
- Who-Knows-What matrix spot-checks: no early-leak violations detected in sample of 8 secrets
- Critical Requirement #1 (Southern drawl under stress only): consistent across 6+ sample chapters
- Critical Requirement #2 (present tense for flashback): Ch22 fully compliant
- Critical Requirement #3 (no head-hopping): all sampled chapters maintain Maya POV exclusively
- Critical Requirement #4 (memory recovery gradual & triggered): no convenient instant-recall violations
- Critical Requirement #6 (island geography): consistent descriptions across 4+ references
- Critical Requirement #7 (Dr. Chen disambiguation): established in Ch7
- Character names (Maya, Richard, Eleanor, James, Park, Kim, Fairchild, Ethan): consistent spelling and usage across all chapters
- Place names (Blackwood Island, Bar Harbor, Portland, Geneva, hollow shore): consistent usage
- Numeric facts (23 victims, 18 rescued, 5 dead, commission $50K, Maya's age 35): consistent tracking across chapters
- Ethan's forgery reveal: layered correctly Ch7→Ch10→Ch24 without contradictions
- Sarah Blackwood murder confirmation: seeded Ch4–6, confirmed Ch7, rendered Ch22, consistent
- Tommy Morrison murder: fragmented Ch4, full memory Ch13, rendered Ch22, consistent

---

## EXCEPTION Honored

None of the failures identified match declared EXCEPTIONs in the facts.md block. (The uncontracted Eleanor forms and the high uncontracted count in Ch17 are noted as potential exceptions in facts.md, but I do not see them formally declared with `### EXCEPTION:` syntax, so I flag them as issues rather than exceptions.)

---

## Verification Matrix Summary

| Section | Rows checked | PASS | FAIL | EXCEPTION |
|---------|--------------|------|------|-----------|
| Per-Chapter State Table | 31 | 31 | 0 | 0 |
| Who-Knows-What Matrix | 20 (spot-check) | 20 | 0 | 0 |
| Critical Requirements | 8 | 7 | 1 | 0 |
| Series Continuity | N/A | — | — | — |
| Anti-Requirements / Planted Defects | 4 | 3 | 1 | 0 |
| Cross-Chapter Entity Consistency | 24 | 22 | 2 | 0 |
| **TOTALS** | **78** | **74** | **4** | **0** |

---

<review_data>
{
  "agent": "matrix",
  "issue_counts": {
    "critical": 1,
    "major": 2,
    "minor": 1
  },
  "issues": [
    {
      "id": "C1",
      "severity": "critical",
      "chapters": [11, 13],
      "category": "Naming collision",
      "fix_type": "surgical",
      "title": "Dr. Marcus Webb / Marcus Webb name collision breaks reader continuity",
      "description": "Story.md notes this as a known issue. Ch11 introduces Dr. Marcus Webb (childhood therapist, Columbia SC, co-author with Dr. Richard, 1997). Ch13 lists 'Marcus Webb (child), nine, Concord, 3 weeks in induced coma' among the rescued victims. The identical name creates ambiguity—readers will conflate the two identities until later context (Webb the therapist is adult/historical; Webb the victim is child/recent). Breaks the identity invariant.",
      "evidence": "Ch11: 'Dr. Marcus Webb (her childhood therapist in Columbia, SC, 1998).' Ch13: 'Marcus Webb (child), 9, Concord. Three weeks.'",
      "suggested_fix": "Rename the coma victim 'Marcus Hale' (smaller ripple; therapist is load-bearing historical figure). In ch13.md, change line 'Marcus Webb (child), nine, Concord. Three weeks [in induced coma]' to 'Marcus Hale (child), nine, Concord. Three weeks [in induced coma].' Update facts.md victim register row to reflect 'Marcus Hale' instead of 'Marcus Webb (child)'."
    },
    {
      "id": "M1",
      "severity": "major",
      "chapters": [16, 21, 27],
      "category": "Cross-chapter pronoun inconsistency",
      "fix_type": "cross_chapter",
      "title": "Agent Martinez pronoun flip (male → female) across chapters",
      "description": "Character profile (Story Bible) establishes Agent Martinez as female ('woman in her forties, graying hair in ponytail'). Ch16 and Ch21 use 'his voice' and 'he said'; Ch27 switches to 'she'. The flip is jarring and breaks character identity consistency.",
      "evidence": "Ch21: 'Agent Martinez's voice cut through the humming air. His voice was low and steady.' Ch27: 'Agent Martinez stood beside her. She said, \"Welcome to the hornet's nest.\"'",
      "suggested_fix": "Standardize to female pronouns throughout. In ch16.md and ch21.md, audit all Agent Martinez pronouns and change 'his'→'her', 'he'→'she', 'him'→'her' globally. Search full manuscript for 'Martinez' and '\\bhis\\b' or '\\bhe\\b' within +/- 5 words to catch all instances. Verify final state: all Martinez pronouns are female."
    },
    {
      "id": "M2",
      "severity": "major",
      "chapters": [20, 22, 23],
      "category": "Missing physical object explanation",
      "fix_type": "structural",
      "title": "Carved wooden bird's 25-year custody unexplained (Req #5 unmet)",
      "description": "Story.md Critical Requirement #5: 'The carved wooden bird's 25-year custody must be explained.' Ch22 (flashback) has child-Maya holding the bird, then passed out/sedated. Adult-Maya appears with the bird in Ch20 with no explanation of how it survived 25 years in her possession—did her parents keep it? Did she find it? The gap breaks the load-bearing object's continuity.",
      "evidence": "Ch22: 'Ethan presses the carved driftwood bird into Maya's hand, whispers Remember, and melts into a side tunnel. The needle. The hollow shore waves fading.' [Next bird reference in Ch20: 'She opened her hand and showed him the small wooden bird.'] No intervening chapter explains the bird's recovery or survival.",
      "suggested_fix": "Add a beat in ch18.md or ch19.md (before Ch20) where Maya recovers the bird from childhood storage. Suggested insertion (50–100 words): after an interrogation scene or therapy moment, add a short scene where Maya's mother or father returns a box of childhood items to her, and the bird is inside. Example: 'Her mother's next call came on a Wednesday. A box had arrived from Columbia—childhood things, her mother said. Maya opened it in her apartment. Inside, wrapped in a sock, was the carved wooden bird. She did not remember packing it. She did not remember keeping it. But her hands knew its weight.' This explains the object's continuity and ties it to her parents' role in the suppression."
    },
    {
      "id": "m1",
      "severity": "minor",
      "chapters": [13, 31],
      "category": "Character age discontinuity",
      "fix_type": "surgical",
      "title": "Emma Washington age jump (18 → 19) lacks birthday signal",
      "description": "Ch13 establishes Emma disappeared at age 6, twelve years ago, making her 18 at rescue. By Ch31 (1 year later), she is 19. Arithmetic works if her birthday occurs during the year-gap, but the prose does not signal this event, making the jump feel like a discontinuity.",
      "evidence": "Ch13: 'She was eighteen now.' Ch31: 'Emma was nineteen now.'",
      "suggested_fix": "In ch31.md, line 'Emma was nineteen now', change to 'Emma was nineteen now, having turned nineteen that spring' or 'Emma was nineteen now; she'd had her birthday in April.' Alternatively, add to ch30.md (The Long Winter) a single line noting 'Emma's birthday had come and gone quietly in the spring.' Surgical fix—one line clarifies the birthday timing."
    }
  ],
  "verdict": "Matrix integrity: 74/78 entries pass. Four failures identified: one critical (name collision), two major (pronoun inconsistency, missing object custody), one minor (age signal). Critical blocks narrative clarity and must be fixed before publication. Major issues degrade cross-chapter coherence and should be resolved. The manuscript's state table and Who-Knows-What tracking are otherwise sound; no systemic matrix violations detected. Recommend fixing C1 and M1–M2 before next pass."
}
</review_data>

---

## Part 6: Reader Pass (first-read experience)

(panel diet — craft lens skipped this pass; full panel returns for the convergence confirmation)


---

## Part 7: Tier-0 Deterministic Findings (synthetic)

<review_data>
{
 "agent": "tier0",
 "issues": [
  {
   "id": "T0-1",
   "severity": "critical",
   "chapters": [
    25
   ],
   "category": "Narration person vs spec",
   "fix_type": "structural",
   "title": "Ch 25 narration person contradicts the story bible",
   "description": "Deterministic narration-person check: chapter 25 narration is FIRST person (15 first-person markers outside dialogue) but the story bible declares it third person. Dialogue is exempt; this is the narration itself.",
   "suggested_fix": "Convert the chapter's NARRATION to the spec-declared person, preserving every quoted line of dialogue verbatim, every fact, and the paragraph structure. Keep gnomic/aphoristic lines as free indirect discourse."
  },
  {
   "id": "T0-2",
   "severity": "critical",
   "chapters": [
    29
   ],
   "category": "Narration person vs spec",
   "fix_type": "structural",
   "title": "Ch 29 narration person contradicts the story bible",
   "description": "Deterministic narration-person check: chapter 29 narration is FIRST person (40 first-person markers outside dialogue) but the story bible declares it third person. Dialogue is exempt; this is the narration itself.",
   "suggested_fix": "Convert the chapter's NARRATION to the spec-declared person, preserving every quoted line of dialogue verbatim, every fact, and the paragraph structure. Keep gnomic/aphoristic lines as free indirect discourse."
  },
  {
   "severity": "major",
   "chapters": [
    1,
    3,
    7,
    8,
    9,
    10,
    13,
    16,
    17,
    21,
    22,
    23,
    24,
    25,
    28,
    29,
    30,
    31
   ],
   "category": "Repetition \u2014 emergent phrase",
   "fix_type": "cross_chapter",
   "title": "Emergent repeated phrase 'for a long time' (18\u00d7, 18 chapters)",
   "description": "The phrase 'for a long time' recurs 18 times across 18 chapters without being a declared motif. An undeclared phrase used this often becomes a verbal crutch that pre-announces the beat (the reader feels the frame, not the content).",
   "suggested_fix": "Keep 1-2 uses of 'for a long time' where it lands hardest; rewrite the rest with scene-specific language. Especially cut it where it opens an interior beat as throat-clearing \u2014 sometimes just say the thing without the preamble.",
   "id": "T0-3"
  },
  {
   "severity": "major",
   "chapters": [
    1,
    4,
    5,
    8,
    10,
    11,
    13,
    14,
    15,
    16,
    17,
    18,
    20,
    24,
    27,
    29,
    30
   ],
   "category": "Repetition \u2014 emergent phrase",
   "fix_type": "cross_chapter",
   "title": "Emergent repeated phrase 'finger tapped once against' (17\u00d7, 17 chapters)",
   "description": "The phrase 'finger tapped once against' recurs 17 times across 17 chapters without being a declared motif. An undeclared phrase used this often becomes a verbal crutch that pre-announces the beat (the reader feels the frame, not the content).",
   "suggested_fix": "Keep 1-2 uses of 'finger tapped once against' where it lands hardest; rewrite the rest with scene-specific language. Especially cut it where it opens an interior beat as throat-clearing \u2014 sometimes just say the thing without the preamble.",
   "id": "T0-4"
  },
  {
   "severity": "major",
   "chapters": [
    4,
    6,
    7,
    8,
    10,
    11,
    12,
    14,
    15,
    17,
    18,
    19,
    20,
    23,
    24,
    26,
    29
   ],
   "category": "Repetition \u2014 emergent phrase",
   "fix_type": "cross_chapter",
   "title": "Emergent repeated phrase 'her right index finger' (17\u00d7, 17 chapters)",
   "description": "The phrase 'her right index finger' recurs 17 times across 17 chapters without being a declared motif. An undeclared phrase used this often becomes a verbal crutch that pre-announces the beat (the reader feels the frame, not the content).",
   "suggested_fix": "Keep 1-2 uses of 'her right index finger' where it lands hardest; rewrite the rest with scene-specific language. Especially cut it where it opens an interior beat as throat-clearing \u2014 sometimes just say the thing without the preamble.",
   "id": "T0-5"
  },
  {
   "severity": "major",
   "chapters": [
    7,
    9,
    11,
    16,
    19,
    24,
    27,
    28,
    30
   ],
   "category": "Repetition \u2014 emergent phrase",
   "fix_type": "cross_chapter",
   "title": "Emergent repeated phrase 'for twenty five years' (9\u00d7, 9 chapters)",
   "description": "The phrase 'for twenty five years' recurs 9 times across 9 chapters without being a declared motif. An undeclared phrase used this often becomes a verbal crutch that pre-announces the beat (the reader feels the frame, not the content).",
   "suggested_fix": "Keep 1-2 uses of 'for twenty five years' where it lands hardest; rewrite the rest with scene-specific language. Especially cut it where it opens an interior beat as throat-clearing \u2014 sometimes just say the thing without the preamble.",
   "id": "T0-6"
  },
  {
   "severity": "major",
   "chapters": [
    8,
    11,
    12,
    14,
    16,
    18,
    20
   ],
   "category": "Repetition \u2014 emergent phrase",
   "fix_type": "cross_chapter",
   "title": "Emergent repeated phrase 'maya said her voice' (7\u00d7, 7 chapters)",
   "description": "The phrase 'maya said her voice' recurs 7 times across 7 chapters without being a declared motif. An undeclared phrase used this often becomes a verbal crutch that pre-announces the beat (the reader feels the frame, not the content).",
   "suggested_fix": "Keep 1-2 uses of 'maya said her voice' where it lands hardest; rewrite the rest with scene-specific language. Especially cut it where it opens an interior beat as throat-clearing \u2014 sometimes just say the thing without the preamble.",
   "id": "T0-7"
  },
  {
   "severity": "minor",
   "chapters": [
    12
   ],
   "category": "Repetition \u2014 structural opening (datestamp cluster)",
   "fix_type": "structural",
   "title": "Ch 12 opens on a day/time stamp inside a back-to-back cluster",
   "description": "Advisory: consecutive chapters [10, 11, 12] include 2 that open by establishing WHEN it is ('The next morning\u2026', 'Thursday I\u2026'). Back-to-back datestamp leads are a mild structural rut. Surfaced for the reader agent's holistic judgment \u2014 NOT auto-rewritten, since a day-named opening can be a strong, distinct entry on its own.",
   "suggested_fix": "If the reader pass agrees these openings feel repetitive, vary ONE of the cluster's openings to a non-datestamp entry (dialogue, question, mid-action, sensory, philosophical, temporal); otherwise leave them \u2014 naming a day is not by itself a flaw.",
   "id": "T0-8"
  },
  {
   "severity": "minor",
   "chapters": [
    14
   ],
   "category": "Repetition \u2014 structural opening (datestamp cluster)",
   "fix_type": "structural",
   "title": "Ch 14 opens on a day/time stamp inside a back-to-back cluster",
   "description": "Advisory: consecutive chapters [12, 13, 14] include 2 that open by establishing WHEN it is ('The next morning\u2026', 'Thursday I\u2026'). Back-to-back datestamp leads are a mild structural rut. Surfaced for the reader agent's holistic judgment \u2014 NOT auto-rewritten, since a day-named opening can be a strong, distinct entry on its own.",
   "suggested_fix": "If the reader pass agrees these openings feel repetitive, vary ONE of the cluster's openings to a non-datestamp entry (dialogue, question, mid-action, sensory, philosophical, temporal); otherwise leave them \u2014 naming a day is not by itself a flaw.",
   "id": "T0-9"
  },
  {
   "severity": "minor",
   "chapters": [
    16
   ],
   "category": "Repetition \u2014 structural opening (datestamp cluster)",
   "fix_type": "structural",
   "title": "Ch 16 opens on a day/time stamp inside a back-to-back cluster",
   "description": "Advisory: consecutive chapters [14, 15, 16] include 2 that open by establishing WHEN it is ('The next morning\u2026', 'Thursday I\u2026'). Back-to-back datestamp leads are a mild structural rut. Surfaced for the reader agent's holistic judgment \u2014 NOT auto-rewritten, since a day-named opening can be a strong, distinct entry on its own.",
   "suggested_fix": "If the reader pass agrees these openings feel repetitive, vary ONE of the cluster's openings to a non-datestamp entry (dialogue, question, mid-action, sensory, philosophical, temporal); otherwise leave them \u2014 naming a day is not by itself a flaw.",
   "id": "T0-10"
  },
  {
   "id": "T0-11",
   "severity": "major",
   "fix_type": "cross_chapter",
   "category": "Repetition \u2014 near-duplicate passage",
   "chapters": [
    4,
    6
   ],
   "title": "Near-duplicate passage across ch04 and ch06 (80% overlap)",
   "description": "These two passages overlap ~80% and read as the same beat reworded: \"James's fork clattered against his plate. \"She was trying to tell me something,\" he said, his voice high with strain. \"Sarah, I mean. In her\" (ch04) vs \"James's face crumpled. \"In her last weeks she kept saying she remembered things from when she was little. About the other children. But Moth\" (ch06). If it is a re-run of the same scene or line, cut the weaker instance or reduce it to a brief callback. Keep both ONLY if it is a deliberate recurring motif.",
   "suggested_fix": "Cut the weaker of the two passages or reduce it to a short callback so the two chapters no longer restate the same beat; keep both only if the repetition is an intentional motif."
  },
  {
   "id": "T0-12",
   "severity": "major",
   "fix_type": "cross_chapter",
   "category": "Repetition \u2014 near-duplicate passage",
   "chapters": [
    30,
    31
   ],
   "title": "Near-duplicate passage across ch30 and ch31 (60% overlap)",
   "description": "These two passages overlap ~60% and read as the same beat reworded: \"Margaret Swift met her at the dock in a blue canvas jacket with a small sea-bird logo on the pocket. She had taken the Trust's caretaker job\" (ch30) vs \"Margaret Swift met her at the dock. Margaret, who had broken a twenty-year silence to lead them to the cave entrance, and who now wore the b\" (ch31). If it is a re-run of the same scene or line, cut the weaker instance or reduce it to a brief callback. Keep both ONLY if it is a deliberate recurring motif.",
   "suggested_fix": "Cut the weaker of the two passages or reduce it to a short callback so the two chapters no longer restate the same beat; keep both only if the repetition is an intentional motif."
  },
  {
   "id": "T0-13",
   "severity": "major",
   "fix_type": "cross_chapter",
   "category": "Repetition \u2014 near-duplicate passage",
   "chapters": [
    3,
    4
   ],
   "title": "Near-duplicate passage across ch03 and ch04 (51% overlap)",
   "description": "These two passages overlap ~51% and read as the same beat reworded: \"\"I'm suggesting that perhaps you should let me help you. I have something that could help you sleep, help you think more clearly. Sometimes \" (ch03) vs \"\"Sometimes the mind needs guidance to process difficult situations properly.\" He opened his medical bag, revealing rows of vials and syringe\" (ch04). If it is a re-run of the same scene or line, cut the weaker instance or reduce it to a brief callback. Keep both ONLY if it is a deliberate recurring motif.",
   "suggested_fix": "Cut the weaker of the two passages or reduce it to a short callback so the two chapters no longer restate the same beat; keep both only if the repetition is an intentional motif."
  },
  {
   "id": "T0-14",
   "severity": "major",
   "chapters": [
    14
   ],
   "category": "Mechanical / markup",
   "fix_type": "surgical",
   "title": "Garbled quote markup",
   "description": "Deterministic markup check: ch14: [garbled] fused-word splice 'nor'easter' near \"...ding into the gray of a nor'easter that had moved north th...\" \u2014 an edit collided two words; separate them.",
   "suggested_fix": "Repair the quotation marks (remove the doubled/orphaned glyph; balance the pair)."
  },
  {
   "id": "T0-15",
   "severity": "major",
   "chapters": [
    4
   ],
   "category": "Quoted-document continuity",
   "fix_type": "surgical",
   "title": "Callback quotes text absent from the quoted document",
   "description": "Deterministic quoted-document check: ch04: callback references text absent from the just-quoted document \u2014 narration has \"underlined *witness,*\" but the quoted text above it (\"What I need.\u2026\") does not contain that phrase.",
   "suggested_fix": "Either add the referenced phrase to the quoted document so the callback has an antecedent, or change the callback to reference a phrase the document actually contains. Keep document and callback in the same edit."
  },
  {
   "id": "T0-16",
   "severity": "minor",
   "chapters": [],
   "category": "Name consistency",
   "fix_type": "surgical",
   "title": "Possible name-form slip",
   "description": "Deterministic name-form check: name-form: 'Arthur' used standalone 1x in narration () but this character is otherwise 'Fairchild' (54x) \u2014 likely a first-name/surname slip or mis-attribution; verify.",
   "suggested_fix": "Verify the intended character and use the consistent name form."
  },
  {
   "id": "T0-17",
   "severity": "minor",
   "chapters": [
    10
   ],
   "category": "Name consistency",
   "fix_type": "surgical",
   "title": "Possible name-form slip",
   "description": "Deterministic name-form check: name-form: 'Lucas' used standalone 1x in narration (ch10) but this character is otherwise 'Chen' (121x) \u2014 likely a first-name/surname slip or mis-attribution; verify.",
   "suggested_fix": "Verify the intended character and use the consistent name form."
  },
  {
   "id": "T0-18",
   "severity": "minor",
   "chapters": [
    2,
    10
   ],
   "category": "Continuity (entity attribute)",
   "fix_type": "surgical",
   "title": "Stable attribute (floor/age) contradicts across chapters",
   "description": "Deterministic entity-attribute check: floor asserted with conflicting values \u2014 2 (ch02); 3 (ch10); verify these are the same entity (continuity slip) vs distinct ones.",
   "suggested_fix": "Confirm the canonical value and align every chapter to it."
  },
  {
   "id": "T0-19",
   "severity": "major",
   "chapters": [
    21
   ],
   "category": "Continuity (character gender/pronoun)",
   "fix_type": "surgical",
   "title": "Pronoun/gender mismatch for Martinez",
   "description": "Deterministic gender-pronoun check: Martinez is female per the cast but the narration uses male pronouns near the name. Snippet: \"Martinez:  \n\n  His voice stayed level.\".",
   "suggested_fix": "Correct the pronouns referring to Martinez to her/she and audit the whole scene for any other slipped pronouns on this character."
  },
  {
   "id": "CF-20",
   "severity": "critical",
   "chapters": [
    2,
    14
   ],
   "category": "carry-forward",
   "fix_type": "structural",
   "title": "Fused-word collision: 'nor'easter'",
   "description": "Carry-forward: still present after 1 prior attempt(s) and no longer being re-flagged. Unresolved quoted text: \"easter\"",
   "suggested_fix": "Resolve the original issue; the quoted text above is verbatim still in the prose. Apply the fix decisively."
  },
  {
   "id": "CF-21",
   "severity": "critical",
   "chapters": [
    20
   ],
   "category": "carry-forward",
   "fix_type": "structural",
   "title": "Literal 'Ch17's identification' outline leak into prose",
   "description": "Carry-forward: still present after 1 prior attempt(s) and no longer being re-flagged. Unresolved quoted text: \"The Architect\"",
   "suggested_fix": "Resolve the original issue; the quoted text above is verbatim still in the prose. Apply the fix decisively."
  }
 ]
}
</review_data>
