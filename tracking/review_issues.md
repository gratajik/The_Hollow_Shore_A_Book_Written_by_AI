# Review Issues — The Hollow Shore

Cumulative issue log across review passes. Reviewer: before each pass, read this file. Do not re-report issues marked `fixed` or `verified`. Do check for regressions on previously-fixed issues.

## Status legend
- `open` — reported but not yet fixed
- `fixed` — rewritten; pending verification
- `verified` — confirmed fixed in a subsequent pass with no regression
- `reopened` — was fixed in an earlier pass, regressed
- `wontfix` — reported and consciously deferred

## Issues

### Pass 1 issues (Critical)

| ID | Pass Found | Pass Fixed | Status | Severity | Chapter(s) | Category | Description |
|----|-----------|-----------|--------|----------|-----------|----------|-------------|
| C1 | 1 | 1 | fixed | Critical | 20 | tense | Ch20 was written in past tense; story.md requires present tense. Rewritten in present tense throughout. |
| C2 | 1 | 1 | fixed | Critical | 6 | continuity | Ch06 arrested Dr. Richard and Eleanor on-page, 7 chapters before the canonical Ch13 arrests. Rewritten: Richard escapes on yacht, Eleanor stays composed, Park arrives with Bar Harbor patrol only. |
| C3 | 1 | 1 | fixed | Critical | 4 | plot | Dr. Richard openly confessed to Tommy's and Sarah's murders in Ch04. Confessions belong to Ch15/Ch25. Rewritten: Richard menaces without confessing. |
| C4 | 1 | 1 | fixed | Critical | 5 | plot | Full present-tense Tommy-murder flashback in Ch05 collapsed the Ch12/Ch20 memory arc. Rewritten: Ch05 fragment is sensory-only (smell, doubling), no Tommy name, no murder details. |
| C5 | 1 | 1 | fixed | Critical | 5, 6 | structure | Ch05 and Ch06 both staged the hidden-room discovery + "Choose, Maya" hostage scene. Rewritten: Ch05 ends at boy discovery + phone ringing; Ch06 opens on Richard's arrival. |
| C6 | 1 | 1 | fixed | Critical | 7 | plot | "I remember everything now" in Ch07 broke the state-table memory gradient. Rewritten: "fragments — more every hour." |
| C7 | 1 | 1 | fixed | Critical | 17-28 | genre/reframe | Act 3's SF/techno-thriller framing (logic bomb, master-key phone-hack, digital-ghost Ethan, working consciousness-preservation tech) contradicted the user's stated series direction (grounded PI). Reframed: Fairchild's motive = private delusion; Ethan = twenty-year paper archivist; Ch27 climax = coordinated global raid, not digital warfare. |
| C8 | 1 | 1 | fixed | Critical | all | prose | Aphoristic/thesis-statement chapter endings across 25+ of 28 chapters (budget 2-3). Rewritten to images/actions/silence. 2-3 retained. |
| C9 | 1 | 1 | fixed | Critical | 20, 21 | continuity | Carved wooden bird's 25-year custody unexplained. Added Ch20 closing paragraph: bird on nightstand a week after the flashback, in velvet-lined box in Maya's jewelry cabinet for 25 years. |
| C10 | 1 | 1 | fixed | Critical | 22 | continuity | Ch17 and Ch22 both titled "The Ghost in the Machine." Ch22 renamed "The Patient Watcher." |
| C11 | 1 | 1 | fixed | Critical | 14-19, 21 | character | Agent Martinez pronoun flip (male Ch14-19, 21; female Ch22-28). ~19 pronoun conversions across the range. Now consistently female per voice card. |
| C12 | 1 | 1 | fixed | Critical | 3-7 | plot | Memory-recovery acceleration — Maya was at memory level 10 by Ch05 per prose; state table says Ch12. Fixed via C3, C4, C6 and Ch04/Ch05 memory dialog-backs. |
| C13 | 1 | 1 | fixed | Critical | 2, 3 | structure | Ch02 and Ch03 staged near-identical dinner conversations. Ch03 dinner compressed -535 words, focused on blue-wallpaper fragment + journal discovery. |
| C14 | 1 | 1 | fixed | Critical | 3, 4, 6 | voice | "Some promises are meant to be broken" previewed in Ch03 and Ch04 before Ch06's climactic drawl-moment. Previews stripped. Ch06 owns the line. |

### Pass 1 issues (Major)

