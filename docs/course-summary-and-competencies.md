# WDD 231 Course Summary and Suggested Competencies

## Purpose and Scope

This document summarizes the **semester pathway** in `src/content` for WDD 231 and proposes competencies the course appears to measure.

Source of truth used:

- `src/content/semester` (unit structure)
- `src/content/prepare` (exploration/research tasks)
- `src/content/prove` (performance assessments and project milestones)
- `src/content/config.ts` plus AI guidance patterns in prove/prepare content

## Course Summary (Semester Pathway)

The course is organized into 6 units with a repeated rhythm:

1. **Prepare**: short exploration/research prompts to activate prior knowledge and new concepts.
2. **Ponder**: guided learning modules and references.
3. **Prove**: applied deliverables that demonstrate working implementation and progress.

### Progression Arc

- **Unit 1**: environment setup, HTML/CSS/JS fundamentals, initial NPS app structure.
- **Units 2–5**: incremental build-out of an NPS-style web application through `nps-1` to `nps-7` tasks and team checkpoints, including API integration, async workflows, URL params, modular architecture, accessibility/UX, and deployment.
- **Unit 6**: tooling emphasis (e.g., regex, workflow productivity), finalization and project completion.

### Assessment Pattern in Current Content

- Frequent, concrete implementation requirements.
- Milestone-based proofs of progress.
- Team project requirements aligned to broad web app capabilities (form handling, persistence, data access, responsive design, accessibility, modules, interaction patterns).
- AI-use language exists and generally promotes support/learning over substitution, but is not yet uniformly embedded as an assessable competency.

## Suggested Competencies Measured

The list below is inferred from current assignments and can be mapped to department/program outcomes.

### A. Technical Web Development Competencies

1. **Semantic structure and accessible markup**
   - Uses semantic HTML and appropriate element structure.
   - Demonstrates accessibility practices (keyboard paths, labeling, readable structure).

2. **CSS architecture and responsive implementation**
   - Builds responsive layouts using modern CSS.
   - Organizes CSS for maintainability and team collaboration.

3. **JavaScript fundamentals and DOM programming**
   - Uses variables, functions, modules, and event handling effectively.
   - Updates UI dynamically based on data and user interaction.

4. **Asynchronous data integration**
   - Retrieves and handles API data with async/await.
   - Diagnoses request/response failures and recovers gracefully.

5. **State and persistence**
   - Uses local storage appropriately for user-relevant persistence.
   - Implements basic client-side state flow between views.

6. **Routing patterns and URL parameters**
   - Uses URL parameters to drive detail views or contextual rendering.

7. **Build/deploy workflow literacy**
   - Runs local build/preview checks and deploys with environment variable handling.

### B. Engineering Process Competencies

8. **Incremental development and refactoring**
   - Breaks work into small, testable milestones.
   - Refactors to reduce duplication and improve readability/maintainability.

9. **Debugging and evidence-based troubleshooting**
   - Uses browser dev tools, network inspection, and logging to isolate issues.
   - Explains root cause and verifies fix.

10. **Code quality and project organization**

- Maintains modular file organization and coherent naming.
- Produces understandable code with consistent conventions.

### C. Professional and Collaboration Competencies

11. **Team planning and execution**

- Participates in team checkpoints and contributes to scoped milestones.
- Integrates team work while maintaining quality and coherence.

12. **Communication and decision rationale**

- Documents major implementation decisions and tradeoffs.
- Justifies selected approaches with technical reasoning.

13. **Responsible AI-assisted learning**

- Uses AI to explore, clarify, and troubleshoot concepts.
- Validates AI output against docs/tests/observed behavior.
- Avoids copy-forward substitution that bypasses understanding.

## Competency Evidence Matrix (Suggested)

| Competency                  | Strong Evidence Artifacts                        | Observable Indicators                                                       |
| --------------------------- | ------------------------------------------------ | --------------------------------------------------------------------------- |
| Semantic/accessibility      | Header/nav/forms/landmarks, keyboard support     | Correct semantic roles/labels; no major accessibility blockers in key flows |
| CSS responsive architecture | Multi-breakpoint layouts, partial organization   | Layout remains usable across device widths; style code remains maintainable |
| Async/API integration       | Service modules, fetch logic, error handling     | Successful data retrieval + clear handling of failure states                |
| State/persistence           | localStorage flows                               | Stored data is retrievable, validated, and reflected in UI                  |
| URL parameter flow          | list-to-detail navigation                        | Correct detail view rendering from parameterized context                    |
| Refactoring                 | before/after service or CSS modularization       | Reduced duplication, clearer responsibilities                               |
| Debugging                   | bug notes, network/tool screenshots, fix commits | Root cause identified and fix verified, not guessed                         |
| Team execution              | team milestone submissions                       | Deliverables align to scope and quality expectations                        |
| Responsible AI use          | AI usage log + verification notes                | Student can explain what AI suggested, what changed, and why                |

## Suggested Proficiency Levels

- **Emerging**: can follow patterns with support, limited transfer to new contexts.
- **Developing**: completes core tasks independently with occasional guidance; explains most choices.
- **Proficient**: applies concepts across new requirements, debugs effectively, and justifies decisions.
- **Advanced**: demonstrates strong architecture/refactoring judgment, quality validation, and peer-support capacity.

## External Outcome Mapping (Template)

Use this section to map inferred competencies to official BYUI/program outcomes.

| Program Outcome (to be filled) | WDD 231 Competency Alignment                                   |
| ------------------------------ | -------------------------------------------------------------- |
| Outcome A                      | Semantic/accessibility, responsive implementation, UX quality  |
| Outcome B                      | API integration, async data handling, persistence              |
| Outcome C                      | Team planning/execution, communication, professional workflow  |
| Outcome D                      | Debugging, refactoring, quality assurance practices            |
| Outcome E                      | Responsible AI-assisted learning and evidence-based validation |

## Notes for Instructors

- Current assignments already provide strong technical scaffolding for mastery through iterative project work.
- The highest-leverage enhancement area is making **understanding evidence** explicit (especially where AI is allowed).
- The companion recommendations document proposes concrete assessment/deliverable upgrades without requiring major platform changes.
