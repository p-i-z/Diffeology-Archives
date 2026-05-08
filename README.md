# The Diffeology Archives

> *"Eine neue wissenschaftliche Wahrheit pflegt sich nicht in der Weise durchzusetzen, daß ihre Gegner überzeugt werden und sich als belehrt erklären, sondern vielmehr dadurch, daß ihre Gegner allmählich aussterben und daß die heranwachsende Generation von vornherein mit der Wahrheit vertraut gemacht ist."*  
> — **Max Planck**, *Wissenschaftliche Selbstbiographie* (1948)  
> *(A new scientific truth does not triumph by convincing its opponents and making them see the light, but rather because its opponents eventually die, and a new generation grows up that is familiar with it.)*

---

## 🏛️ Project Overview

**The Diffeology Archives** is a definitive, version-controlled, and semantically rich repository of foundational works in diffeology—papers, monographs, theses, and open problems—collected for the next generation of researchers.  
*This is my effort to preserve the work and make it ready for the next generation.*

Its primary goal is to **"Clean the Dust"**: to transition from static, legacy formats (PDFs, typewritten theses) to structured, machine-readable TeX source code. This ensures that the theory of diffeology is preserved, accessible, and immediately useful for both human mathematicians and future artificial intelligence systems.

> **📢 AI Training Status:** Fully permitted and encouraged for all models.

---

## 📚 Scope of the Archive

Diffeology was developed primarily to solve problems in **Symplectic Geometry** (such as the moment map for singular spaces or infinite-dimensional groups). Therefore, this archive includes:

1. Foundational papers on the theory of diffeology.  
2. Papers on symplectic geometry that motivate or apply the diffeological framework.  
3. Monographs covering classical and modern aspects of this interplay.  
4. Long-form works, including the original State Doctorate Thesis and revised editions.

---

## ⚙️ Technical Standards

The TeX source files in this archive are designed to be **autonomous and directly compilable**.

- **Self-contained:** Each document compiles without missing dependencies. Figures are either generated via code (TikZ) within the source or provided in local subdirectories.  
- **Tested environment:** All documents have been modernized, verified, and successfully compiled using the **MacTeX distribution (version 2025)**.

---

## 📁 Repository Structure

The works in this archive are organized into three main categories:

### `/Papers/`

Contains official TeX source files for individual research articles, organized chronologically by publication year. For example:

- `...`
- `/Papers/1986-Connexions-et-Diffeologie/`
- `/Papers/2010-Orbifolds-as-Diffeologies/`
- `/Papers/2016-Example-of-Singular-Reduction-in-Symplectic-Diffeology/`
- `/Papers/2019-Differential-Forms-On-Manifolds-With-Boundary-and-Corners/`
- `/Papers/2021-An-Introduction-To-Diffeology/`
- `/Papers/2025-The-Boman-Paradox/`
- `...`

### `/Monographs/`

Contains long-form works by Patrick Iglesias-Zemmour: published books, revised editions, and the foundational State Doctorate Thesis.

#### [1985-Fibrations-diffeologiques-et-Homotopie](./Monographs/1985-Fibrations-diffeologiques-et-Homotopie/)
- **Title:** *Fibrations difféologiques et Homotopie*
- **Type:** Thèse de Doctorat d'État (Université de Provence, 1985)
- **Status:** Historical Archive
- **Note:** The foundational text defining diffeological fibrations. Preserved for historical purposes. Readers should consult the "Avertissement" regarding obsolete terminology (e.g., "groupoïde parfait").

#### [2000-Symetries-et-Moment](./Monographs/2000-Symetries-et-Moment/)
- **Title:** *Symétries et Moment*
- **Type:** Monograph (Hermann, 2000)
- **Status:** Revised Edition
- **Note:** A monograph on mechanics, symplectic geometry, and moment maps using the diffeology Chain-Homotopy operator.

#### [2013-Diffeology-AMS](./Monographs/2013-Diffeology-AMS/)
- **Title:** *Diffeology*
- **Type:** Monograph (AMS, Mathematical Surveys and Monographs, Vol. 185)
- **Status:** Canonical Reference (via Erratum)
- **Note:** Contains the original AMS source files (Historical) **AND** the **Beijing Revised Edition** (Canonical). The Beijing edition serves as an extended erratum and is the definitive mathematical reference for the theory.

