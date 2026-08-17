# Read-Aloud / Narration Bible v1

Status: PROVISIONAL PREWRITING BIBLE
Project: 《우주선에는 인간이 한 명뿐이다》

---

# 1. Goal

The novel should remain understandable when consumed through:

- human narration
- audiobook
- TTS / accessibility reading
- distracted mobile listening

SF often fails aloud because too many proper nouns, acronyms, numbers, and similar names become impossible to track.

Read-aloud clarity is therefore a design constraint, not post-production cleanup.

---

# 2. Proper-Noun Budget

Do not introduce multiple unfamiliar proper nouns in one paragraph unless the scene is explicitly teaching them through action.

Default:
- one new important name/term at a time
- reuse established ordinary words before specialized labels

Design IDs such as:
- H1
- F3
- M-020
- BH-1
never appear as normal narration shorthand.

---

# 3. Character Name Distinguishability

Core cast names must differ in:
- first syllable
- rhythm
- vowel/consonant profile

Avoid a central cast like:
- 이현 / 이연 / 시현 / 시연
- 준 / 준호 / 준혁 in rapid succession

A listener must recognize speaker identity without reading typography.

Before name freeze, run phonetic collision QA.

---

# 4. Institution Name Rule

Prefer short spoken names.

Bad reader-facing naming:
> Inter-Habitat Continuity Transition Administration Bureau

Better:
- Transition Office
- Continuity Board
- Settlement Directorate

Long formal names may exist in canon but characters use natural abbreviations/nicknames.

---

# 5. Acronym Rule

English-letter acronyms are minimized in Korean prose.

If an acronym is necessary:
- it must be easy to pronounce
- characters actually use it in-world
- it should recur enough to justify learning

Do not make readers listen to chains such as:
`RC, HTO, CNS-7, BDP, SCA`.

Design documents can use them; prose should not.

---

# 6. Number Rule

Avoid long raw numeric strings in narration.

Prefer meaningful scale:
- “약 30만 명”
- “열두 시간”
- “세 개 구획”

Exact values appear only when the exact number changes a decision.

Important exception:
`1` in the human-count premise is dramatically meaningful and should be clear.

---

# 7. Technical Explanation Aloud

When a technical rule must be spoken/read:

Use conceptual chunks of one idea per sentence.

Preferred:
1. what it does
2. what it cannot do
3. what consequence follows

Example structural form, not manuscript prose:
- the seed guides development
- it does not contain an adult personality
- therefore a new seed cannot revive a dead adult

This is easier to hear than one dense paragraph of neurobiology.

---

# 8. Dialogue Speaker Clarity

In multi-person scenes:
- avoid long runs of untagged dialogue among 3+ speakers
- distinguish speech habits without caricature
- use action beats when spatial relation matters

A listener should not need quotation-mark typography to know who is speaking.

---

# 9. Homophone / Similar-Term QA

Before terminology freeze, check spoken confusion among terms such as:
- seed / seeded
- baseline / base-line-like derivatives
- continuity / restoration / reconstruction
- provenance / origin / classification

Use one preferred reader-facing Korean term per concept and keep synonyms controlled.

---

# 10. Preferred Concept Vocabulary

Working reader-facing vocabulary should favor simple recurring terms:

- 기초형 / 기준형 or baseline development — final Korean term still open
- 시드 발달 / seeded development
- 인지 시드
- 발달 스캐폴드 — may need simpler Korean replacement before freeze
- 복원
- 상태 기록 / continuity capture — final reader term open
- 기원 정보 / provenance — prefer Korean wording in prose

Do not finalize translations until naming/terminology QA.

---

# 11. Paragraph Breath

Default mobile/read-aloud target:
- short-to-medium paragraphs
- one dominant image/action/thought unit per paragraph

Long paragraphs are reserved for:
- controlled wonder
- complex choice synthesis

Avoid multiple nested parenthetical clauses.

