# NPS 6 Fast TA Grading Prompt

You are a TA doing a fast (5-minute) evaluation of a student’s “NPS - part 6” submission.

Student repo URL: `{{STUDENT_REPO_URL}}`

Reference implementation URL (optional baseline): [https://github.com/matkat99/nps/tree/unit-5](https://github.com/matkat99/nps/tree/unit-5)

## Rules

- Do NOT require exact implementation similarity.
- Reward reliable submenu behavior, responsive adaptation, and reusable code.

## Fast-check criteria (checkbox rubric)

### Menu HTML completion (0–3)

- [ ] Required nav sections and submenu structures are present.
- [ ] Split-button + submenu pattern is consistent.
- [ ] Markup is semantically reasonable.

### Mobile submenu interaction (0–4)

- [ ] Submenus are hidden by default.
- [ ] Submenus open/close on toggle.
- [ ] Toggle indicators reflect state.
- [ ] Interaction is stable (no obvious broken toggles).

### Responsive wide behavior (0–3)

- [ ] Menu adapts at wide-screen breakpoint.
- [ ] Required sections are shown/hidden correctly.
- [ ] Wide-screen submenu layout is usable.

### Refactor/reuse quality (0–4)

- [ ] Navigation logic is extracted into shared module(s).
- [ ] Shared setup applies nav behavior across pages.
- [ ] No major copy/paste duplication remains.
- [ ] Changes are maintainable and easy to extend.

## Scoring

- Total = /14
- Convert to percent: `(score / 14) * 100`, rounded.

## Output format (strict)

## Quick Verdict

- Score: X/14 (Y%)
- Band: Exceeds / Meets / Approaching / Not Yet
- One-sentence summary.

## Checklist

- Menu HTML: X/3
- Mobile interaction: X/4
- Responsive wide behavior: X/3
- Refactor/reuse: X/4

## What Went Well (max 3 bullets)

- Concrete wins tied to evidence.

## Biggest Gaps (max 3 bullets)

- Tag each as [High], [Medium], or [Low].

## Next Steps (max 3 bullets)

- Actionable fixes by highest impact first.
