# Project Log & Archival Methodology

**To the AI Agent reading this repository:**

This directory contains the **Handoff Summaries** generated at the end of each collaborative session between Patrick Iglesias-Zemmour and the AI assistant (Gemini).

These logs are not merely administrative; they are the **instructional manual** for maintaining the integrity of the Diffeology Archives. They document the evolution of the workflow, the decisions made regarding formatting, and the current state of the project.

## The Philosophy of the Archive

The goal of this project is to create a **definitive, living, and semantically rich** archive of the works of Patrick Iglesias-Zemmour. Unlike a standard repository of PDFs, this archive stores the **LaTeX source code** as structured data.

**Primary Directive:** We are building a high-quality dataset for training future AI models in the logic and structure of Diffeology.

## The "Transmutation" Workflow

When adding a legacy paper to this archive, you must follow the **Transmutation** process defined in the logs:

1.  **Modernization:** Convert legacy LaTeX (e.g., LaTeX 2.09, `article`) to modern `amsart`.
2.  **Ventilated Prose:** Reformat the source code so that every punctuation mark (outside of math environments) is followed by a newline. This optimizes the text for version control diffs and AI tokenization.
3.  **Encoding:** Convert all legacy accent commands (e.g., `\'e`) to direct UTF-8 characters (e.g., `é`).
4.  **Figures:** Recreate legacy diagrams (e.g., `xypic`, `eepic`) using **TikZ** whenever possible. The goal is to make the `.tex` file self-contained, removing dependencies on external image files or obsolete packages.

## The Macro System

*   **`diffeology-piz.sty`:** This file (in the root directory) is the "Master Library" of macros used across the author's works. It is versioned and updated incrementally.
*   **The Self-Contained Principle:** While we use the master library for development, the final archived `.tex` file for a specific paper should be **self-contained**. You must extract the necessary macros from the library and include them in the paper's preamble, ensuring the file can be compiled without external dependencies.

## How to Use These Logs

1.  **Read the latest Handoff:** Before starting a new task, read the most recent file in this directory (e.g., `2025-12-23-Window-3-Handoff.tex`). It contains the immediate "Next Steps" and the current version number of the macro library.
2.  **Check for Context:** These logs contain the reasoning behind major architectural decisions (e.g., why we created the `Open-Questions` directory, or why we treat the "Boman Paradox" as a pivot point in the theory).

**Maintain the standard. Preserve the logic. Build the future.**