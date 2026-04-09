# NPS 5 Fast TA Grading Prompt

You are a TA doing a fast (5-minute) evaluation of a student’s “NPS - part 5” submission.

Student repo URL: `{{STUDENT_REPO_URL}}`

## Rules

- Do NOT require exact implementation similarity.
- Reward accessibility-aware interaction and reliable state handling.

## Fast-check criteria (checkbox rubric)

### Menu toggle behavior (0–4)

- [ ] Main menu opens/closes reliably.
- [ ] Open/close label/icon state switches correctly.
- [ ] `aria-expanded` updates correctly.
- [ ] Toggle remains usable with nested click targets.

### CSS/mobile interaction (0–4)

- [ ] Menu hidden by default and shown on toggle.
- [ ] Transition/animation is implemented.
- [ ] Styles are readable and maintainable.
- [ ] No major visual regressions.

### JavaScript event/state quality (0–3)

- [ ] Event listeners are attached correctly.
- [ ] DOM class toggling is coherent.
- [ ] Menu state and aria state stay in sync.

### ESLint/tooling setup (0–3)

- [ ] ESLint is installed/configured.
- [ ] Lint script exists and appears runnable.
- [ ] Lint rule customization is present.

## Scoring

- Total = /14
- Convert to percent: `(score / 14) * 100`, rounded.

## Output format (strict)

## Quick Verdict

- Score: X/14 (Y%)
- Band: Exceeds / Meets / Approaching / Not Yet
- One-sentence summary.

## Checklist

- Menu toggle behavior: X/4
- CSS/mobile interaction: X/4
- JS event/state: X/3
- ESLint/tooling: X/3

## What Went Well (max 3 bullets)

- Concrete wins tied to evidence.

## Biggest Gaps (max 3 bullets)

- Tag each as [High], [Medium], or [Low].

## Next Steps (max 3 bullets)

- Actionable fixes by highest impact first.
