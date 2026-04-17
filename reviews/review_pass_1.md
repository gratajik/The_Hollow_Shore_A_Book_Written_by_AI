# Review Pass 1 — The Hollow Shore

**Pass:** 1
**Date:** 2026-04-16
**Reviewer:** LoopReviewerAgent (Opus 4.7, parallel subagent orchestration)
**Inputs:** 28 chapters, 41,205 words total, pre-review baseline

---

## Strategic Reframe (applies to all fixes in this pass)

Greg confirmed (possible.md, 2026-04-16) that The Hollow Shore is **Book 1 of a traditional-detective series**. Books 2-4 will be "more traditional detective" novels. Act 3's current SF/techno-thriller register (Geneva logic bomb, master-key phone-hack, Ethan-as-digital-ghost, consciousness-preservation-as-working-tech) is an early-AI drafting artifact that must be pulled back to grounded PI thriller.

**Translation for this fix pass:**
- Fairchild stays. His motive stays. But the "consciousness preservation" framing is reframed as a **billionaire's private delusion** — he *thinks* Thomas's essence is in the children; the tech doesn't actually work. Cryogenic anchors are ritual objects, not a system.
- Ethan stays. His thematic function (the survivor who remembered) is load-bearing. But he becomes a **smart, wronged man** — a twenty-year investigative collaborator who has been quietly assembling evidence, not a cyberwarfare architect.
- The **Geneva logic bomb and master-key phone-hack are cut.** The climax becomes a raid and an interrogation — standard PI-thriller mechanics.
- The Orchid Room meeting can stay as a character confrontation. The digital-warfare climax cannot.

This reframe resolves five independent reviewer concerns (genre fracture, Fairchild camp, Ethan implausibility, Ch27 under-writing, series mismatch) in one structural fix.

---

## Deliverable A — Prioritized Issue List

### CRITICAL (Must fix before the book is shown to a reader)

**C1. Ch20 is written entirely in past tense.**
Story.md Critical Requirement #2 states the childhood flashback chapter must be in present tense. Entire chapter currently reads "The island was magic..." instead of "The island is magic..." This is a load-bearing book-specific rule violation.
- **Fix:** Full tense conversion of ch20.md from past → present.

**C2. Ch06 arrests Dr. Richard and Eleanor on-page, seven chapters before their canonical arrest.**
Per story.md Plot Sequence Verification Table, Dr. Richard is captured at Pemaquid Point (Ch13) and Eleanor is arrested in the library burning evidence (Ch13). Currently ch06:137-153 has Detective Park arresting both at the mansion during the Danny Morrison rescue. This invalidates the entire Ch07-Ch13 arc.
- **Fix:** Rewrite Ch06 ending so Dr. Richard flees (through the hidden passages / out to the yacht) and Eleanor stays composed. Detective Park arrives to find Maya, James, and the rescued Danny; Richard is gone and Eleanor claims no knowledge. Also fix ch06:141 "Maya's been in contact with us for days" — contradicts the communications blackout.

**C3. Ch04 has Dr. Richard openly confessing to Tommy's and Sarah's murders.**
Ch04 lines 117-127 have Maya saying "You killed him" and "Is that why you killed her?" and Dr. Richard effectively confessing. Per state table, these confessions don't land until Ch15 (Devil's Logic interrogation) and Ch25 (Sarah-harvest reveal). Collapsing them into Ch04 empties the Act 2-3 payoffs.
- **Fix:** Ch04 Richard menaces with veiled therapy language ("I helped you forget once. I can help you again") but does not confess. Maya holds the accusation internally.

**C4. Ch05 contains a full present-tense Tommy-murder flashback with name, strangulation, sheet-wrap.**
Per state table, Maya's memory is level 3 in Ch05. Full Tommy memory is Ch12 (integrated) / Ch20 (rendered). Ch05's present-tense detonation of Tommy's murder collapses the Ch06 → Ch12 → Ch20 gradient into a single chapter.
- **Fix:** Ch05 fragment shows adult arguing + sensory flash (Dr. Richard carrying a sheet), without naming Tommy or showing the murder. Reserve for Ch12 (full memory) / Ch20 (full render).

**C5. Ch05/Ch06 overlap: both stage the "Choose, Maya" hostage scene.**
Ch05 lines 117-168 stage the hidden-room discovery, the unconscious boy, and Dr. Richard's "Choose, Maya" ultimatum. Ch06 re-stages the same beats. The reader is watching the same scene twice.
- **Fix:** Ch05 ends at the discovery of the hidden room with the unconscious boy. Ch06 opens with Dr. Richard's "Well, well. I was wondering when you'd find this place."

**C6. Ch07 has Maya declaring "I remember everything now."**
Per state table, Maya memory level in Ch07 is 6 (mostly recovered), level 10 isn't reached until Ch12. Ch07's total-recall declaration empties Ch08-12's integration arc.
- **Fix:** Maya says she remembers "fragments — more every hour" and names specific sensory beats (blue room, basement, a boy named Tommy who I need to identify). Full recall stays Ch12.

**C7. Act 3 is written as a digital-warfare / consciousness-preservation techno-thriller.**
Per Strategic Reframe above. Ch17-Ch27 currently uses "harvest motive," "master key to the network," "logic bomb," "digital architect," "consciousness preservation" as operational concepts. Book 1 must be a grounded PI thriller.
- **Fix:** Reframe Fairchild's motive as private delusion (he *believes* the tech works; it does not). Reframe Ethan as a smart, wronged man — twenty-year investigative collaborator, not cyberwarfare architect. Cut the Geneva logic bomb and master-key phone-hack. Rewrite Ch25-27 climax as raid + interrogation. Fairchild is Jeffrey Epstein with a delusion, not Arthur C. Clarke.

**C8. Aphoristic/thesis-statement chapter endings across 25+ of 28 chapters.**
Budget per SKILL §6.7: 2-3 across the full manuscript. Current count includes "X had just begun" / "X had only just started" / "had his name" / "one more ghost to find" / "the chaos of justice" / "The past was not a ghost to be exorcised, but a shore to which she could always return, whole and unafraid" — the final line is the worst offender (aphoristic + thesis + titular + balanced-paradox + motif-catalog). This is the manuscript's single largest AI fingerprint.
- **Fix:** Rewrite at least 22 chapter endings to land on images, actions, or silence. Keep 2-3 aphoristic endings max. Ch28's closing sentence gets cut; end on the stone hitting the water.

