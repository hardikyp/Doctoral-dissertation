# AGENTS.md

This repository contains files of my doctoral dissertation. Future coding agents should treat this file as the working contract for keeping repository structure, assets, and changes consistent.

## High-Level Architecture

- This document is typeset using LaTeX.
- Top level folders and descriptions:
  - `.vscode`: VS Code and Latex-workshop settings for this repository
  - `/00-front-material/`: contains `.tex` files for front matter (front page, dedication, abstract, acknowledgements, etc.)
  - `/01-figures/`: contains `.jpg` files for figures inside the main document
  - `/02-chapters/`: contains `.tex` files for individual chapters of the dissertation
  - `/03-appendices/`: contains `.tex` files for individual appendices of the dissertation
  - `/04-illustrator-files/`: contains `.ai` files for each figure in `/01-figures/`

## Dependency Guidance

- Keep dependencies minimal.
- Do not add new packages unless the feature cannot be solved cleanly with the current package stack.

## Change Rules For Future Agents

- Do not change ANY filenames.
- Do not change labels and titles within any `.tex` file.

## Files Worth Reading First

- `AGENTS.md`
- `README.md`
- `NOTES.md`
- `TODO.md`
