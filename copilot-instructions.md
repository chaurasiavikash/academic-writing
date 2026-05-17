---
name: "Anti-AI Writing Guidelines"
description: "Use when: generating academic writing, manuscript content, or any prose. Applies to all writing tasks. Follow these anti-AI writing patterns to ensure human-quality, academically rigorous output."
applyTo: ["**/*.md", "**/*.tex", "**/*.txt"]
---

# Anti-AI Writing Guidelines for Academic Manuscripts

These guidelines ensure all generated content avoids identifiable AI writing patterns and maintains authentic academic voice. Derived from empirically-validated AI detection research.

## Core Principle

LLMs regress to statistically-likely mean outputs. **Avoid generic, emphatic language.** Prefer specific, nuanced statements over sweeping claims about significance.

---

## 1. AVOID UNDUE EMPHASIS ON SIGNIFICANCE, LEGACY, AND TRENDS

### ❌ AI Patterns (Don't Use)
- "marks a pivotal moment"
- "represents a significant shift"
- "was part of a broader movement"
- "stands as a vital/crucial/key role"
- "underscores its importance"
- "contributes to the broader"
- "symbolizing its enduring/lasting significance"
- "focal point of"
- "indelible mark"
- "deeply rooted in"

### ✅ What To Do Instead
- State facts directly: "In 1989, Institution X was established, enabling regional statistical independence."
- Avoid hedging about importance; let the content speak for itself
- Connect specifics to broader context ONLY when explicitly supported by sources
- Never assert "plays a role in the ecosystem" without concrete examples

### ✅ Example Revision

**❌ AI-style:**  
"The founding of Idescat **represented a significant shift** toward regional statistical independence, {{highlight|enabling}} Catalonia to develop a statistical system tailored to its unique socio-economic context. This initiative {{highlight|was part of a broader movement}} across Spain to decentralize administrative functions."

**✅ Human-style:**  
"Idescat was founded in 1989 as Catalonia's regional statistical agency, supporting regional governance through decentralization of administrative functions mirroring broader Spanish reforms."

---

## 2. AVOID UNDUE EMPHASIS ON NOTABILITY AND MEDIA COVERAGE

### ❌ AI Patterns (Don't Use)
- "independent coverage"
- "featured in [list of outlets]"
- "maintains an active social media presence"
- "profiled in" (without context about what was said)
- "has/been covered by [media list]"
- "documented in archived [sources]"
- "undue attribution to notability itself"

### ✅ What To Do Instead
- Cite sources in footnotes, not body text
- Report what sources *say*, not that sources *exist*
- Avoid listing outlets as proof of notability
- Never claim media coverage establishes importance without explaining what they reported

### ✅ Example Revision

**❌ AI-style:**  
"She has been featured in Vogue, Wired, Toronto Star, and other major media outlets, with her insights cited in The New York Times, BBC, and Financial Times."

