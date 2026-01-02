# Project Status

The **Diffeology Archives** project continues to grow. We have
successfully archived two major papers in this session and refined the
theoretical links between them. The repository is live at
<https://github.com/p-i-z/Diffeology-Archives>.

# Work Completed in This Session

## New Archives

- **2010-Orbifolds-as-Diffeologies**:

  - Transmuted legacy source to modern `amsart`.

  - **Major Task:** Recreated all 6 legacy `eepic` figures using `TikZ`,
    making the file completely self-contained.

  - Added historical context regarding the collaboration with Yael
    Karshon and Moshe Zadka.

- **2021-An-Introduction-To-Diffeology**:

  - Transmuted to `amsart` and applied \"ventilated prose\".

  - Cleaned the preamble significantly.

  - Added a \"Significance\" section to the README highlighting the
    \"Shift in Perspective\" (Diffeology vs. Topology) and the
    connection to Felix Klein's Erlangen Program.

## Documentation and Theoretical Linking

- **The Boman Paradox (2025):** Updated the existing README to
  explicitly state that this paper invalidates the strict Erlangen
  Program view proposed in earlier works.

- **Cross-Referencing:** Added a note to the 2021 \"Introduction\"
  README citing the 2025 \"Boman Paradox\" as a necessary refinement of
  the Kleinian perspective. This creates a dialectical link between the
  archives.

## Technical Updates

- **Macro Library (`diffeology-piz.sty`):** Updated to **Version 2.13**.

- Added functional space operators: `\Paths`, `\Loops`, `\Params`,
  `\Maps`.

- Added geometry operators: `\Geod`, `\Ham`, `\Surf`, `\Sq`.

- Added algebraic operators: `\Ad`, `\Hom`, `\ev`, etc.

- Added specific symbols: `\dR`, `\CHK` (Chain-Homotopy), `\dt`.

# Current Workflow

1.  **Transmutation:** Convert to `amsart`, apply ventilated prose,
    convert accents to UTF-8.

2.  **Figures:** Recreate legacy diagrams in `TikZ` whenever possible to
    ensure self-containment.

3.  **Macros:** Extract general macros to the central `.sty` file; keep
    specific ones in the local preamble.

4.  **Context:** Write rich READMEs that include historical anecdotes
    and theoretical significance.

# Next Steps

The user has indicated a pause. The next session should pick up by
identifying the next monograph or key paper to archive. The goal remains
to create a high-quality, semantic dataset for future AI training.
