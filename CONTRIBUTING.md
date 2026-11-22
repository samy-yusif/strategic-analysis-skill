# Contributing

Thanks for helping improve the Strategic Analysis Skill.

## Ways to contribute
- **New framework**: Blue Ocean, Ansoff, Business Model Canvas, Scenario planning, etc.
- **Industry pack**: preset key success factors, typical ratios and data sources for one industry.
- **Rule fixes**: a scale, formula or interpretation that's wrong or unclear.
- **Example outputs**: a full run on a public company (Excel + Word + deck) for `examples/`.
- **Translations** of the docs.

## How
1. Fork the repo and create a branch: `git checkout -b feature/blue-ocean`.
2. Edit `skills/strategic-analysis/SKILL.md` and, if relevant, `docs/frameworks.md`.
3. Keep the pipeline logic intact: every new framework must say **what feeds it** and **what it feeds**, and must include **success solutions**.
4. Test it: run the skill once in Claude with your change and attach a short note of the result to your PR.
5. Open a pull request describing the change and why.

## Style
- Plain, specific English. No filler.
- Scales and formulas stated exactly (e.g., `Priority = (Occurrence − 1) × 3 + Impact`).
- Cite the source of any rule you add (textbook, paper, practitioner guide).
