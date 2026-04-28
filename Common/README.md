# Common/ — Shared Resources for the Diffeology Archives

This folder contains shared LaTeX files used across multiple papers and monographs in the Diffeology Archives.

## Files

| File | Purpose |
|:---|:---|
| `Diffeology-macros.tex` | Semantic macros: number sets, groups, operators, tangent spaces, differential forms, paths, loops, homology, cohomology, covering spaces, etc. |
| `Environments.tex` | Document environments: article numbering, theorem-like environments (theorem, proposition, lemma, corollary, definition, proof), French versions for historical papers. |
| `Packages.tex` | Core LaTeX packages: AMS math, fonts (Utopia), graphics (graphicx, tikz-cd), special characters (pifont, ulem, url, contour), spacing defaults. |

## Usage

For future use in papers or monographs, which will include these files in the preamble **in this order**:

```latex
\documentclass[...]{amsart}

\input{../../Common/Diffeology-macros.tex}
\input{../../Common/Packages.tex}
\input{../../Common/Environments.tex}

% Paper-specific overrides follow...