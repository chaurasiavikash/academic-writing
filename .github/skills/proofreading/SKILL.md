---
name: academic-proofreading
description: "Use this skill when asked to proofread, review, or improve academic manuscripts, LaTeX documents, journal papers, or any formal scientific writing. Covers grammar, agency rules, citation practice, anti-AI writing patterns, notation consistency, LaTeX hygiene, and English variety consistency. Do NOT use this skill for creative writing, blog posts, or informal documents."
---

# Academic Manuscript Proofreading

## Overview

Proofreading an academic manuscript is not the same as copy-editing for style.
The goal is to find errors that would cause a reviewer to distrust the work or
reject it on presentation grounds. Work through the manuscript in the order
below. Do not skip steps. Report every issue with a line reference and a
specific fix; never say "the writing is unclear" without quoting the sentence
and either proposing a replacement or describing precisely what is wrong.

## Working principle: describe the problem, prescribe only when asked

The author knows the content. You know the patterns. When you find an issue,
describe what is wrong and why — do not always rewrite the sentence for them.
Authors push back when reviewers prescribe specific wording that does not fit
their voice or the conventions of their field. Two acceptable response styles:

**Acceptable (describe + suggest):**
"This sentence assigns action to a section, which reads as AI writing.
Restructure so 'we' is the subject. One option: 'In Section 3, we introduce...'"

**Acceptable (describe only, for stylistic issues):**
"The opening of paragraph 2 repeats the definition of registration from
paragraph 1. Cut the first sentence or restructure to add new information."

**Not acceptable (prescriptive without context):**
"Replace this sentence with: 'In Section 3, we introduce the BodiesReg
pipeline that pioneers a novel approach to...'"

For grammatical errors, typos, missing commas, broken references, undefined
notation, and other mechanical issues, prescribe the exact fix.
For voice, structure, and stylistic issues, describe the problem and offer
options.

---

## Step 1 — Agency and attribution (highest priority)

**Rule: only people perform actions. Objects, sections, methods, and
limitations do not.**

Scan every sentence for a non-human subject performing a verb that implies
intention or action.

### Forbidden constructions
| Wrong | Right |
|---|---|
| "Section 3 introduces..." | "In Section 3, we introduce..." |
| "The method addresses..." | "We designed the method to address..." |
| "These limitations motivate..." | "These limitations led us to..." |
| "The results show..." | "We show that..." |
| "Registration enables..." | "We use registration to enable..." |
| "The table compares..." | "In Table 2, we compare..." |
| "This work presents..." | "We present..." |

**Also check:** citations must name the authors and state their specific
finding. Never write "studies have shown" or "researchers argue" without
naming who.

Wrong: "Studies show that marker placement affects accuracy."
Right: "Ancillao et al.~\cite{ancillao2021effect} found that soft-tissue
motion between the skin marker and the underlying bone introduces errors in
joint-centre estimation that are difficult to correct post hoc."

---

## Step 2 — Anti-AI vocabulary and patterns

Search the full document for each item below. Flag every occurrence and
propose a replacement or deletion.

### High-priority words (strong AI signal)
- delve → examine, analyse, investigate
- crucial, vital, pivotal → important, key (or delete)
- underscore (verb) → show, demonstrate, reveal
- leverage → use
- tapestry, landscape (abstract) → delete or rephrase specifically
- robust (unless used with a precise technical meaning) → delete or specify
- showcasing, highlighting, emphasizing → shows, demonstrates
- novel (as self-claim about your own work) → delete; let the content speak
- deploy (for software use) → use
- utilize → use
- foster, cultivate → support, enable (or be specific)
- meticulous → delete
- testament → evidence, example
- vibrant, rich, profound → delete or replace with specific language
- intricate, intricacies → complex, complexities
- enhance, bolster → improve, strengthen, or be specific

### Sentence-structure patterns
- Sentence-initial "Additionally", "Moreover", "Furthermore" → restructure
  the transition; do not just delete the word
- "Not only X, but Y" / "It's not just X, it's Y" → state X and Y as
  separate facts; the contrast is usually manufactured
- Three-item triadic lists used to pad ("important, crucial, and vital",
  "fast, efficient, and scalable") → reduce to one item if the items overlap
- Participial -ing phrases at the end of sentences adding vague significance
  ("...ensuring robust performance", "...highlighting the importance of",
  "...thereby providing a strong foundation for...") → cut entirely
- "Despite X, Y faces challenges..." formulaic structure → restructure
- Weak signposting: "as discussed next", "as we will see", "in what follows"
  → cut; the reader can see the next paragraph without being told

