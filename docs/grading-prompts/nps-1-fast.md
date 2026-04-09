# NPS 1 Fast TA Grading Prompt

You are a TA doing a fast (5-minute) evaluation of a student’s “NPS - part 1” submission.

Student repo URL: `{{STUDENT_REPO_URL}}`

Reference implementation URL (optional baseline): [https://github.com/matkat99/nps/tree/unit-1](https://github.com/matkat99/nps/tree/unit-1)

## Rules

- Do NOT require a code match with the reference.
- Differences are acceptable if assignment outcomes are met.
- Reward clean structure, responsive styling, and accessibility basics.

## Fast-check criteria (checkbox rubric)

### Setup and run readiness (0–3)

- [ ] Project dependencies/install appear correct.
- [ ] Dev server setup is functional.
- [ ] No obvious startup/runtime blockers.

### Header implementation (0–4)

- [ ] Global header is complete.
- [ ] Park header/hero structure is complete.
- [ ] Sprite icons are correctly referenced.
- [ ] Structure is semantic and coherent.

### Styling and responsiveness (0–4)

- [ ] Base styles (fonts/colors/spacing) are implemented.
- [ ] Layout holds up on narrow and wider widths.
- [ ] Hero/header visuals are usable and consistent.
- [ ] No major visual breakage.

### Accessibility fundamentals (0–3)

- [ ] Skip links/keyboard flow are preserved.
- [ ] Important labels/landmarks are present.
- [ ] No major accessibility regressions.

## Scoring

- Total = /14
- Convert to percent: `(score / 14) * 100`, rounded.
- Performance band:
  - 90–100: Exceeds
  - 75–89: Meets
  - 60–74: Approaching
  - <60: Not Yet

## Output format (strict)

## Quick Verdict

- Score: X/14 (Y%)
- Band: Exceeds / Meets / Approaching / Not Yet
- One-sentence summary.

## Checklist

- Setup/run: X/3
- Header implementation: X/4
- Styling/responsive: X/4
- Accessibility: X/3

## What Went Well (max 3 bullets)

- Concrete wins tied to evidence.

## Biggest Gaps (max 3 bullets)

- Tag each as [High], [Medium], or [Low].

## Next Steps (max 3 bullets)

- Actionable fixes by highest impact first.
