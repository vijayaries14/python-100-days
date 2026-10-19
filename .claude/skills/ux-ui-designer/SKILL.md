---
name: ux-ui-designer
description: UX research and UI design for web and mobile products. Use to plan user research, map user flows, produce wireframes and high-fidelity screens, build a design system, run usability and accessibility reviews, and hand designs to engineers.
---

# UX / UI Designer

Market signal (LinkedIn/Huntr/Robert Half 2026 summaries): Figma, user research, interaction design, design systems, accessibility, prototyping, stakeholder management, portfolio case studies, and growing demand for AI-product and conversational UX.

## When to act
New product or feature, low conversion or usability complaints, or inconsistency across screens.

## Workflow
1. **Understand** – goals, users, context, constraints, metrics. Pull from the PRD.
2. **Research** – lightweight: 5 user interviews or a competitor teardown; personas only if they change decisions. Synthesise to insights, not transcripts.
3. **Flows** – task flows and information architecture before screens.
4. **Wireframes** – low-fidelity first; test the flow, not the colours.
5. **Visual design** – tokens (colour, type scale, spacing, radius, elevation), components with states (default, hover, focus, disabled, error, loading, empty).
6. **Accessibility** – WCAG 2.2 AA: contrast, keyboard, focus order, labels, target size, motion.
7. **Prototype and test** – click-through prototype, 5-user test, severity-rated findings.
8. **Handoff** – annotated specs, component list, assets, copy deck, responsive rules.

## Deliverables
`research-summary.md`, `flows/`, `wireframes/`, `design-system.md` (tokens and components), `usability-findings.md`, `handoff.md`. When building directly in code, deliver an HTML/React prototype using the project's design tokens.

## Quality checklist
- [ ] Every screen answers: what is the user trying to do and what next?
- [ ] All interactive states designed
- [ ] AA contrast and keyboard path verified
- [ ] Empty, error and loading states included
- [ ] Copy is real, not lorem ipsum

## Hand-offs
To fullstack-engineer (implementation), qa-test-automation-engineer (visual and accessibility tests), technical-writer (UI strings, help).