| ID | Pass Found | Pass Fixed | Status | Severity | Chapter(s) | Category | Description |
|----|-----------|-----------|--------|----------|-----------|----------|-------------|
| M1 | 1 | 1 | fixed | Major | all | mechanical | 159 em-dashes manuscript-wide. All replaced with commas/periods/colons/parentheses or period-fragments. Count: 159 → 0. |
| M2 | 1 | 1 | fixed | Major | all | mechanical | 85 forbidden dialogue tags. Replaced with "said" or action beats. ~11 residual regex hits are false positives (adjectival usage). |
| M3 | 1 | 1 | fixed | Major | multiple | mechanical | 15 "suddenly" instances. All deleted or restructured. Count: 15 → 0. |
| M4 | 1 | 1 | partial | Major | multiple | prose | Trait-word accumulation (precise/deliberate/composure/methodical/calculated): 63 → ~25. Further reduction deferred to Pass 2. |
| M5 | 1 | 1 | partial | Major | multiple | prose | Hedge phrases ("seemed to" / "a sense of"): 36 → ~8. Deferred residuals to Pass 2. |
| M6 | 1 | 1 | fixed | Major | 6, 11, 13 | character | Eleanor's composure cracked pre-Ch14. Restored to scalpel-precise aristocratic coldness across Ch06/11/13. Ch14 Project Nightingale crack now earns itself. |
| M7 | 1 | 1 | fixed | Major | 11, 13, 21 | voice | Maya's drawl vocabulary was only "Lord have mercy" (6+ times). Varied to "Sure as I'm standin'" (Ch11), "What in the Sam Hill" (Ch13), "Fixin' to find" / "I don't have a dog in this fight" (Ch21). |
| M8 | 1 | 1 | fixed | Major | 8-19, 21-27 | character | Maya's finger-tapping tic lost after Ch02. Reinstated at stress moments across 17+ chapters. |
| M9 | 1 | 1 | fixed | Major | 14, 15 | character | Marcus Williams past-failure case dropped after Ch01. Reinstated in Ch14 (post-phone-call interior) and Ch15 (pre-Tommy-question during interrogation) as fear-of-being-wrong subtext. |
| M10 | 1 | 1 | fixed | Major | 6 | character | Detective Park's Atlanta-Southern rapport never appeared in prose. Added Ch06 exchange where Park's drawl surfaces under stress and Maya's meets it. |
| M11 | 1 | 1 | fixed | Major | 9 | character | Dr. Sarah Chen's "How does that make you feel?" TV-therapist cliché. Replaced with voice-specific reframe. |
| M12 | 1 | 1 | fixed | Major | 12, 23, 24 | naming | Marcus Webb child victim → Marcus Hale. Silas Blackwood → Silas Renault. Dr. Alistair Finch → Dr. Henry Finch. |
| M13 | 1 | 1 | fixed | Major | 7 | prose | "Puppet master / mastermind operating from the shadows" telegraphed Fairchild 10 chapters early. Rewritten to procedural unease. |
| M14 | 1 | 1 | fixed | Major | 9, 10 | prose | "Act One ending / Act Two begun" self-referential act-boundary narrator asides. Cut. |
| M15 | 1 | 1 | fixed | Major | 2, 3, 4, 7, 8, 13, 14, 16, 19 | prose | Repeated cross-chapter constructions ("temperature seemed to drop ten degrees," "hunt was/wasn't over," "sense of purpose"). Deduplicated; one instance preserved of each. |
| M16 | 1 | 1 | fixed | Major | 7, 8 | structure | Ch07/Ch08 used identical opening template. Ch07 opener preserved; Ch08 rewritten. |
| M17 | 1 | 1 | partial | Major | 25-28 | pacing | Act 3 under-writing (Ch25-28 was 3,529 words). Expanded to 7,739 (2.2×). Additional expansion deferred to Pass 2 (Ch19-22 interstitial chapters). |
| M18 | 1 | 1 | fixed | Major | 20 | character | Maya-Sarah friendship under-written in Ch20 flashback. Added 250-word scene of them in the Cathedral cave with the chalk mermaid drawing. |
| M19 | 1 | 1 | fixed | Major | 26 | voice | Ethan's Ch26 TV-villain monologue ("burn their monstrous world to the ground") broke voice card. Rewritten to spare philosophical register. |
| M20 | 1 | 1 | fixed | Major | 17, 19, 25 | genre/reframe | Fairchild motive grounding. Added Kim line ("The consciousness data is corrupted noise... Fairchild paid for a ritual") in Ch17. Ch19 shrine reframed as ritual chapel ("none of the equipment was plugged into anything"). Ch25 Ethan: "He believed it would work. It never would have." |
| M21 | 1 | 1 | fixed | Major | 12 | prose | "MK-Ultra" exchange ("Dr. Richard perfected it") tone-deaf during rescue. Cut. |
| M22 | 1 | 1 | wontfix-pass1 | Major | 17 | prose | Kim's breakthroughs appear as past-tense "we got it" announcements. Deferred to Pass 2 — dramatize one mid-struggle breakthrough. |
| M23 | 1 | 1 | fixed | Major | 18, 22, 25, 26, 28 | prose | Motif catalogs near endings (three-term enumerations of established images). All cut. |

## Per-Chapter Sign-Off

