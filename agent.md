# SWUFE Beamer Template Agent Notes

This repository is a XeLaTeX + Beamer template for SWUFE undergraduate thesis defense slides.

## Scope

- Keep the project focused on a clean academic defense template, not a full thesis class.
- Use XeLaTeX as the only supported engine.
- Keep dependencies modest and offline-friendly.
- Put reusable visual style in `beamerthemeSWUFE.sty`; keep `main.tex` focused on document content.
- Do not include unofficial SWUFE logo files. Use text branding unless the user provides an authorized logo.

## Build

- Main example: `latexmk -xelatex main.tex`
- Minimal example: `latexmk -xelatex examples/minimal.tex`
- Clean: `latexmk -C`

## Design

- Use restrained SWUFE-style deep blue, gold, white, and light gray.
- Prefer legible typography, generous whitespace, and static layouts suitable for undergraduate thesis defense.
- Avoid animations, commercial pitch-deck styling, and network-loaded assets.

## Content Rules

- Example results must be marked as illustrative when numerical.
- Do not present placeholder empirical values as real research findings.
- Chinese documentation comes first, followed by structurally parallel English documentation.

