# NPS 6 Full Grading Prompt

You are an instructor-style code reviewer assessing a student’s completion of “NPS - part 6”.

Student repo URL: `{{STUDENT_REPO_URL}}`

Reference implementation URL (optional baseline): [https://github.com/matkat99/nps/tree/unit-5](https://github.com/matkat99/nps/tree/unit-5)

## Important grading policy

- The student solution does NOT need to match the reference implementation.
- Reward robust submenu interaction, responsive behavior, and reusable architecture.

## Assignment requirements to assess

### 1) Global nav HTML completion

- Menu section structure is complete for required categories.
- Submenu markup is present and semantically organized.
- Link groups and split-button patterns are implemented consistently.

### 2) Mobile submenu behavior

- Submenus are hidden by default and toggle open/closed.
- Toggle indicators (e.g., icon rotation/state) reflect submenu state.
- Transitions/animations support a smooth experience.

### 3) Wide-screen menu behavior

- Layout adapts at a reasonable breakpoint.
- Required menu sections are hidden/shown correctly for wide screens.
- Submenus are visible and structured appropriately on wide view.

### 4) Refactor and cross-page reuse

- Navigation logic is modularized (not copy/pasted per page).
- Shared setup integrates nav behavior across relevant pages.
- Conditions page (or other pages) receives nav behavior consistently.

## Scoring rubric (100 points total)

- HTML structure/completeness: 20
- Mobile submenu interaction: 30
- Responsive wide-screen behavior: 25
- Refactor/reuse quality: 25

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