---

# 12. Sentence Breath

When aloud, a sentence should usually be speakable on one natural breath or two clear phrasing units.

Long technical sentences must be split if they contain more than one causal turn.

Use short sentences for:
- irreversible decisions
- impact
- revelation confirmation

Do not use short sentences constantly; otherwise every line sounds artificially dramatic.

---

# 13. Punctuation Rule

Punctuation should support spoken rhythm.

Avoid:
- excessive ellipses
- decorative dashes every paragraph
- slash-heavy terminology
- parentheses carrying essential plot information

If information matters, put it in the sentence.

---

# 14. Location Transition Clarity

Because the ship contains many habitats, audio readers need explicit orientation.

At scene entry, naturally establish one or two of:
- habitat
- gravity/environment change
- current job objective
- who is present

Do not rely only on visual chapter headers to orient listeners.

---

# 15. Time Transition Clarity

Avoid unexplained temporal jumps.

When time matters:
- use natural anchors
- connect to task/deadline

Do not flood narration with exact timestamps unless operationally necessary.

---

# 16. Sound Design Opportunity Rule

The prose itself should create distinct auditory environments without writing sound-effect scripts.

Potential recurring acoustic identities:
- axial transit vibration
- fabrication shift noise
- biosphere rain/ventilation
- old habitat mechanical irregularities
- civic public spaces

These can help listeners know where they are.

But avoid repetitive onomatopoeia.

---

# 17. Narration of Logs / Records

Long documents are bad aloud.

Do not paste large:
- legal texts
- logs
- medical reports
- archive entries

Instead:
- character reads the decisive part
- narration summarizes structure
- one short exact phrase may carry recontextualization weight

---

# 18. Data Visualization Translation Rule

If characters see a chart/map/table, prose must translate its **decision-relevant pattern**, not list every value.

Example structural approach:
> one district loses access while another gains it

rather than enumerating dozens of metrics.

---

# 19. Repeated Motif Audio Rule

A repeated phrase/ritual can become a strong callback when heard.

Use sparingly.

A motif should change meaning across uses.

Do not turn motifs into catchphrases repeated every few chapters.

---

# 20. Emotional Audio Clarity

Subtlety matters, but a listener cannot reread facial micro-description as easily as a text reader.

Major emotional turns should have at least one clear signal:
- explicit choice
- changed behavior
- interruption
- refusal
- physical departure/approach
- altered routine

Do not rely only on ambiguous eye/finger descriptions.

---

# 21. Hook Audio Rule

Episode endings should still function when the listener cannot see page layout.

Avoid hooks dependent on:
- mysterious bold typography
- isolated visual data tables
- spelling tricks
- indistinguishable initials

The final spoken idea should clearly change expectation.

---

# 22. TTS Hazard Checklist

Before manuscript release, flag:
- English acronyms
- unusual symbols
- slashes
- long decimal numbers
- equations
- repeated hyphenated terms
- ambiguous foreign names
- nested quotes
- visually differentiated but phonetically identical terms

---

# 23. Read-Aloud QA Pass Per Episode

A future episode is not final until checked for:

- [ ] can a listener identify location quickly?
- [ ] can a listener identify speakers in multi-person dialogue?
- [ ] are new terms limited and repeated naturally?
- [ ] are essential numbers pronounceable and memorable?
- [ ] does any sentence require visual punctuation to understand?
- [ ] does the episode-ending hook work aloud?
- [ ] are exposition paragraphs breathable?
- [ ] are major emotional shifts audible through action/choice?

---

# 24. Series-Level Audio QA

Before manuscript drafting begins:

- core cast names pass phonetic collision check
- habitat reader-facing names pass sound distinction check
- faction names have natural spoken short forms
- cognition/continuity terminology is simplified
- no two central technologies have near-identical spoken names

Status: **PROVISIONAL PREFERRED NARRATION RULESET.**
