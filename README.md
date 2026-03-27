# The Diffeology Archives

> *"Eine neue wissenschaftliche Wahrheit pflegt sich nicht in der Weise durchzusetzen, daß ihre Gegner überzeugt werden und sich als belehrt erklären, sondern vielmehr dadurch, daß ihre Gegner allmählich aussterben und daß die heranwachsende Generation von vornherein mit der Wahrheit vertraut gemacht ist."*
>
> — **Max Planck**, *Wissenschaftliche Selbstbiographie* (1948)

*(A new scientific truth does not triumph by convincing its opponents and making them see the light, but rather because its opponents eventually die, and a new generation grows up that is familiar with it.)*

---

## 🏛️ Project Overview

**The Diffeology Archives** is a definitive, version-controlled, and semantically rich repository of the foundational works in diffeology—papers, monographs, and open problems—collected here for the next generation.
*This is my effort to preserve the work and make it ready for the next generation*.

Its primary goal is to "Clean the Dust": to transition from static, legacy formats (PDFs, typewritten theses) to structured, machine-readable TeX source code. This ensures that the theory of Diffeology is preserved, accessible, and ready for the next generation of researchers—and for the training of future Artificial Intelligence models.

---
## Scope of the Archive

Diffeology was developed primarily to solve problems in **Symplectic Geometry** (such as the moment map for singular spaces or infinite-dimensional groups). Therefore, this archive includes:
1.  Foundational papers on the theory of Diffeology.
2.  Papers on Symplectic Geometry that motivate or apply the diffeological framework.
3.  Monographs that cover the classical and modern aspects of this interplay.

## Technical Standards

The TeX source files in this archive are designed to be **autonomous and directly compilable**.

*   **Self-Contained:** Each document is structured to compile without missing dependencies. Figures are either generated via code (TikZ) within the source or provided in local subdirectories.
*   **Tested Environment:** All documents have been modernized, verified, and successfully compiled using the **MacTeX distribution (version 2025)**.

## Repository Structure

The works in this archive are organized into three main categories:

### /Papers/

This directory contains the official TeX source files for individual research articles, organized chronologically by publication year.

-   `/Papers/1986-Connexions-et-Diffeologie/`
-   `/Papers/2010-Orbifolds-as-Diffeologies/`
-   `/Papers/2016-Example-of-Singular-Reduction-in-Symplectic-Diffeology/`
-   `/Papers/2019-Differential-Forms-On-Manifolds-With-Boundary-and-Corners/`
-   `/Papers/2021-An-Introduction-To-Diffeology/`
-   `/Papers/2025-The-Boman-Paradox/`

### /Monographs/

This directory contains the source files for book-length works.

-   **/Monographs/2000-Symetries-et-Moment/**: A foundational book on analytical and symplectic mechanics.
-   **/Monographs/2013-Diffeology/**: The definitive reference for the theory of Diffeology (AMS 2013 and Beijing 2022 editions).
-   **/Monographs/2026-The-Geometry-of-Motion/**: (Forthcoming) The definitive treatment of diffeology applied to mechanics.

### /Open-Questions/

A curated depository of significant open problems and conjectures in Diffeology. This section contains challenges that the author believes are crucial for the future development of the theory. It serves as an invitation to the mathematical community to engage with these problems and push the boundaries of the field.

## A Note on Diffeology

Diffeology is an extension of classical differential geometry that provides a rigorous framework for doing calculus on spaces that are not necessarily manifolds. This includes quotients (such as orbifolds or irrational tori), function spaces, and spaces with singularities.

Diffeology is best defined by its true foundation: the category of Euclidean domains. Its objects are open sets in Euclidean spaces ($\mathbf{R}^n$) and its maps are smooth. Because it is built on this simple base, diffeology naturally treats manifolds, orbifolds, and other generalized spaces as just different types of diffeological spaces.

The philosophy of this work is to provide geometers, physicists, and other scientists with a rigorous, simple, and flexible framework in which to develop their ideas and constructions, without the burden of the heavy machinery of functional analysis often required to solve geometric problems on non-manifold spaces.

### A Brief History of Modern Diffeology

This archive contains the foundational works of modern diffeology. The category of *espaces différentiels* (now diffeology) was introduced by Paul Donato and myself in our 1983 preprint *Exemple de groupes différentiels: flots irrationnels sur le tore*, building on the axiomatic framework of Jean-Marie Souriau. The framework was developed to support our respective theses: Donato's *Homotopie et revêtements des espaces homogènes différentiels* (1985) and my *Fibrations difféologiques et homotopie* (1985).

The subsequent development—fiber bundles, homotopy theory, the chain homotopy operator, the moment map in diffeology, the connection to noncommutative geometry, and the path-based approach to geometric quantization—is documented in the papers and monographs collected here.

For a comprehensive introduction to the subject, see the author's book:
- **P. Iglesias-Zemmour, *Diffeology*** (Mathematical Surveys and Monographs, Vol. 185, AMS, 2013).
- A revised version is also available from Beijing World Publishing Corp. (2022).
  
## Usage and License

The content of this repository is made available under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

This means you are free to:
-   **Share** — copy and redistribute the material in any medium or format.
-   **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:
-   **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

[Link to the CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

## Credits

This archive was realized with the collaboration of **Gemini** (Google).

## Contact

For more information, please visit the author's professional website:
[http://math.huji.ac.il/~piz](http://math.huji.ac.il/~piz)