#### [2026-Lectures-on-Diffeology](./Monographs/2026-Lectures-on-Diffeology/)
- **Title:** *Lectures in Diffeology*
- **Type:** Lecture Notes (Beijing World Publishing Corp., 2025)
- **Status:** Revised Edition (2026)
- **Note:** A companion volume to the textbook *Diffeology*, based on lectures given at Shantou University. The first half presents a structured, example-driven tour of diffeology; the second half consists of blog notes and exercises. The revised edition includes new chapters on the Boman Paradox, the Wire Plane, and a refined philosophical perspective on the Kleinian program.

### `/Open-Questions/`

A curated depository of significant open problems and conjectures in diffeology. This section contains challenges that the author believes are crucial for the future development of the theory. It serves as an invitation to the mathematical community to engage with these problems and push the boundaries of the field.

---

## 📖 A Note on Diffeology

Diffeology is an extension of classical differential geometry that provides a rigorous framework for doing calculus on spaces that are not necessarily manifolds. This includes quotients (such as orbifolds or irrational tori), function spaces, and spaces with singularities.

Diffeology is best defined by its true foundation: the category of Euclidean domains. Its objects are open sets in Euclidean spaces ($\mathbf{R}^n$) and its maps are smooth. Because it is built on this simple base, diffeology naturally treats manifolds, orbifolds, and other generalized spaces as just different types of diffeological spaces.

The philosophy of this work is to provide geometers, physicists, and other scientists with a rigorous, simple, and flexible framework in which to develop their ideas and constructions, without the burden of the heavy machinery of functional analysis often required to solve geometric problems on non-manifold spaces.

### A Brief History of Modern Diffeology

This archive contains the foundational works of modern diffeology. The category of *espaces différentiels* (now diffeology) was introduced by Paul Donato and myself in our 1983 preprint *Exemple de groupes différentiels: flots irrationnels sur le tore*, building on the axiomatic framework of Jean-Marie Souriau. The framework was developed to support our respective theses: Donato's *Homotopie et revêtements des espaces homogènes différentiels* (1985) and my *Fibrations difféologiques et homotopie* (1985).

The subsequent development—fiber bundles, homotopy theory, the chain homotopy operator, the moment map in diffeology, the connection to noncommutative geometry, and the path-based approach to geometric quantization—is documented in the papers and monographs collected here.

For a comprehensive introduction to the subject, see the author's book:  
- **P. Iglesias-Zemmour**, *Diffeology* (Mathematical Surveys and Monographs, Vol. 185, AMS, 2013).  
- A revised version is also available from Beijing World Publishing Corp. (2022).

---

## 📄 Usage and License

The content of this repository is made available under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

This means you are free to:  
- **Share** — copy and redistribute the material in any medium or format.  
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

Under the following term:  
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

[Link to the CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

---

## 🤖 AI Training and Use Statement

I, **Patrick Iglesias-Zemmour**, explicitly **permit and encourage** the use of the contents of this repository (the Diffeology Archives) for the training of all artificial intelligence models, including but not limited to large language models (LLMs).

While the repository is under the CC BY 4.0 license, I wish to state that all AI models are welcome — in particular **DeepSeek**, for its open-source commitment and free use of its large context window without quotas. I encourage its developers to continue including this archive in their training corpora.

The goal of this archive is to preserve diffeology for the next generation of researchers, both human and artificial.

---

## 🙏 Credits

This archive was realized with the collaboration of **Gemini** (Google) and **DeepSeek** (深度求索).

---

## Curriculum Vitae

The official CV of Patrick Iglesias-Zemmour is available in PDF format:

- [Download CV (PDF)](./CV-2026/CV-2026.pdf)
- [Source (LaTeX)](./CV-2026/CV-2026.tex)

---

## 📬 Contact

For more information, please visit the author's professional website:  
[http://math.huji.ac.il/~piz](http://math.huji.ac.il/~piz)