**C9. Ch20 flashback ends with the bird in 8-year-old Maya's pocket; Ch21 pulls it from "her evidence box." The 25-year custody chain is never explained.**
Story.md Known Issue #8. The carved wooden bird is the book's central physical object and its continuity is broken at the central seam.
- **Fix:** Add a present-tense closing paragraph to Ch20: when Maya wakes in Columbia a week later, the bird is on her nightstand. Her mother says nothing. For 25 years it sits in a velvet-lined box in her jewelry cabinet, a piece of driftwood she assumes she picked up on a beach. Ch21 retrieval then makes sense.

**C10. Chapter title duplication (Ch17 = Ch22 = "The Ghost in the Machine").**
Story.md Known Issue #4.
- **Fix:** Ch22 renamed. Recommended: *"The Patient Watcher"*.

**C11. Agent Martinez pronoun flip (male Ch14-19, 21; female Ch22-28).**
Story.md Known Issue #6. Per character card Martinez is female.
- **Fix:** Global find-replace of Martinez male pronouns across Ch14, Ch15, Ch16, Ch18, Ch19, Ch21. Every "his/he/him" referring to Martinez → "her/she/her". Also soften the "goddamn treasure trove," "spat," "low growl" register toward the voice card's "supportive, low rumble, military-efficient."

**C12. Memory-recovery acceleration.**
Per state table, Maya's memory level progression is Ch03=2 → Ch04=3 → Ch06=4 → Ch07=6 → Ch12=10 → Ch20=rendered. Current prose collapses to level 10 by Ch05. This is not a single-chapter issue; it's the entire Act 1 arc being deployed at accelerated pace.
- **Fix:** See C3, C4, C6 above. Also clip Ch04 dinner-table memory ("I remember Dr. Richard carrying something wrapped in a sheet") — let Maya hold that card internally through Ch05-Ch06.