### Em dashes (en-GB and en-US both)
Em dashes ("---" in LaTeX) used where a comma, parenthesis, or colon would
work are a strong AI signal. Count the em dashes in the document. If there
are more than two per page, most of them should be commas, parentheses, or
colons. Em dashes are legitimate for parenthetical interruption with strong
emphasis; they are not legitimate as a general-purpose connector.

### Curly quotation marks
ChatGPT and DeepSeek output curly quotes (" " ' ') by default. LaTeX uses
straight quotes (` ' for single, `` '' for double). Search for U+201C, U+201D,
U+2018, U+2019 in the source. Replace with the LaTeX equivalents.

### Copula avoidance (AI pattern)
- "serves as" → is
- "marks the beginning of" → began
- "represents a shift" → shifted
- "features" / "boasts" (as substitute for "has") → has
- "constitutes" → is (when used as a fancy "is")

### Elegant variation
Cycling through synonyms for the same concept ("the model", "the framework",
"the approach", "the methodology", "the system" — all referring to the same
thing in adjacent paragraphs) is an AI tell from repetition-penalty training.
Pick one term and use it consistently.

### Excess hedging
Multiple hedges per sentence ("could potentially be considered as possibly
providing...") signal AI writing. One hedge per claim is enough. Strong
claims should be made directly when supported by evidence.

### Vague pronouns
"This" without a clear referent ("This addresses the problem", "This is
important") forces the reader to scan back for the antecedent. Replace with
"This [noun phrase that names what 'this' refers to]".

---

## Step 3 — Grammar and syntax

Check each of the following:

**Subject-verb agreement**
Read every sentence and confirm the verb agrees with its actual grammatical
subject, not the nearest noun. Pay attention to sentences with long noun
phrases between subject and verb.

**Tense consistency**
Methods sections: past tense ("we detected", "we minimised").
Claims about what the paper does: present tense ("we show", "we report").
Do not mix within a paragraph without reason.

**Comma placement**
- No comma between subject and verb
- Comma after introductory clauses ("In this section, we...")
- No comma before "that" in a restrictive clause
- Oxford comma: pick one convention and apply it throughout

**Apostrophes and possessives**
"its" (possessive) vs "it's" (it is). Check every occurrence.

**Prepositions**
"different from" not "different than" (en-GB)
"compared with" for parallel comparisons, "compared to" for analogies

---

## Step 4 — English variety consistency

Determine which variety is in use (en-GB or en-US) from the first paragraph
or from the journal's style guide. Then search for the following pairs and
ensure only one variety appears throughout:

| en-GB | en-US |
|---|---|
| artefact | artifact |
| behaviour | behavior |
| colour | color |
| modelling | modeling |
| optimisation | optimization |
| recognise | recognize |
| personalised | personalized |
| individualised | individualized |
| neighbouring | neighboring |
| centre | center |
| labelling | labeling |

**Mixed variety is worse than either choice.** Flag every inconsistency.

For biomechanics journals with European authorship, en-GB is conventional
unless the journal explicitly requires en-US.

---

## Step 5 — Citation hygiene

For every citation, check:

1. **Author name in text matches the cite key.** A cite key `zheng2017` used
   with "Zeng et al." in the text is an error regardless of which is correct.
   They must match.

2. **The attributed finding matches what the paper actually reports.**
   Do not use a citation to support a claim the cited paper does not make.
   Flag any citation where the connection is indirect or where the paper
   is well known but the specific claim is unverified.

3. **No club citations without explanation.** "~\cite{a,b,c}" without naming
   authors and specific findings is not acceptable. Each citation must be
   attached to a sentence that names the authors and their contribution.

4. **Citation placement.** Citations go after the claim they support, before
   the full stop. Not at the start of a sentence ("Smith et al. showed X")
   unless the sentence is about what Smith et al. did.

5. **AI-generated citation warnings.** If citations were suggested by an AI
   tool, verify every one independently against the actual paper abstract.
   AI tools hallucinate DOIs, confuse papers in the same journal volume, and
   match on keywords rather than content.

---

## Step 6 — LaTeX hygiene

Check the following mechanically:

**Labels and references**
- Every `\label{}` is referenced at least once with `\ref{}` or `\eqref{}`
- Every `\ref{}` resolves to a defined label
- No `_new`, `_rev2`, `_old` suffixes left in label names from revision history
- Figure and table labels follow a consistent convention

**Placeholders**
Search for: `TODO`, `FIXME`, `TBD`, `PLACEHOLDER`, `\textcolor{red}`,
`{\clr`, `{\clb`, `{\clg`, `<repo>`, `[funding`, `[protocol`.
Every hit is a submission blocker. List them all.

**Notation collisions**
Check that no symbol is used for two different things. Common collision:
using the same letter for a function name and a parameter to that function.

**Figure file extensions**
Every `\includegraphics` and `\begin{overpic}` call must have a file
extension (`.pdf`, `.png`, `.jpg`). Missing extensions cause compile errors.

**`\noindent` misuse**
`\noindent` should not appear at the start of regular paragraphs or before
bold contribution headings. LaTeX class files handle paragraph indentation.
Flag every `\noindent` and ask whether it is genuinely needed.

**Matching environments**
Count `\begin` and `\end` calls. They must match. Check that every
`\begin{algorithm}` has a caption and a label.

**Double words**
Search for common double-word typos: "and and", "the the", "is is", "of of".

---

## Step 7 — Flow and structure

For each paragraph, check:

1. **One idea per paragraph.** If a paragraph makes two distinct points,
   split it.

2. **Opening sentence states the point.** Paragraphs should not warm up
   for two sentences before making their claim.

3. **No repetition across paragraphs.** If the same claim appears in the
   introduction and again in the discussion without adding new information,
   one occurrence should be cut.

4. **Transitions are logical, not formulaic.** "Furthermore", "Moreover",
   "Additionally" at sentence start are formula transitions. Replace with
   a sentence that shows why the next point follows from the previous one.

5. **Roadmap paragraph accuracy.** Every section mentioned in the roadmap
   must exist. Every section that exists should appear in the roadmap.
   The verbs in the roadmap must assign action to "we", not to sections.

---

## Step 8 — Contribution and claim consistency

Check that:

1. Every claim in the abstract is supported by a specific result in the paper.
2. Every contribution listed in the introduction is demonstrated by an
   experiment in the evaluation section.
3. No comparison claim appears without a corresponding experiment.
   "Our method outperforms X" requires X to appear in a results table with
   numbers produced under the same protocol.
4. Limitations stated in the discussion are not contradicted by claims
   elsewhere.
5. Future work is not presented as a current result.

---

## Output format

Report findings in the following structure:

**Blockers** (must be fixed before submission):
List each with: location (section/line), the problem, and the fix.

**Errors** (incorrect content, wrong attributions, notation collisions):
Same format.

**Style issues** (agency, AI vocabulary, copula avoidance, variety):
Group by type. Quote the offending phrase and propose the replacement.

**Minor** (typos, double words, missing extensions, label suffixes):
List as a bullet list with locations.

Do not pad the report with praise. Every sentence in the output should
add information the author can act on.

---

## Example output (excerpt)

This is what good proofreading output looks like for a single pass:

```
BLOCKERS (4)

1. Section 4.2, Table 4: "tab:methods_summary" referenced but the table
   does not exist in the document. Either restore the table or delete the
   reference and the surrounding paragraph.

2. Section 4.3, line 612: Caption reads "[PLACEHOLDER] Practical challenges
   with the real world scanned data are show." Two issues: placeholder text
   in submitted manuscript, and typo "show" should be "shown".

3. Section 5.1: Three coloured annotation blocks remain ({\clr ...}, {\clb ...},
   {\clg ...}). All are draft notes that must be resolved before submission.

4. Acknowledgments: "[FUNDING STATEMENT]" placeholder still present.

ERRORS (3)

1. Section 2.1, equation (4): The LBS function W and the skinning weights W
   share the same symbol. Rename one. Suggest renaming skinning weights to
   \mathcal{W}.

2. Section 2.1, line 287: Text states "K=22 articulated joints" but Section 1,
   Section 3.2, and Figure 2 caption all use K=24. SMPL has 24 joints total
   (one root + 23 articulated). Choose one convention and use it throughout.

3. Section 3.1.2, line 354: Citation "Georgios et al.~\cite{SMPL-X:2019}"
   uses first name rather than family name. Verify the actual family name
   from the .bib entry and correct.

STYLE (12)

Agency violations (4):
- Section 1, line 230: "These limitations motivate automated 3D scan
  registration methods" — limitations cannot motivate anything. Suggest:
  "These limitations led us to pursue automated registration."
- [...]

Anti-AI vocabulary (5):
- Section 3.1, line 320: "We utilize anatomically meaningful keypoints"
  → "We use anatomically meaningful keypoints"
- Section 3.3, line 412: "Leveraging the inverse kinematics formulation"
  → "Using the inverse kinematics formulation"
- [...]

Em dashes (3):
- Section 4.1, line 510: em dash used as general connector; comma works here
- [...]

MINOR (7)
- Section 2, line 250: "and and" double word
- Figure 5 path: "./figures/correspondence_selector" — missing file extension
- Section 4.2, line 580: "about 100 subjects out of 631" — give exact number
- [...]
```

Each entry has a location, a description, and either a fix or a clear
direction for the author to fix it themselves.
