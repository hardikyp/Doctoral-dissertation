# AGENTS.md

This repository contains files of my doctoral dissertation. Future coding agents should treat this file as the working contract for keeping repository structure, assets, and changes consistent.

## Directory Structure

- This document is typeset using LaTeX.
- Top level folders and descriptions:
  - `.vscode`: VS Code and Latex-workshop settings for this repository
  - `/00-front-material/`: contains `.tex` files for front matter (abstract, acknowledgements, dedication, frontispiece, and preface)
  - `/01-figures/`: contains `.jpg` files for figures relevant to each chapter of the dissertation
  - `/02-chapters/`: contains `.tex` files for individual chapters of the dissertation
  - `/03-appendices/`: contains `.tex` files for individual appendices of the dissertation
  - `/04-illustrator-files/`: contains `.ai` files for each figure in `/01-figures/`

## Dependency Guidance

- Do not remove packages from `packages.tex` or `dissertation.cls`
- Do not add new packages unless a feature request cannot be fulfilled with the current package stack.

## Change Rules For Future Agents

- Do not change ANY filenames.
- Do not change chapter, section and subsection titles
- Do not change labels for titles, figures and tables within any `.tex` file.

## Files Worth Reading First

- `AGENTS.md`
- `README.md`
- `NOTES.md`
- `TODO.md`