**C13. Dinner-scene redundancy (Ch02 / Ch03).**
Ch02 and Ch03 stage nearly identical dinner conversations (Dr. Richard probing Maya's psychology background, Eleanor's "Sarah had struggled," James's silenced outburst). Lines 55-81 of both chapters are near-verbatim.
- **Fix:** Ch03 dinner compresses to 2-3 exchanges; focus shifts to the blue-wallpaper memory fragment and the basement infiltration.

**C14. "Some promises are meant to be broken" preempted in Ch03 and Ch04 before the Ch06 voice-card moment.**
Maya's signature drawl-emergence line is previewed three times before its intended climactic delivery.
- **Fix:** Strip the previews from Ch03 and Ch04. Ch06 owns the first occurrence.

---

### MAJOR

**M1. Em-dashes: 159 across 21 chapters** (target 0 per style guide).
Per-chapter count: ch01=15, ch02=17, ch03=11, ch04=11, ch05=14, ch06=11, ch07=9, ch08=4, ch09=4, ch10=9, ch11=10, ch12=7, ch13=24, ch14=1, ch15=4, ch17=1, ch18=1, ch19=1, ch20=1, ch22=3, ch23=1.
- **Fix:** Mechanical replacement pass. Dialogue self-interruptions use period-separated fragments per SKILL §3.1 workaround. Exposition em-dashes become commas, colons, periods, or parentheses.

**M2. Forbidden dialogue tags: 85 across 26 chapters** (target near-zero).
Most offending: whispered, breathed, muttered, murmured, continued, agreed, corrected, announced, yelled, snarled, barked, hissed, spat, gasped.
- **Fix:** Every forbidden tag → "said" or action beat.

**M3. "Suddenly" as scene-transition crutch: 15 instances.**
- **Fix:** Delete every "suddenly" and restructure sentence.

**M4. Trait-word accumulation: 63 instances** (precise/precisely, deliberate/deliberately, methodical, calculated, composure/composed, steady/steadily).
- **Fix:** Replace 80% with dramatized action.

**M5. Hedge-phrase habit: 36 instances** (seemed to, a sense of, something like, something that).
- **Fix:** Every hedge → specific.

**M6. Eleanor cracks composure in Ch06, Ch11, Ch13 before her sanctioned Ch14 shatter.**
Story.md Critical Requirement #8.
- **Fix:** Restore composure to ch06 ("End this, Richard. She knows too much." — scalpel-cold instead of cracked-desperate), ch11 ("I trust you find this satisfying" — cool enamel instead of venom), ch13 (cold contempt in handcuffs, not spitting rage or naming "the program" or "Richard went too far that night"). Ch14 Project Nightingale crack stays.

**M7. Maya's Southern drawl vocabulary = only "Lord have mercy."**
Voice card lists: "What in the Sam Hill," "Sure as I'm standin'," "Worth a damn," "Might could," "Wrong as rain," "Fixin' to," "Bless your heart," "Over yonder," "Pretty as a peach." Currently "Lord have mercy" appears 6+ times; the other phrases don't appear.
- **Fix:** Distribute the drawl vocabulary across chapters. Vary the phrases.

**M8. Maya's finger-tapping physical tic disappears after Ch02.**
Story.md character voice card: tapping right index finger is her signature stress tell. Ch01 and Ch02 use it; Ch03-Ch28 do not.
- **Fix:** Reinstate tapping across Ch08, Ch11, Ch12, Ch14, Ch15, Ch17, Ch22, Ch26 — at moments of stress, decision, hunt-proximity.

**M9. Marcus Williams past-failure thread dropped after Ch01.**
Story.md Known Issue #11. Maya's wrong-identification case is named once in Ch01 and never invoked again as fear-of-being-wrong subtext.
- **Fix:** Invoke in Ch14 (parents' confession — "she'd been wrong about them for years"), Ch15 (interrogation — "what if I'm wrong about his confession?"), Ch26 (moral climax — the fear of making the wrong call about the children).

**M10. Detective Park's Atlanta-Southern voice card never realized.**
Voice card specifies shared-Southern rapport with Maya. Park's dialogue reads as generic LE throughout.
- **Fix:** Add at least one shared-Southern idiom exchange in Ch06 or Ch07. Park uses "Lord" or "y'all" under frustration; Maya catches the drawl and a small rapport forms.

**M11. Dr. Sarah Chen (therapist) Ch09 line "How does that make you feel?"**
TV-therapist cliché; the character's voice card is warm-specific, not sitcom-therapist.
- **Fix:** Replace with voice-specific reframe.

**M12. Naming collisions.**
- "Dr. Marcus Webb" (Ch10 childhood therapist) shares name with "Marcus Webb, 9, Concord" (Ch12 coma victim). Rename child victim → "Marcus Hale" or "Marcus Walsh."
- "Mr. Alistair" (Romanian collector, Ch14-16) shares first name with "Dr. Alistair Finch" (Ch24 Toronto thesis advisor). Rename advisor → "Dr. Robert Finch" or "Dr. Henry Finch."
- "Silas Blackwood" (Ch23 Nova Scotia old-timer) shares surname with the antagonist family. Lampshaded in prose but still confusing. Rename → "Silas Renault" or "Silas Burke."

**M13. "Puppet master / mastermind operating from the shadows" language in Ch07.**
Telegraphs the Fairchild reveal ten chapters early. Also appears as reader-facing narrator voice.
- **Fix:** Make Maya's Ch07 unease procedural, not thesis-statement. "The forgery was too good. Patricia too well-sourced. Something about the commission file bothered her, and she didn't yet have the word for it."

**M14. Act 1 "act-boundary" self-references.**
Ch09 ends with "Act One of her investigation was ending"; Ch10 opens with "Act Two of her investigation had begun." The narrator is literally labeling the book's structural beats.
- **Fix:** Cut both.

**M15. Repeated cross-chapter constructions.**
- "The temperature in the room seemed to drop [ten degrees]" — Ch02, Ch03, Ch04 (identical in Ch03/Ch04).
- "Sharp as [winter/a blade/winter ice]" — 5+ times across Ch01-Ch06.
- "The hunt was/wasn't over. It had just Y" — Ch13, Ch14, Ch16, Ch19 endings use the same construction.
- "Footsteps pacing back and forth, back and forth" — Ch02 and Ch03.
- "A sense of purpose" — Ch07 and Ch08.
- **Fix:** Keep one of each; vary the rest.

**M16. Ch07 / Ch08 openings use identical template: "[setting] felt like a different world from [previous setting]."**
- **Fix:** Vary one.

**M17. Ch25-Ch28 severe under-writing.**
Ch25=991, Ch26=1081, Ch27=781, Ch28=676 — 3,529 words total for the entire Geneva climax + one-year-later epilogue. Ch27 (action climax) is the shortest non-epilogue chapter in the book.
- **Fix (in concert with C7 grounded-PI reframe):** Expand Ch25 → 1,800; Ch26 → 2,000; Ch27 → 1,800; Ch28 → 1,500. Scene-work expansion, not padding.

**M18. Ch20 Maya-Sarah friendship under-written.**
Story.md Known Issue #14. Sarah gets roughly 3 sentences in the chapter that establishes the book's emotional spine.
- **Fix:** Add 200-300 words of Maya-Sarah friendship inside the flashback — a scene of them alone in the Cathedral cave, drawing or storytelling, before Ethan and Tommy join.

**M19. Ethan's voice convergence (Ch26 performs; voice card says "never performs").**
Ch25 Ethan is spare ("I had a lot of time to plan") and matches card. Ch26 Ethan rambles in five-to-seven-sentence literary monologues ("burn their monstrous world to the ground"). Under the grounded-PI reframe, Ethan's register should stay Ch25-style throughout.
- **Fix:** Rewrite Ch26 Ethan dialogue to spare register — shorter sentences, more silences, Maya doing more of the argument.

**M20. Fairchild motive grounding.**
Per story.md Known Issue #15 and Strategic Reframe. Current lines ("Genetically compatible, neurologically perfect," "digital tombstone," "He was trying to get his son back. Over and over again") edge toward operational SF.
- **Fix:** Add explicit grounding lines framing the "consciousness preservation" as a billionaire's delusion. Ethan in Ch25: "He believed it would work. It never would have. Sarah would have died for a delusion." Kim in Ch17: "The 'consciousness data' is noise. No one could restore anything from this. Fairchild paid for a ritual, not a technology." Ch19 shrine described as "a ritual space, not a laboratory."

**M21. "This is some MK-Ultra level shit" / "MK-Ultra was sloppy. Dr. Richard perfected it." (Ch12).**
Two agents fan-casting the antagonist's craftsmanship inside a rescue of sedated children. Tone-deaf.
- **Fix:** Cut the exchange entirely. Replace with a silent beat as the extraction team works.

**M22. Kim's breakthroughs are off-screen past-tense declarations.**
"I cracked it" / "We got it" appear 3+ times as already-solved announcements. Drama is in the doing.
- **Fix:** At least one Kim breakthrough (recommend Ch17) is dramatized mid-struggle — he's failing, tries a new angle, succeeds on-page.

**M23. Motif catalogs near Act 3 endings.**
- Ch18: "The digital offering... The physical offering... A yearly tribute..." (three-term enumeration of established images)
- Ch22: "The ghost. The architect. The other survivor." (three-term enumeration)
- Ch25: "Ethan, the ghost, the survivor, the monster, the savior, stood before her." (four-term identity list)
- Ch26: "the key to a global conspiracy, the ghosts of twenty-three stolen childhoods, and the weight of an impossible choice." (three-term enumeration)
- Ch28: "She thought of Tommy... She thought of Sarah... And she thought of Ethan..." (three-term enumeration)
- **Fix:** Cut every enumerated motif catalog. Single specific image per ending.

### MINOR

**m1.** Ch01 line 33 typo: "who'd though" → "who'd thought."
**m2.** Maya's drawl "explanation" meta-sentence at Ch01:33, Ch02:39, Ch08:11 (narrator tells us the drawl is emerging). Cut the meta-commentary. Trust the reader.
**m3.** Maya's Ch03:73 and Ch04:85 drawl rendered as "threatening to emerge and fought to keep it down" — telling not showing. Dramatize the suppression through the dialogue's pressure.
**m4.** Patricia Valdez voice is indistinguishable from Martinez/Kim procedural register. Add a lawyer tell — one formal "counsel" or "I would note."
**m5.** "The way [pronoun] [verb]" tic appears Ch05 (Maya), Ch15 (Martinez), Ch22 (Martinez twice). Replace at least two.
**m6.** Maya thinking in aphorisms (Ch17 "mapping its footsteps," Ch22 "He's a ghost long before the summer was over," Ch24 "He wasn't building a life; he was building a weapon"). Character-as-novelist — de-novelize to investigator register.
**m7.** Eleanor Ch14 "stammered" — Eleanor's voice card allows teacup-rattle and single-word stumble, not stammer. Replace.
**m8.** "Temperature in the room seemed to drop ten degrees" × 3 chapters. See M15.
**m9.** Ch06 Park arrests Dr. Richard for MURDER before Tommy's body has been exhumed, Sarah's autopsy reopened, or the cave children found. Procedurally impossible. See C2.
**m10.** Ch13 Dr. Richard escape plausibility — add a single line: he slipped out through a service tunnel during the cave breach.
**m11.** "The hollow shore" phrase first seeded in Ch09 per story.md states Ch08-09. Minor timing drift.
**m12.** Ch08 lines 37-47 FBI "specialized consultation program" pitch reads as series-hook bait. Cut the meta-pitch.
**m13.** Ch28 opening paragraph is 7-sentence global-aftermath summary. Paragraph sprawl + info-dump. Split and dramatize.

---

## Deliverable B — Publisher & Reviewer Panel

### 1. Acquisitions Editor (Big Five imprint)

Pass, with a polite ask-to-resubmit after major revision. This manuscript is not acquirable in its current form, and the single most disqualifying fact is the word count: at ~41,000 words it is structurally a novella, and the 2026 adult psychological-thriller market begins at 80,000 words and hits its sweet spot around 85-95K. I cannot take this to an acquisitions meeting. The jacket copy is genuinely compelling — PI with suppressed trauma hired under forged stationery onto a Gothic Maine island where she was abused as a child — and the opening pages are strong (Captain Murphy's foreshadowing in Ch1 is earned, the déjà-vu trigger is well-placed, and Eleanor's "I did no such thing" is a real hook). I would read a query with this premise. But I cannot sign a 41K-word psychological thriller, and the gap is not a line-edit gap; it is a full developmental re-draft.

What excites me is the Ch1-7 architecture: the false-commission reveal is a proper genre hook, Maya as both-investigator-and-victim is a real commercial spine, and the Morrison-family-as-true-clients turn is a clever inversion of the PI setup. What concerns me past that, beyond wordcount, is genre fracture. The book I'd pitch from Chapters 1-6 is a Tana French / Gothic atmospheric thriller; what I actually get by Chapter 19 is a Dan Brown digital-warfare / AI-consciousness-preservation cryogenic-pod shrine thriller; and what I get by Chapter 27 is a Mr. Robot hacktivism climax in a Geneva orchid conservatory. These are three different jackets. The Gothic register is what I could sell; the cryogenic-pod / logic-bomb / consciousness-vessel architecture reads as YA-dystopia/sci-fi adjacent and will not be comped to the three authors listed. Arthur Fairchild's motive — recreate his dead son via harvested child consciousness — is, bluntly, camp in this register, and the book does not do enough work to ground it as a wealthy madman's delusion rather than as an operational reality within the world of the novel.

On comps: French / Flynn / Atkinson is an aspirational cocktail that the current prose cannot cash. French's lyricism lives in the language at the sentence level, not in the fog-on-the-ferry opening image; the prose here is competent but not lyrical — it tells me about atmosphere rather than achieving it. Flynn's sharpness is almost entirely absent; Maya's interiority never has Flynn's acid wit, and the Blackwood family scenes are melodrama rather than Sharp Objects-grade family dysfunction. Atkinson's braided plotting is gestured at but not executed — the 25-year conspiracy is summarized rather than unfurled. More credible comp shelf: *The Searcher* (French on a thinner day), Riley Sager, Lisa Jewell's atmospheric thrillers, Shari Lapena. The Maya-PI-with-trauma archetype is crowded and Maya is not yet differentiated enough from that sea — her Southern drawl is the intended differentiator but it is barely executed in the actual prose. I would request a full at 85K words with the tonal register held and the Fairchild architecture reframed or amputated. Not before.

### 2. Developmental Editor

The arc on paper is strong — investigator → victim → survivor → advocate → arbiter — and Maya's Ch14 phone call with her parents is, structurally, the best beat in the book: the moment where the case stops being external and becomes the family-loyalty theme made flesh. Ch6's hostage sequence is a genuine Act 1 climax and Ch20's present-tense flashback is exactly the right structural choice. But the arc as executed collapses in Act 3 because you have compressed a four-stage transformation into a word count that cannot hold it. The "arbiter" stage — Maya as the sole moral authority over twenty-three stolen childhoods — needs the weight of an entire Act 3. You give it one chapter of debate (Ch26, 1,081 words) and one chapter of execution (Ch27, 781 words). The reader is told Maya is transformed; the reader is never made to live the transformation.

The pacing diagnosis is simple: the book's mass is front-loaded and its stakes are back-loaded. Ch1-9 (the island arc) averages ~2,200 words; Ch20-28 (the plot's entire climax plus epilogue) averages ~1,000 words. Ch27, the action climax, is the shortest non-epilogue chapter in the book. The Geneva sequence (Ch25-27) is the thesis of the novel — the moral climax, the action climax, and the final redemption of Ethan — and it is 2,853 words. For comparison, Ch2 (a dinner-party establishing chapter) is 3,083. That is a structural defect that cannot be line-edited out; Act 3 needs to roughly triple. Additionally, Ch17 ("Ghost in the Machine") and Ch22 ("Ghost in the Machine") share a chapter title.

Character-level: Sarah-as-absence is working — the journal fragments, the "Maya knows" note, the final Ch25 "she was the harvest" reveal — but her felt presence is mostly narrated, not dramatized. Ethan's 25-year long con has a plausibility problem that the book does not solve. A twelve-year-old who escaped into a side tunnel, was adopted into a Nova Scotian artisan collective under the alias "Leo," groomed by Fairchild into his digital architect, executed a multi-decade plan to route a forged commission through the Morrisons' lawyer in order to put eight-year-old Maya on Blackwood Island at thirty-five — this is a staircase of coincidences the book presents rather than earns. The Fairchild/Ethan architecture coheres as an outline but, on the page, reads as scaffolded retcon: Fairchild is introduced in Ch17 and fully deposed by Ch19, two chapters later. That's not a mastermind; that's a mid-boss. Missing scenes this developmental editor would insist on: (1) at least one full chapter of Maya living with her eight-year-old selfhood after Ch20; (2) a scene from Ethan's POV that earns his long con rather than having him narrate it in Ch25; (3) a Sarah journal chapter in the first act, in Sarah's voice; (4) a middle-act chapter in which Dr. Richard is *not* already caught — he is captured in Ch13, then reappears only in a single interrogation (Ch15), which starves the book of its best antagonist; (5) at least two additional Act 3 chapters.

### 3. Copy Editor

Mechanical baseline is not rescuable with a light pass. 159 em-dashes against a zero target is not a style choice — it is a habit, and it is the manuscript's most visible prose tic. 85 forbidden dialogue tags across 26 chapters means almost every chapter has at least three violations. Twenty-five+ of twenty-eight chapters end on an aphoristic thesis sentence — that is near-universal landing on a fortune-cookie closer, which is an AI fingerprint and a publisher-readability alarm in equal measure. Paragraph-length violations are distributed throughout; Ch15 has at least four paragraphs exceeding the 5-sentence cap. Oxford commas are consistent, which is the one thing I can compliment.

Recurring prose tics, with evidence. **Trait-word accumulation** — Ch1 deploys "professionally neutral," "methodical building," "investigator's instincts," "cataloging details." Ch15 gives us "calm and steady," "perfect," "sterile," "professional neutrality," "cold and clinical," "chilling, pitying calm." **Hedge-phrase habit** — "something twisted in her stomach," "something shifted in his face," "a sensation she couldn't name," "something like recognition." These "something + verb/like" constructions appear 36 times. **Similes on the nose** — "like a lifeline that could become a death sentence," "blood splattered across the marble floor — red against white, like truth against lies," "like metal skeletons," "like a digital onion." **Adverbial stacking on dialogue** — "said softly," "asked carefully," "said quietly," "whispered urgently." **"The X was a Y" thesis openers** — "The Orchid Room was a beautiful prison," "Geneva was a city of impossible precision," "The convoy moved through the Wyoming dawn like a funeral procession." **Ch12's** "This is some MK-Ultra level shit" / "Dr. Richard perfected it" — dialogue congratulating the antagonist inside a rescue scene.

Remediation plan, ordered by blast radius: (1) Global pass: delete every em-dash. (2) Global search-and-replace for dialogue tags. (3) Endings pass: keep 2-3 aphoristic, cut the rest. (4) Hedge-phrase pass. (5) Trait-word pass. (6) 5-sentence paragraph cap. (7) No more than 3 metaphorical "The X was a Y" openers total. (8) Dedupe chapter titles.

### 4. Genre-Savvy Beta Reader

I wanted to love this and for the first six chapters I did. The ferry, the mist, Captain Murphy ("Some places, they hold onto things"), the false-commission reveal, the blue wallpaper déjà vu, the basement child files, the Ch6 hostage standoff — I was locked in. When Maya told Detective Park "Basement. Secret room behind the basement wall. Child victim. Come now," I said out loud "holy shit." That is earned tension. The Emma Washington "The lady from the dreams. You came back for us" line in Ch12 is the scene that worked hardest and landed hardest. Ch14's phone call with her parents was the second punch. Those two scenes are the book's heart and they are real.

I lost the book in three specific places. The first was Ch17's Arthur Fairchild reveal. I'd been reading a Gothic Maine murder mystery for two hundred pages and suddenly I'm being told the real villain is an 88-year-old tech-philanthropist AI-consciousness pioneer who's been funding this for 25 years to resurrect his dead son by transplanting his consciousness into harvested children. Reader, I laughed. I never believed Fairchild. He feels like a boss fight imported from a different book, and when we meet him in Ch19 and he's listening to Bach's Cello Suites waiting for the FBI to arrive, I rolled my eyes. He has a cryogenic pod shrine of a mannequin of his dead son in a sub-level lab under a Persian rug pressure plate. This is *Saw VIII*. The second place I lost the book was Ch22-24, because it's 3,500 words of "Maya flies to a new country, interviews one person, finds a breadcrumb, flies to the next country." It reads like synopsis. The third place was Ch25's Ethan reveal — the "I had a lot of time to plan" line is trying to land as Keyser Söze but lands as Bond-villain-speech.

Did the epilogue work? Partly. The beat of Maya walking the shore with her parents and skipping a stone earns the book's title. But the last line ("The past was not a ghost to be exorcised, but a shore to which she could always return, whole and unafraid") is a line a book writes about itself rather than a line a book earns, and it broke the spell for me in the final sentence. The thing I keep coming back to: if the book had been the island, plus the caves, plus the parents' confession, plus Maya making peace with Emma and with her own memory — with Dr. Richard as the sole antagonist, without Fairchild and without Ethan's long con and without Geneva — I would have recommended it to three friends this week. Instead I have to say "the first half is great, and then it gets weird."

### 5. Adversarial Reviewer

The book's fatal tell is the chapter-endings pattern. Twenty-five+ of twenty-eight chapters end on a thesis sentence — an aphorism, a "And X was Y" declaration, a philosophical summary of the scene just read. Ch1: "a half-remembered nightmare finally coming into focus." Ch6: "She was leaving as someone who had finally faced it — and won." Ch14: "her own hunt... had just begun." Ch17: "And now, they had his name." Ch19: "There was one more ghost to find." Ch25: "He had given her back her past. Now he was asking her to decide the future of twenty-three others." Ch27: "It was the chaos of justice." Ch28: "The past was not a ghost to be exorcised, but a shore to which she could always return, whole and unafraid." This is not a voice. It is a model doing what models do — ending every unit on a resolving summary sentence, because resolution feels like craft. It isn't craft. It is the opposite of craft, because it tells the reader what the scene meant instead of trusting the scene to mean it. Cut twenty-two of those twenty-five, and the book immediately reads more human.

Is the Ch28 closer a genuine earned ending or thesis scaffolding? Thesis scaffolding. Cut it. The stone-skipping gesture is the ending. The book ends on the stone hitting water. Period. Done.

The fatal flaw, named: this manuscript does not know what kind of book it is. It opens as French/Gothic island thriller (beautifully, for about sixty pages). It pivots to Flynn-style family dysfunction thriller (passably, for another forty). Then at Ch17 it re-genres into a Dan Brown / digital-espionage / AI-consciousness-conspiracy thriller — and in doing so abandons every instrument it tuned in the first half. Maya's Southern drawl, the book's defining voice signature per the style guide's *critical* rule, is essentially invisible in Acts 2 and 3. I counted: Ch1 has "Lord have mercy," Ch6 has "Some promises are meant to be broken" (dialogue, earned), Ch8 has "Lord have mercy," Ch12 has "Lord have mercy," Ch26 has an adverb claiming the drawl sharpens ("her Southern drawl sharpening with the edge of her anger") but the dialogue that follows contains no drawl markers whatsoever. The voice-card rule is lip-service. The book tells us Maya is drawling; it does not let her drawl. In Ch27, the action climax — Maya's on-the-hunt peak stress — her dialogue is generic thriller protagonist: "I am a deputized consultant with the Federal Bureau of Investigation." That is a CBS procedural. If the Southern drawl under stress is *the* thing that differentiates Maya from every other trauma-scarred female PI in the market, and the book does not execute it when the stress is maximum, the book has not built its protagonist.

Specific passages that embarrass the book. Ch12: "This is some MK-Ultra level shit." "Worse. MK-Ultra was sloppy. Dr. Richard perfected it." This is two professionals fan-casting the antagonist's craftsmanship inside a rescue of sedated children; it is tone-deaf. Ch15, Dr. Richard's villain speech: "They are patrons! Visionaries! They understand that what I create is art. A gallery of perfect, untarnished souls, more beautiful than any Rembrandt or Da Vinci!" The exclamation points are a confession; no character who has successfully run a consciousness-preservation conspiracy for twenty-five years speaks like this. Ch17's reveal: "The entire war room fell silent" — "It's the passphrase," Maya breathed — "And a name appeared. **ARTHUR FAIRCHILD**." That is a screenplay beat rendered in prose, bolded all-caps. Ch19's Fairchild arrest: the 88-year-old mastermind sitting in a leather chair listening to Bach's Cello Suites when the FBI walks in — cryogenic shrine, Persian rug pressure plate. Ch25 Ethan: "I had a lot of time to plan." Ch26 Ethan remembering Tommy: "He... he taught me how to skip stones. He said the secret was finding the flat ones." Sentimentally perfect, psychologically implausible, paid off four chapters later when Maya skips a stone herself. The parallel is so architected it squeaks. The thing I cannot say is "with revision this could be publishable," because the revision required is not polishing — it is choosing. Choose the French/Flynn book or the Dan Brown book. Cut the other one.

**The user has chosen** (per possible.md): this is Book 1 of a traditional-detective series. The Dan Brown book gets cut. Grounded PI debut. That is the fix.

---

## Deliverable C — Book-Specific Validation Matrix

### 8a. Plot Sequence Verification

| # | Event | Stated Ch | Actual | PASS/FAIL | Notes |
|---|---|---|---|---|---|
| a | Sarah's death reclassified murder | Ch 4/7 | ch04:55 / ch07:9 | PASS | |
| b | Maya's first déjà vu | Ch 1 | ch01:34 | PASS | |
| c | "Not hired by the family" reveal | Ch 1 | ch01:87 | PASS | |
| d | Morrison commission revealed | Ch 7 | ch07:27 | PASS | |
| e | FBI consulting begins | Ch 7/8 | ch07:115 / ch08:3 | PASS | |
| f | "Hollow shore" pattern discovered | Ch 8-9 | ch09 only | PARTIAL | Ch08 never uses the phrase; only Ch09 |
| g | Return to island with FBI | Ch 11 | ch11:5 | PASS | |
| h | Cave entrance found | Ch 11 | ch11:51 | PASS | |
| i | 18 children rescued | Ch 12 | ch12:69 | PASS | |
| j | Tommy full memory | Ch 12 / Ch 20 rendered | ch12 + ch20 | PASS | |
| k | Dr. Richard captured | Ch 13 | ch06:137 AND ch13:127 | **CRITICAL FAIL** | Double-arrest. Ch06 arrest must be removed (see C2). |
| l | Eleanor arrested | Ch 13 | ch06:153 AND ch13:49 | **CRITICAL FAIL** | Double-arrest. Ch06 arrest must be removed. |
| m | Nightingale Fund decoded | Ch 16/17 | ch16:41 / ch17:33 | PASS | |
| n | Fairchild identified | Ch 17 | ch17:45 | PASS | |
| o | Fairchild raid | Ch 19 | ch19:35 | PASS | |
| p | Ethan identified | Ch 21 | ch21:51 | PASS | |
| q | Nova Scotia → Toronto → Geneva | Ch 23/24/25 | all correct | PASS | |
| r | Orchid Room meeting | Ch 25 | ch25 | PASS | |
| s | Logic bomb / third option | Ch 26-27 | ch26:43 / ch27:13 | PASS (but cut per C7 reframe) |
| t | Network exposed | Ch 27 | ch27:17 | PASS (but reframe per C7) |
| u | Epilogue one-year-later | Ch 28 | ch28 | PASS | |

### 8b. Tracking Device / Counter Verification

All six counters (23 victims, 18 rescued, 5 dead, 23 cryogenic anchors, 25 years, $50K commission) are consistent across the manuscript. **PASS 6/6.**

### 8c. Hidden Character / Antagonist Movements

- Ethan operating secretly until Ch25: PASS
- Dr. Richard between Ch12 and Ch13: **FAIL** — invalidated by Ch06 arrest contradiction (C2)
- Fairchild digital purge Ch18: PASS
- Samuel Blackwood never reappears living: PASS
- Island geography plausible: PASS

### 8d. Outcome Rules — 6/6 PASS

All Ch28 state-table outcomes verified (Richard/Eleanor supermax, Fairchild psychiatric, Ethan digital ghost — TO BE REFRAMED to "benevolent wronged man in hiding" per C7, 18 children Trust-protected, Maya integrated). No critical failures.

### 8e. Information Asymmetry — 13/13 PASS

Who-knows-what matrix verified. No character reacts to information before they have it.

### 8f. Speech Rule Compliance

- Maya drawl: **PARTIAL PASS** — one minor Ch02:71 violation; Ch08:11 "overwhelmed" justification not in voice-card taxonomy. Mostly correct deployment. See M7 re vocabulary.
- Dr. Richard Chicago-direct: PASS
- Eleanor aristocratic-until-Ch14: **FAIL** — cracks Ch06, Ch11, Ch13 before sanctioned Ch14 shatter. See M6.
- James NY-nervous: PASS
- Captain Murphy Maine laconic: PASS
- Dr. Sarah Chen reframes: PARTIAL PASS — Ch09 "How does that make you feel?" cliche. See M11.
- Ethan spare: PARTIAL — Ch25 PASS, Ch26 FAIL. See M19.
- **Agent Martinez pronoun: FAIL** — male Ch14-19, 21; female Ch22-28. See C11.

### 8g. Recurring Text / Quotation Accuracy — 8/8 PASS

All recurring quotes verified exact.

### 8h. Setting Geography Consistency — 13/13 PASS

All spatial references consistent.

### 8i. Setup/Payoff

- Blue wallpaper Ch03 → PASS
- Hidden passages / peephole-to-cave-surveillance echo: SOFT PASS (underdeveloped)
- Sarah's journal: PASS
- Dr. Marcus Webb paper → Ch14 parents confession: PASS
- 8-year-old photo: PASS
- Carved wooden bird: **PARTIAL FAIL** — 25-year custody not explained. See C9.
- Morrison PI files → cryptographic key: PASS
- Nightingale Fund grief-donation → Fairchild: PASS
- 23 cryogenic anchors → Ch19 raid: PASS
- **Marcus Williams past-failure case: FAIL** — dropped after Ch01. See M9.
- **Maya's tapping tic: FAIL** — vanishes after Ch02. See M8.
- "Come to the hollow shore" song: PASS

### Critical Failures Summary

- **C2** (Ch06 double-arrest destroying Ch07-13 arc)
- **C9** (bird 25-year custody)
- Downstream of C2: Ch07 "I remember everything" (C6), Ch04 confessions (C3), Ch05 full flashback (C4), Ch05/Ch06 overlap (C5)
- **C11** (Martinez pronoun)
- **C1** (Ch20 past tense vs. required present tense)

---

## Deliverable D — Voice & Style Consistency Report

### D1. Voice Card Compliance Matrix

| Character | Chapters sampled | Sentence Length | Metaphor Domain | Contractions | Stress Response | Forbidden Patterns | Overall |
|-----------|-----------------|-----------------|-----------------|--------------|-----------------|--------------------|---------|
| Maya Chen (narration) | 1, 3, 6, 8, 12, 14, 15, 22, 26, 27 | Drifts: French-lyrical → bureaucratic → airport-thriller | Abstract-physical metaphor widespread | Consistent | Drawl partial; tapping tic lost after Ch02 | "seemed to" 23×; "the way X verb" | **FAIL** |
| Dr. Richard Blackwood | 2, 3, 4, 6, 13, 15 | Medium/long correct | Medical/therapeutic → commercial | Heavy contractions | Chicago-direct correctly deployed | Ch15 "snarled"/"roared" forbidden tags | **PASS** with one violation |
| Eleanor Blackwood | 1, 2, 3, 6, 11, 13, 14 | Complete sentences correct | Aristocratic/formal | Formal minimal | **Composure cracks Ch06, Ch11, Ch13 before sanctioned Ch14 shatter** | Ch14 "stammered" wrong tag | **FAIL** |
| James Blackwood | 1, 2, 3, 6, 7, 11, 13 | Nervous/ramble/self-interrupt correct | Nervous/emotional | Heavy contractions | Clipped when defending Sarah — correct | None notable | **PASS** |
| Detective Park | 1, 6, 7 | Short professional | Law-enforcement idiom | Standard | **Atlanta Southern drawl absent from prose; voice card unrealized** | None | **FAIL** |
| Agent Martinez | 8-19, 21-28 | Short-to-medium efficient | Military/procedural | Standard | Female per card; **male pronouns Ch14-19, 21** | "low rumble/growl" used 3× | **FAIL** |
| Agent Kim | 8, 11, 12, 13, 16, 17, 18, 22, 27 | Short technical | Digital/academic | Standard | Glasses-push tic Ch22; Ch27 "Lord, Maya" signature lands | Ch17 "trembling with excitement" breaks flat-academic | **PARTIAL PASS** |
| Captain Murphy | 1, 11, 13 | Short laconic correct | Folk-wisdom / sea / ghost | Minimal | Accent thickens with grief — correct | None | **PASS** (best-realized supporting voice) |
| Margaret Swift | 2, 3, 11 | Short plainspoken | Domestic | Standard | Flat cautious — correct | None | **PASS** |
| Dr. Sarah Chen | 7, 8, 9, 16 | Medium measured | Clinical reframing | Standard | Signature "you can't pour from an empty cup" lands; "How does that make you feel?" Ch09 cliché | None structural | **PARTIAL PASS** |
| Arthur Fairchild | 19 | Medium refined | Aesthetic/art/garden | Minimal | Shattered-king grandeur correctly deployed | None | **PASS** (best antagonist voice) |
| Ethan Renault | 25, 26 | Ch25 spare; Ch26 literary-performing | Philosophical/shadow/mercy | Standard | Ch25 hits card; **Ch26 rambles TV-villain cadence** | Ch26 "shot back, voice rising" breaks "never performs" | **FAIL** |

### D2. Strip-the-Name Blind Test

Sample A (ch01:p1): *"The ferry's engine thrummed beneath Maya Chen's feet, a steady, low pulse..."* — French-lyrical register, sensory-embodied. **Ch01 Maya (voice card).**

Sample B (ch14:p1): *"The FBI's Portland field office was a maelstrom of controlled chaos..."* — bureaucratic compression, abstract metaphor. **Ch14 Maya (drifted).**

Sample C (ch27:p3): *"The world exploded in a cacophony of sound and light..."* — techno-thriller cadence. **Ch27 Maya (drifted).**

**Verdict: Partially converged / significant drift.** Sample A is the Maya of the voice card. Samples B and C are generic thriller prose. A reader tracking only the POV character's rhythm would have trouble proving Sample B or C came from the same interiority as Sample A.

Dialogue blind test (Dr. Richard / James / Eleanor / Fairchild / Ethan): all five identifiable from prose rhythm at their best moments. **Verdict: Distinct** in dialogue, **Converged** in narration.

### D3. Drift Report — Maya Chen

**Ch01 → Ch14 → Ch27: Significant drift.**

- Sentence-level texture shifts from sensory-embodied → abstract-declarative → screenplay-beat compression.
- Interior register shifts from French-flavored observation → dissertation → near-zero interior.
- Physical tics (finger-tap, phone-check) lost after Ch02.
- Southern cadence at baseline lost; the drawl-under-stress tell has no baseline contrast.
- Metaphor-domain shift from environmental/sensory → abstract-physical → compressed-action.
- Sentence length: ~28 words/avg (Ch01) → ~18 (Ch14) → ~15 (Ch27).

The drift is significant, cumulative, and genre-correlated. As the book escalates from island mystery to global conspiracy, the prose abandons its comp-title register and drifts toward airport-thriller pacing.

### D4. Dialogue Voice Report

| Character | Distinct? | Sample | Ch | Notes |
|-----------|-----------|--------|-----|-------|
| Maya (drawl mode) | Y | *"Some promises are meant to be broken"* | 6 | Best voice moment in the book |
| Dr. Richard | Y | *"Memory is such a fragile thing, isn't it?"* | 2 | Most recognizable villain voice |
| Eleanor | Y baseline, drifts Ch6+ | *"Someone has gone to extraordinary lengths to bring you here, Ms. Chen."* | 1 | Card hit in Ch01, drifts from Ch06 |
| James | Y | *"I enabled a monster for twenty years because I was too weak to face the truth."* | 7 | NY-direct in resolve mode |
| Detective Park | N | *"Danny Morrison. He's Tommy Morrison's nephew."* | 7 | Generic LE. Zero Atlanta Southern |
| Captain Murphy | Y | *"Some places, they hold onto things."* | 1 | Best-realized supporting voice |
| Agent Martinez | N | *"Welcome to the hornet's nest"* (male) vs *"That leap you just made..."* (female) | 14/22 | Pronoun and voice inconsistent — two characters one name |
| Agent Kim | Y partial | *"Lord, Maya, what did you do?"* | 27 | Signature lands |
| Dr. Sarah Chen | Y | *"You can't pour from an empty cup."* | 7 | Signature delivered; Ch09 cliché dip |
| Fairchild | Y | *"I do hope you haven't damaged my front door."* | 19 | Strongest antagonist voice |
| Ethan | Y Ch25, N Ch26 | *"I had a lot of time to plan"* (25) vs rambling Ch26 | 25/26 | Inconsistent across two appearances |
| Emma Washington | Y | *"The lady from the dreams. You came back for us."* | 12 | Child-survivor register, distinctive |
| Mark Morrison | Y | *"They told us we were crazy. Obsessed."* | 17 | Quiet, determined, clipped |
| Patricia Valdez | N | *"The FBI wants to offer you a consulting position. Your unique perspective..."* | 7 | Indistinguishable from Martinez/Kim |
| Silas | Y | *"Well, I'll be. The boy's work. Haven't seen one of these in twenty years."* | 23 | Maritime-Canadian well-executed; **name collision** (Silas Blackwood) |

### Convergence anti-patterns found (per SKILL §4.4)

1. Literary default: Martinez gets novelistic lines in Ch22; Kim gets literary closer in Ch17.
2. Abstract-physical metaphor: "X was a Y" construction across multiple voices.
3. "The way [pronoun] [verb]" appears in Maya, Martinez ×2, narration — three characters share this tic.
4. Character-as-novelist: Maya thinks in aphorisms (Ch17, Ch22, Ch24).
5. Uniform sentence complexity across Martinez, Kim, and Ch26-Ethan.

**Severity:** Voice convergence Major; Maya drift Major (affects 70%+ of chapters).

---

## Deliverable E — Fix Plan (Prioritized, For Immediate Execution)

### Phase 1: Critical structural (must land first)

1. **Ch06 rewrite:** Dr. Richard flees during the Park arrival; Eleanor stays composed; no murder charges; no "we've been building a case." (C2)
2. **Ch20 present-tense conversion:** Full chapter rewrite in present tense, plus 200-300 word Maya-Sarah friendship expansion, plus closing paragraph establishing the bird's 25-year custody. (C1, M18, C9)
3. **Ch04 confession pull-back:** Dr. Richard menaces but does not confess. Maya holds accusations internally. (C3, C12)
4. **Ch05 flashback pull-back + Ch05/Ch06 overlap cleanup:** Ch05 ends at discovery of hidden room with unconscious boy. No Tommy-murder full-flashback; no "Choose, Maya" ultimatum (that's Ch06). (C4, C5)
5. **Ch07 memory pull-back:** Maya says "fragments — more every hour," not "I remember everything now." (C6)
6. **Act 3 grounded-PI reframe (C7):** 
   - Ch17-19: Fairchild's motive as private delusion; Kim line confirming "consciousness data" is unrestorable noise.
   - Ch19: cryogenic shrine as ritual space, not laboratory.
   - Ch25: Ethan spare throughout; "He believed it would work. It never would have. Sarah would have died for a delusion."
   - Ch25-27: remove logic bomb, master key, digital warfare. Replace with raid + interrogation mechanics.
   - Ch27: Maya triggers a raid on Fairchild's remaining cells via the evidence she's assembled, not a phone-hack. Global data release via FBI/prosecutors, not a Mr. Robot-style network takeover.
7. **Martinez pronoun fix (C11):** Global find/replace Ch14, 15, 16, 18, 19, 21.

### Phase 2: Mechanical sweeps

8. **Em-dash sweep (M1):** 159 → 0. Most exposition em-dashes → commas, colons, periods, parentheses. Dialogue interruptions → period-separated fragments.
9. **Forbidden dialogue tag sweep (M2):** 85 → 0. Every non-said/asked tag → action beat or "said."
10. **Aphoristic ending sweep (C8):** Rewrite 22+ chapter endings to images/actions/silence. Keep 2-3 aphoristic max.
11. **"Suddenly" sweep (M3):** 15 → 0.
12. **Hedge/trait-word sweep (M4, M5):** reduce counts by 70%+.
13. **Repeated construction fixes (M15):** one use of "temperature seemed to drop," one "sharp as winter," one "hunt was over / just begun." Vary the rest.

### Phase 3: Character voice repairs

14. **Maya drawl vocabulary (M7):** Distribute the full voice-card phrase list.
15. **Finger-tap tic restoration (M8):** Ch08, 11, 12, 14, 15, 17, 22, 26.
16. **Marcus Williams thread reinstatement (M9):** Ch14, 15, 26 invocations.
17. **Detective Park voice (M10):** Ch06 or Ch07 shared-Southern idiom exchange.
18. **Eleanor composure restoration (M6):** ch06 scalpel-cold, ch11 cool enamel, ch13 cold contempt (no "Richard went too far" admission).
19. **Ethan Ch26 spare rewrite (M19):** shorter sentences, more silence, no literary monologues.
20. **Dr. Sarah Chen Ch09 cliche replacement (M11).**
21. **Patricia Valdez lawyer tell (m4).**

### Phase 4: Continuity repairs

22. **Title duplication (C10):** Ch22 → *"The Patient Watcher"*.
23. **Naming collisions (M12):** Marcus Webb child victim → Marcus Hale; Dr. Alistair Finch → Dr. Robert Finch; Silas Blackwood → Silas Renault.
24. **Act 1 boundary self-references (M14):** Cut from Ch09 and Ch10.
25. **"Puppet master" telegraphing (M13):** Ch07 fix.
26. **Ch02/Ch03 dinner-redundancy (C13):** Ch03 compresses.
27. **"Some promises are meant to be broken" previews (C14):** Strip from Ch03, Ch04.
28. **Ch13 Dr. Richard escape plausibility (m10):** one line re service tunnel.

### Phase 5: Expansion (if time permits this pass)

29. **Ch25 expansion (M17):** 991 → 1,800.
30. **Ch26 expansion (M17):** 1,081 → 2,000. Ethan's counter-arguments to the third option.
31. **Ch27 expansion (M17, C7):** 781 → 1,800. Raid mechanics, interrogation, grounded climax.
32. **Ch28 expansion (M17):** 676 → 1,500. Parents reconciliation scene; specific rather than summary.

### Execution note

Full convergence in one pass is not realistic given the scope of C7 (grounded-PI reframe) and Phase 5 (expansion). This pass prioritizes Phases 1-4 (Critical structural + Mechanical + Voice + Continuity). Phase 5 expansion will be the focus of Pass 2.

---

## Convergence Criteria Status

- Zero open Critical: **14 open** (C1-C14)
- Zero open Major: **23 open** (M1-M23)
- Mechanical budgets met: **NO** (em-dashes 159/0, forbidden tags 85/0, aphoristic endings ~25/3, paragraphs-over-5 numerous)
- Five reviewer personas sign off: **NO** — all five find substantial work remaining
- Book-Specific Validation Matrix PASS: **NO** — 8a has 2 CRITICAL failures (C2), 8c FAIL, 8f FAIL (Eleanor + Martinez + Park), 8i FAIL (bird + Williams + tapping)

**Manuscript has not converged. Proceeding to fix pass.**
