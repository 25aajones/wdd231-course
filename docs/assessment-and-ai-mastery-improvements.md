# WDD 231 Assessment and Deliverable Improvements for Mastery + Effective AI Use

## Goal

Improve assessment quality so students:

1. Master core web development concepts more deeply.
2. Use AI as a **learning assistant** (clarification, feedback, debugging support), not as a replacement for their own thinking and implementation.

This document is based on the semester pathway in `src/content` and existing AI guidance patterns.

## Current Strengths

- Iterative project arc (`nps-1` through `nps-7`) naturally supports progressive mastery.
- Repeated implementation practice in authentic contexts (API calls, async flow, modular code, deployment).
- Team project introduces real collaboration constraints and integrative scope.
- Existing AI language already discourages over-reliance and encourages validation.

## Main Gaps to Address

1. **Understanding evidence is under-specified**
   - Students can complete features without clearly demonstrating reasoning/debugging process.

2. **AI-use expectations are not consistently assessable**
   - Policy language exists, but many tasks lack a required artifact showing responsible use.

3. **Rubric signals favor “feature complete” over “concept mastery”**
   - Some deliverables evaluate what works, but not always why it works.

4. **Inconsistent AI metadata in prove content**
   - Some files omit explicit `aiUsage`, which can create policy ambiguity.

## Recommended Improvements (Prioritized)

## 1) Add a Short “Learning Evidence” Section to Prove Submissions

### What to add

Require a brief appendix (5–10 minutes) for each major prove milestone:

- What changed (high level)
- One bug encountered + root cause
- How it was fixed and verified
- One design/refactor decision and rationale

### Why

This directly measures understanding and debugging competency, not only output completion.

### AI guardrail

If AI was used, require:

- Prompt intent (what they asked for)
- What they accepted/rejected and why
- How they verified correctness (docs/test/manual check)

## 2) Standardize an “AI Use Declaration” Block in Prepare/Prove

### What to add

At submission time, require one of:

- No AI used
- AI used for explanation/brainstorming/debugging
- AI used for code suggestions (with validation notes)

Suggested format:

- Task where AI was used
- AI contribution type
- Verification steps performed
- Final student-authored changes

### Why

Makes AI behavior visible and teaches accountable professional practice.

## 3) Shift Rubrics Toward Mastery Signals (Not Only Features)

For major NPS milestones and final project checkpoints, include criterion bands for:

- Technical correctness
- Code organization/modularity
- Accessibility and UX quality
- Debugging quality (evidence of root-cause thinking)
- AI-use quality (when applicable)

### Example performance language

- **Proficient**: explains implementation choices and validates AI suggestions with independent checks.
- **Developing**: delivers working code but explanations/validation are incomplete.
- **Emerging**: relies on copied solutions without clear understanding.

## 4) Add Lightweight Oral/Live Validation at Key Milestones

At selected checkpoints (e.g., NPS mid-point, team-final):

- 5-minute walkthrough: student/team explains one core module and one bug fix.
- Include 1–2 transfer questions (“How would this change if endpoint X failed?”).

### Why

Rapidly detects genuine understanding and reinforces communication competency.

## 5) Strengthen Team Deliverables with Role + Decision Traceability

### What to add

For team milestones:

- Role snapshot for the week
- Decision log (2–3 entries)
- Integration issues encountered and resolved

### Why

Improves collaboration accountability and makes hidden learning work visible.

## 6) Ensure Consistent AI Policy Metadata in Content Files

### What to change

Audit `src/content/prove` and `src/content/prepare` to ensure each activity has intentional `aiUsage` value (`red`, `yellow`, or `green`) matching instructional intent.

### Why

Removes ambiguity and aligns displayed policy with assessment expectations.

## Suggested Deliverable Enhancements by Assessment Type

## Prepare Activities

Keep short format, add one required line:

- “What I validated outside AI and how” (docs, course modules, experiment, peer/instructor check)

Outcome: encourages source triangulation and discourages single-source dependency.

## Prove (NPS Sequence)

Add two small artifacts to existing submission:

1. **Implementation note** (what was built + why)
2. **Debug note** (issue, root cause, evidence, fix)

For AI-allowed tasks, include AI declaration block.

Outcome: better measurement of conceptual mastery and engineering process.

## Team Project Milestones

Add milestone packet items:

- Scope status against requirements
- Risk list + mitigation
- Team decision log
- Optional AI usage summary by team member
- Unit-specific AI audit prompt + audit report (what was learned and what changed)

Outcome: stronger project management and team accountability signals.

## Example Rubric Add-On (Reusable)

| Criterion           | Emerging                  | Developing               | Proficient                                         |
| ------------------- | ------------------------- | ------------------------ | -------------------------------------------------- |
| Concept Explanation | Can describe steps only   | Explains some rationale  | Explains rationale and tradeoffs clearly           |
| Debugging Evidence  | Fixes are trial-and-error | Some root-cause analysis | Clear root-cause analysis and verification         |
| AI Use Quality      | Unclear or unverified use | Partial validation       | Intentional use with documented validation         |
| Code Ownership      | Heavy copy-forward signs  | Mixed ownership          | Student/team can explain authored code confidently |

## Implementation Roadmap

## Implementation Status (Completed in this branch)

- [x] Added required reflection blocks to `src/content/prove/nps-1.mdx` through `src/content/prove/nps-7.mdx`.
- [x] Added required team checkpoint reflection blocks to all team milestones: `src/content/prove/team-1.mdx` through `src/content/prove/team-final.mdx`.
- [x] Added unit-specific AI audit prompts and required audit reports to all team milestones: `src/content/prove/team-1.mdx` through `src/content/prove/team-final.mdx`.
- [x] Added lightweight prepare validation prompt to all prepare activities (16 files): `src/content/prepare/unit1.md` through `src/content/prepare/unit6.md` (including part files).
- [x] Completed `aiUsage` consistency sweep: prove milestones now explicitly set `aiUsage: yellow`; prepare activities reviewed and currently rely on collection default.
- [x] Added a lightweight instructor scoring rubric for AI audit quality to all team milestones for consistent evaluation.
- [ ] Updated rubric descriptors in course assessment tooling/content (still pending).

## This Term (Low Lift)

1. [x] Add AI declaration and learning evidence template to prove/prepare submission instructions.
2. [ ] Update rubric descriptors to include debugging evidence and explanation quality.
3. [x] Run `aiUsage` metadata consistency sweep in `src/content/prove` + `src/content/prepare` (prove explicitly set; prepare reviewed with schema defaults).

## Next Revision Cycle (Moderate Lift)

4. Add 5-minute live validation at selected checkpoints.
5. Add team decision logs and role snapshots to team milestones.
6. Review outcome data and tune rubric language.

## Success Indicators

Track the following after adoption:

- Fewer submissions with unexplained or brittle code.
- Improved student ability to explain async/API/debug decisions.
- Higher consistency in responsible AI use reporting.
- Better team milestone predictability and integration quality.

## Practical Guidance for Students (Language You Can Reuse)

Use AI to:

- Clarify concepts in plain language.
- Generate debugging hypotheses.
- Compare alternative approaches.

Do not use AI to:

- Produce large unreviewed code blocks for direct submission.
- Skip reading docs or testing behavior yourself.
- Replace your own explanation of how/why code works.

Always include:

- What you verified independently.
- Why your final implementation choice is appropriate.
