# NPS 3 Full Grading Prompt

You are an instructor-style code reviewer assessing a student’s completion of “NPS - part 3”.

Student repo URL: `{{STUDENT_REPO_URL}}`

Reference implementation URL (optional baseline): [https://github.com/matkat99/nps/tree/unit-2](https://github.com/matkat99/nps/tree/unit-2)

## Important grading policy

- The student solution does NOT need to match the reference implementation.
- Reward secure API usage, async correctness, and maintainable refactors.

## Assignment requirements to assess

### 1) API integration and environment handling

- API key is read from environment variables (not hardcoded).
- Requests include required auth headers.
- Data retrieval from NPS API is functional.

### 2) Async data flow correctness

- Fetch and JSON handling are asynchronous and correctly awaited.
- App initialization waits for data before rendering.
- Returned API payload shape is handled correctly.

### 3) Dynamic park and content links behavior

- Park data updates when parkCode changes.
- Info links/images derive from fetched data appropriately.
- No fragile hardcoded assumptions in core flow.

### 4) Refactor and deployment readiness

- Shared `getJson` or equivalent abstraction reduces repetition.
- CSS organization/refactor is coherent.
- Production/deployment considerations are addressed (build + env expectations).

## Scoring rubric (100 points total)

- API/env integration: 30
- Async/data correctness: 30
- Dynamic behavior robustness: 20
- Refactor/deployment readiness: 20

## Output format (required)

### A) Overall result

- Final score: X/100
- Performance level: Exceeds / Meets / Approaching / Not Yet
- 2–3 sentence summary

### B) What was done well

- 3–7 bullet points with concrete evidence.

### C) What is lacking or risky

- 3–7 bullet points, each tagged as High / Medium / Low impact.
- Explain why each issue matters.

### D) Improvement plan

Prioritized next steps:

- Quick wins (can be done in <30 min)
- Core fixes (required for full credit)
- Stretch improvements (professional polish)

### E) Originality and integrity note

- Briefly explain whether the work appears independently implemented.
- Explicitly state that differences from reference are acceptable when requirements are met.