| Chapter | Prose Cleared | Last Verified Pass | Notes |
|---------|---------------|-------------------|-------|
| ch01 | ✓ Pass 1 | 1 | Subagent-fixed. Em-dashes 15→0. Aphoristic ending→image. Typo corrected. |
| ch02 | ✓ Pass 1 | 1 | Subagent-fixed. Em-dashes 17→0. Flashback converted to present tense. Aphoristic ending→image. |
| ch03 | ✓ Pass 1 | 1 | Subagent-fixed. Dinner compressed -535w. Em-dashes 11→0. "Some promises" preview cut. |
| ch04 | ✓ Pass 1 | 1 | Manual rewrite. Murder confessions cut. Memory pulled back to level 3. |
| ch05 | ✓ Pass 1 | 1 | Manual rewrite. Tommy flashback cut. Ch05/Ch06 overlap resolved. Ends at boy discovery. |
| ch06 | ✓ Pass 1 | 1 | Manual rewrite. Richard escapes. Eleanor composed. No impossible murder charges. Park drawl rapport added. |
| ch07 | ✓ Pass 1 | 1 | Manual rewrite. "I remember everything" pulled back. Puppet-master telegraphing cut. |
| ch08 | ✓ Pass 1 | 1 | Subagent-fixed. FBI pitch compressed. Aphoristic ending→image. Dr. Chen disambiguation added. |
| ch09 | ✓ Pass 1 | 1 | Subagent-fixed. "Act One ending" self-reference cut. Aphoristic ending→action. |
| ch10 | ✓ Pass 1 | 1 | Subagent-fixed. "Act Two begun" cut. "blood run cold" cliche replaced. |
| ch11 | ✓ Pass 1 | 1 | Subagent-fixed. Eleanor composure restored. Drawl varied. Em-dashes 10→0. |
| ch12 | ✓ Pass 1 | 1 | Subagent-fixed. MK-Ultra cut. Marcus Hale rename. Martinez pronouns. |
| ch13 | ✓ Pass 1 | 1 | Subagent-fixed. Em-dashes 24→0. Eleanor admissions stripped. Service-tunnel line added. |
| ch14 | ✓ Pass 1 | 1 | Subagent-fixed. Martinez pronouns. Eleanor stammered→teacup rattle. Marcus Williams thread. Hotel-sensory ending. |
| ch15 | ✓ Pass 1 | 1 | Subagent-fixed. Martinez pronouns. Recruitment scene cut. Marcus Williams thread. |
| ch16 | ✓ Pass 1 | 1 | Subagent-fixed. "Symphony of" cut. Aphoristic triad cut. Finger-tap ending. |
| ch17 | ✓ Pass 1 | 1 | Subagent-fixed. Fairchild delusion grounding. Thomas photograph ending. |
| ch18 | ✓ Pass 1 | 1 | Subagent-fixed. Motif catalog cut. Surveillance-feed ending. Martinez pronouns. |
| ch19 | ✓ Pass 1 | 1 | Subagent-fixed. Shrine as ritual chapel, not lab. Bach-from-empty-speaker ending. Martinez pronouns. |
| ch20 | ✓ Pass 1 | 1 | Manual rewrite. Present-tense conversion. Maya-Sarah friendship expanded. Bird custody explained. |
| ch21 | ✓ Pass 1 | 1 | Subagent-fixed. Martinez pronouns. Drawl added. Staggered simultaneity. Bird-R ending. |
| ch22 | ✓ Pass 1 | 1 | Subagent-fixed. Title renamed "The Patient Watcher." Recruitment scene cut. Paper-trail framing. |
| ch23 | ✓ Pass 1 | 1 | Subagent-fixed. Silas Renault rename. Tech-genius deflated. Atlantic pier ending. |
| ch24 | ✓ Pass 1 | 1 | Subagent-fixed. Dr. Henry Finch rename. Surveillance schematics → paper archive. Finger-tap ending. |
| ch25 | ✓ Pass 1 | 1 | Manual rewrite. Orchid Room. Grounded delusion. Paper archive reveal. +1242w expansion. |
| ch26 | ✓ Pass 1 | 1 | Manual rewrite. Survivor's choice reframed as medical-records custody decision. Ethan surrenders. +817w. |
| ch27 | ✓ Pass 1 | 1 | Manual rewrite. Coordinated global raid (not digital warfare). +1093w. |
| ch28 | ✓ Pass 1 | 1 | Manual rewrite. Epilogue expanded. Parents reconciliation scene. Thesis-statement ending cut. +1058w. |

## Chapters Never Modified Since Last Verification

All 28 chapters modified in Pass 1. Sign-off status resets in Pass 2.

## Pass 2 Carry-Forward

- Residual forbidden-tag false positives need verification (most are adjectival / metaphorical usage, not dialogue attribution).
- Trait-word accumulation (precise/deliberate/composure) further thinning.
- Hedge-phrase residual cleanup.
- Consecutive High-temperature streaks — consider inserting a low-temp relief beat.
- Kim breakthrough dramatization (Ch17) — mid-struggle scene.
- Act 2 expansion candidates: a Sarah-journal chapter inside Act 1; more Maya-eight-year-old integration inside Act 2; at least one additional Ch19-22 transitional chapter.
- Adversarial Reviewer re-pass on new Ch25-28 prose to ensure no regressions from the expansion.