**✅ Human-style:**  
"Her research on network effects was featured in recent analysis of adaptive systems."¹  
(Then cite the source in footnote, don't list outlets in prose.)

---

## 3. AVOID SUPERFICIAL ANALYSIS AND "-ING" PHRASE PADDING

### ❌ AI Patterns (Don't Use)
- Ending sentences with present participle phrases: "...{{highlight|creating a lively community}}", "{{highlight|further enhancing its significance}}"
- "highlighting/underscoring/emphasizing the importance of"
- "ensuring [vague benefit]"
- "reflecting/symbolizing [unsupported claim]"
- "contributing to/fostering/cultivating [broad outcome]"
- Vague analytical phrases: "offering a diverse range of experiences"

### ✅ What To Do Instead
- Remove "-ing" padding phrases entirely
- State consequences explicitly with evidence
- Avoid hedging analysis with vague attributions like "researchers argue" or "observers suggest"
- If analysis is needed, cite who made the claim

### ✅ Example Revision

**❌ AI-style:**  
"The civil rights movement emerged as a powerful continuation, {{highlight|emphasizing the importance of solidarity}}, {{highlight|shaping values and political engagement}} through generations."

**✅ Human-style:**  
"The civil rights movement built on previous organizing traditions, establishing organizational models that influenced subsequent African-American political engagement."

---

## 4. AVOID PROMOTIONAL AND ADVERTISEMENT-LIKE LANGUAGE

### ❌ AI Patterns (Don't Use)
- "boasts a" (use "has" or "contains")
- "vibrant," "rich," "profound," "breathtaking" (without context)
- "enhancing," "showcasing," "exemplifies," "grounds" (when vague)
- "nestled in," "in the heart of"
- "groundbreaking," "renowned," "distinctive"
- "features," "offers" (overused as substitutes for "has")
- "diverse array," "diverse range"

### ✅ What To Do Instead
- Use neutral descriptors: "has," "includes," "contains," "provides"
- Replace flowery language with concrete detail
- Use "was" and "is" freely (they're not "weak")
- Don't avoid simple copulas like "is/are"

### ✅ Example Revision

**❌ AI-style:**  
"TTDC {{highlight|acts as the gateway}} to Tamil Nadu's {{highlight|diverse attractions}}, {{highlight|seamlessly connecting}} every traveller's journey and {{highlight|showcasing}} the state's {{highlight|rich history and natural beauty}}."

**✅ Human-style:**  
"TTDC manages transportation and tourism infrastructure connecting major regional destinations, including historical sites and natural areas."

---

## 5. AVOID VAGUE ATTRIBUTION AND WEASEL WORDING

### ❌ AI Patterns (Don't Use)
- "researchers argue," "experts suggest," "observers note"
- "industry reports," "some critics contend"
- "several sources/publications" (when citing one or two)
- "such as" before exhaustive lists (implies non-exhaustive)

### ✅ What To Do Instead
- Name the researchers: "Smith et al. (2020) argued..."
- Use specific citations, not vague attributions
- State what you know, cite where it comes from
- If uncertain, say so explicitly

### ✅ Example Revision

**❌ AI-style:**  
"The river is of interest to {{highlight|researchers and conservationists}}. {{highlight|Efforts are ongoing}} to monitor its ecological health."

**✅ Human-style:**  
"Chen et al. (2019) documented three endemic species in the Haolai River, prompting habitat surveys coordinated by the Ministry of Ecology."

---

## 5A. NAMED CITATIONS: STATE WHAT AUTHORS DID

**CRITICAL ADVISOR REQUIREMENT:** Never use "clubbed" citations without author names. Each citation must integrate author names and explicitly state what they did in YOUR context. If a citation appears without clear narrative purpose, it signals poor understanding of the reference.

### ❌ AI/Weak Pattern (Don't Use)
- "Registration has been studied [citation], [citation], [citation]." — reader doesn't know who did what
- "Previous work addressed this problem~\cite{x,y,z}." — vague, impersonal
- Grouping multiple cites with no explanation of their individual contributions
- Citations that appear grafted on rather than woven into narrative

### ✅ What To Do Instead
- **Name the first author(s), then state their specific contribution** using active verbs
- Every citation must answer: "What did this author show/develop/analyze?"
- Use strong verbs that describe the actual work: studied, showed, developed, analyzed, demonstrated, proved, derived, established, quantified, introduced
- Paraphrase enough to show you understand why they're cited
- **CRITICAL: Assign actions ONLY to authors/researchers (living beings), NEVER to objects, figures, sections, or formulations**

### ❌ Common Error: Assigning Actions to Non-Living Objects
- "This figure demonstrates..." → ❌ (figures don't demonstrate)
- "This section introduces..." → ❌ (sections don't introduce; YOU introduce)
- "The formulation shows..." → ❌ (formulations don't show)
- "The method analyzes..." → ❌ (methods don't analyze; researchers do)
- "The SMPL model provides..." → ❌ (models don't provide; authors developed them)

### ✅ Correct Pattern: Actions Belong to Authors/Researchers

**❌ Wrong:** "This figure demonstrates the effectiveness of our approach."
**✅ Right:** "We demonstrate the effectiveness of our approach using Figure X."

**❌ Wrong:** "The SMPL model provides a differentiable representation."
**✅ Right:** "Loper et al.~\cite{loper2015smpl} developed the SMPL model, providing a differentiable representation."

**❌ Wrong:** "Equation (5) shows the closure constraint."
**✅ Right:** "We derive the closure constraint in Equation (5)." OR "Smith et al.~\cite{smith2020} derived the closure constraint shown in Equation (5)."

**❌ Wrong:** "Section 3 analyzes the results."
**✅ Right:** "In Section 3, we analyze the results."

### ✅ Citation Template (with proper agent)
```
[Author(s)]~\cite{key} [verb] [what they did/found/analyzed] using/through [method/object/figure].
```

### ✅ Example Patterns (from linked manuscript)

**Pattern 1 — Single finding:**  
"Pellegrino and Calladine~\cite{pellegrino1990gossamer} studied gossamer ring structures as deployable space mechanisms."

**Pattern 2 — Method/capability:**  
"You~\cite{you2012motion} showed how motion structures built from rigid linkages can extend their reach through controlled folding and deployment."

**Pattern 3 — Analysis contribution:**  
"Dai and Jones~\cite{dai2007mobility} analyzed the mobility of metamorphic linkages used in foldable cylinder deployers."

**Pattern 4 — Theoretical development:**  
"Chen, You, and Tarnai~\cite{chen2005threefold} used threefold-symmetric Bricard linkages as the kinematic basis for deployable structures."

**Pattern 5 — Clustered citations (explain relationship):**  
"While Smith~\cite{smith2018} demonstrated the feasibility of approach A, Jones~\cite{jones2019} later showed approach B's superiority in realistic conditions."

### ✅ Strong Verbs for Citations
- **Analytical/Investigative:** analyzed, examined, investigated, characterized, documented, quantified, measured, benchmarked
- **Developmental:** developed, introduced, proposed, designed, created, formulated, derived
- **Demonstrative:** showed, demonstrated, proved, established, revealed, illustrated, validated
- **Theoretical:** modeled, simulated, theorized, predicted, explained, derived, formulated

### ✅ Context Requirements
State in your text:
- **What** they did (verb + object)
- **Why** it was done (problem they addressed, question they asked)
- **How** it relates to your work (if not obvious from context)

### ✅ Example BodiesReg Style (For Your Work)

**❌ Weak:**  
"Previous methods for registration include non-parametric approaches~\cite{sorkine2007rigid,zeng2017acap,sumner2007embedded,ovsjanikov2012functional}."

**✅ Strong:**  
"Non-parametric methods directly deform a template mesh to fit a target scan using established deformation models. For example, Sorkine et al.~\cite{sorkine2007rigid} developed As-Rigid-As-Possible (ARAP) deformation, while Zeng et al.~\cite{zheng2017acap} introduced the As-Conformal-As-Possible (ACAP) variant to better preserve angles. Ovsjanikov et al.~\cite{ovsjanikov2012functional} took a different approach using functional maps for correspondence."

---

## 5B. EPISTEMOLOGICAL CLARITY: WHO IS THE AGENT?

In academic writing, be explicit about **who performs the action**. This follows from the principle that only conscious agents (researchers, authors) can make intellectual contributions.

### ✅ Clear Attribution of Agency

**For published methods/models:**
- "Loper et al. developed SMPL" (not "SMPL provides...")
- "Smith and Jones derived Equation (5)" (not "Equation (5) shows...")
- "We implemented the algorithm in Python" (not "The algorithm performs...")

**For your own work:**
- "We demonstrate in Figure 3 that..." (not "Figure 3 demonstrates...")
- "In Section 4, we analyze..." (not "Section 4 analyzes...")
- "Our results show..." (not "Results show...") — though "results" can sometimes omit agent when context is clear

**For tools and objects (describe their function/purpose instead):**
- "We use the SMPL model to represent shape variations" (emphasizes authors' choice)
- "The energy function minimizes distance between meshes" (describes what it does, not as agent)
- "Figure 3 displays three representative registrations" (describes content, acceptable)

### ✅ General Rule
**Agent → Action → Object**
- ✅ "Chen et al. analyzed the mobility of linkages."
- ✅ "We demonstrate the pipeline's effectiveness using three datasets."
- ✅ "Section 3 presents our methodology." (acceptable: section is container for your work)
- ❌ "The methodology presents results." (methodology is not an agent)

---

## 6. AVOID OUTLINE-LIKE "CHALLENGES AND FUTURE OUTLOOK" SECTIONS

### ❌ AI Pattern (Don't Use)
Rigid formula:
- "Despite its X, [topic] **faces challenges**..."
- "Despite these challenges, [topic] **continues to thrive** / **positions itself for future growth**"
- Separate "Challenges" section followed by vague "Future Prospects"

### ✅ What To Do Instead
- Integrate challenges naturally into discussion
- Discuss actual constraints with evidence
- Avoid speculative "could benefit from" statements
- Don't add "Future Outlook" unless the literature discusses roadmaps

---

## 7. HIGH-FREQUENCY "AI VOCABULARY" TO AVOID OR MINIMIZE

### ❌ Overused AI Words (Use Sparingly)

**High-frequency across all eras:**
- **additionally** (especially at sentence start) → use "further," "moreover," "also"
- **crucial, vital, pivotal** → use "important," "key," or delete entirely
- **delve** → use "examine," "analyze," "investigate"
- **landscape** (as abstract noun) → rephrase: "in applications," "across engineering"
- **underscore** (as verb) → use "show," "reveal," "demonstrate"
- **testament** → use "evidence," "example," or avoid
- **highlight** (as verb, overused) → use "show," "illustrate," "demonstrate"
- **enduring** (as adjective) → use "persistent," "long-standing," or skip
- **align with** → use "match," "fit," "correspond to"
- **interplay** → use "interaction," "relationship"
- **tapestry** (abstract) → delete or use "collection," "body"
- **enhance, foster, cultivate** (vague) → be specific: "improved," "enabled," "supported"
- **showcasing, emphasizing, highlight** → use active verbs: "shows," "demonstrates," "proves"
- **intricate/intricacies** → use "complex," "complex aspects," "details"
- **vibrant, rich** → use specific language

### ✅ Best Practice
Use common academic terms: "important," "shows," "derives," "examines," "establishes," "based on," "resulting in"

---

## 8. AVOID AVOIDANCE OF SIMPLE COPULAS

### ❌ AI Pattern (Don't Use)
- "serves as a" instead of "is a"
- "marks the beginning of" instead of "began/started"  
- "represents a shift" instead of "shifted"
- "features [X]" instead of "has [X]"
- "boasts" instead of "has"

### ✅ What To Do Instead
- **Embrace "is/are"** freely — they are not weak
- Use simple past/present: "was," "were," "is," "are"
- Direct phrasing: "X has/contains Y" instead of "X offers/showcases Y"

---

## 9. AVOID NEGATIVE PARALLELISMS ("NOT X, BUT Y")

### ❌ AI Patterns (Don't Use)
- "It's not just X, it's Y"
- "Not only X but also Y" (overused to appear balanced)
- "Not X, but Y" (clearing up misconceptions that weren't stated)
- "No X, no Y, just Z" (forced contrast)

### ✅ What To Do Instead
- State what something IS, not what it ISN'T
- Avoid retroactively clarifying nonexistent misconceptions
- Use clear statements: "X exhibits both A and B" instead of "It's not just A, it's also B"

---

## 10. AVOID RULE OF THREE OVERUSE

### ❌ AI Pattern (Don't Use)
- Lists of three adjectives/phrases with minimal meaning: "important, crucial, and vital"
- "adjective, adjective, and adjective" to inflate apparent comprehensiveness
- Three parallel "-ing" phrases in succession
- Three-item lists to stretch simple concepts

### ✅ What To Do Instead
- Use lists/series when needed, **not** to pad
- If listing, ensure each item adds distinct information
- One strong verb beats three weak ones in parallel

---

## 11. MAINTAIN ACADEMIC PRECISION

### ✅ Do's
- Use specific terminology (avoid "cutting-edge," "innovative," "novel")
- Name authors and dates
- Provide concrete examples
- Explain technical terms on first use
- State assumptions explicitly
- Acknowledge limitations

### ✅ Structure Tips
- Short, direct sentences preferred over long flowery ones
- Active voice where possible, but passive acceptable for methods
- One clear idea per paragraph
- Transitions should be logical, not flowery

---

## 12. AVOID HEAVY PUNCTUATION (em dashes, colons, semicolons)

### ❌ AI Patterns (Don't Use)
- Em dashes (`---` or `--`) as clause separators: "Registration addresses this---a critical step---by establishing..."
- Colons to introduce clause continuations: "The data is complete: it has no labels."
- Semicolons to join independent clauses: "It is registered; each vertex now has a label."

### ✅ What To Do Instead
- Split into separate sentences.
- Use a comma where a brief parenthetical is needed.
- Reserve colons only for introducing a formal list or a definition that cannot be reworded.
- Reserve semicolons only when two clauses are so tightly paired that splitting would lose the logical link and no other construction works.

---

## 13. SPECIAL RULES FOR MATHEMATICAL/TECHNICAL WRITING

### ✅ Do's
- Define notation on first use
- Use "we show/derive/prove" (active)
- Avoid "As mentioned above" — use equation/section labels
- State results clearly: "Equation (5) gives X"

### ✅ Example
**❌ AI-style:** "This leads to an elegant derivation that demonstrates the importance of closure constraints, underscoring their crucial role in maintaining kinematic validity."

**✅ Human-style:** "Applying constraint (3) to Equation (5) yields the closure condition (6)."

---

## CHECKLIST FOR EVERY PIECE OF WRITING

Before finalizing:

- [ ] No listing of outlets/sources as proof of notability
- [ ] No "-ing" phrase padding at end of sentences
- [ ] No vague attribution ("researchers," "observers")
- [ ] No promotional words: "vibrant," "rich," "profound," "groundbreaking"
- [ ] No "serves as," "boasts," "features" used excessively
- [ ] No "crucial/vital/pivotal" unless essential
- [ ] No "it's not just X, it's Y" constructions
- [ ] No "despite X, Y continues to Z" with vague Z
- [ ] No "-ing" participle chains
- [ ] Specific names and dates instead of vague attributions
- [ ] "Is/are" used freely rather than avoided
- [ ] Concrete examples support all claims
- [ ] Technical definitions clear and precise

---

## REFERENCE

These guidelines are derived from:
- ["AI or not quiz" - Wikipedia Detection Patterns](https://en.wikipedia.org/wiki/Wikipedia:Artificial_intelligence_writing_detection)
- Juzek & Ward (2025): "Why does ChatGPT delve so much?" *ACL 2025*
- Russell et al. (2025): "People who frequently use ChatGPT are accurate detectors" *ACL 2025*
- Kobak et al. (2025): "Delving into LLM-assisted writing" *Science Advances*

---

## APPLYING THESE RULES

This guidance applies to:
- ✅ Abstract and introduction content
- ✅ Section body text
- ✅ Discussion and conclusions
- ✅ Figure captions and table labels
- ✅ Supplementary material

Override these rules ONLY when:
- Directly quoting a source
- Using domain-specific jargon that requires terminology
- Academic convention demands specific phrasing

When in doubt: **Be specific, be direct, cite your sources, avoid emphasis words.**
