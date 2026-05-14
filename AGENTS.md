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

- You are only allowed to make LaTeX syntax and formatting changes.
- Ask for explicit approval before making any syntax or formatting changes.
- Do not modify, rewrite, paraphrase, summarize, or otherwise alter any text content in chapter or appendix `.tex` files.
- Do not change any filenames.
- Do not change chapter, section, or subsection titles.
- Do not change any labels associated with titles, figures, tables, equations, or references within any `.tex` file.
- Do not modify figure captions, table captions, citation keys, bibliography entries, or cross-reference identifiers unless explicitly instructed.

## Files Worth Reading First

- `AGENTS.md`
- `README.md`
- `NOTES.md`
- `TODO.md`
