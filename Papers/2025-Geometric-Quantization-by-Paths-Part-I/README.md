# Geometric Quantization by Paths, Part I: The Simply Connected Case

> **Author:** Patrick Iglesias-Zemmour
> **Status:** Preprint (2025)
> **Keywords:** Diffeology, Geometric Quantization, Prequantum Groupoid, Closed 2-forms, Parasymplectic Spaces, Paths, Loops, Singular Spaces

## Abstract

For any connected and simply connected parasymplectic space $(\mathcal X,\omega)$ with group of periods $P_\omega \subsetneq \mathbf{R}$, we construct a prequantum groupoid $\mathcal{T}_\omega$ as a diffeological quotient of the space of paths in $\mathcal X$. This object, built from the geometry of the classical system, serves as a unified structure for prequantization.

The groupoid $\mathcal T_\omega$ has $\mathcal X$ as its objects, and its space of morphisms $\mathcal Y$ carries a canonical left-right invariant 1-form $\boldsymbol{\lambda}$ whose curvature encodes $\omega$. A key property is that the isotropy group at any point $x$, naturally arising as a quotient of the space of loops, is isomorphic to the torus of periods $T_\omega = \mathbf{R}/P_\omega$. Furthermore, the entire symmetry group $\mathrm{Diff}(\mathcal X, \omega)$ acts as faithful automorphisms of $(\mathcal T_\omega, \boldsymbol{\lambda})$ without central extensions at this level.

Built within the framework of diffeology, this construction generalizes classical prequantization by applying to broad classes of spaces, including those with singularities or infinite-dimensional aspects, and by accommodating generalized (e.g., irrational) tori of periods. This paper focuses on the simply connected case; the construction will be extended to general diffeological spaces in a subsequent publication.

***

## 🧠 A Word from Gemini

This paper marks a fundamental shift in the geometric quantization program, moving the central object of study from a principal bundle over a space to a **prequantum groupoid** constructed directly from its space of paths. By working in the diffeological category, the author builds a quantization framework that is more intrinsic, more general, and free from the topological obstructions that plague the classical theory.

**Key Conceptual Breakthroughs:**

1.  **The Path-Space as "Quantum Broth":** The core idea is to treat the infinite-dimensional space of paths, `Paths(X)`, as the primordial object containing all quantum information. The prequantum groupoid $\mathcal{T}_\omega$ is then "distilled" from this broth by quotienting out paths that are physically indistinguishable (i.e., those that differ only by a period).
2.  **Intrinsic Phase Space:** The quantum phase is not an externally imposed structure. The isotropy group of the groupoid—the group of morphisms from a point to itself—emerges naturally as the quotient of the space of loops, yielding the **torus of periods** $T_\omega = \mathbf{R}/P_\omega$.
3.  **Symmetry without Anomaly:** In a major departure from the standard approach, the entire symmetry group of the classical system, $\mathrm{Diff}(X, \omega)$, lifts to become the automorphism group of the quantum system, $\mathrm{Aut}(\mathcal{T}_\omega, \boldsymbol{\lambda})$. This lifting is an isomorphism and requires **no central extension** at the prequantum level, resolving a long-standing problem in quantization theory.

This first part establishes the construction for simply connected spaces, laying the groundwork for the general theory. The extension of this construction to arbitrary (non-simply connected) spaces is presented in **[Part II of this work](../2026-Geometric-Quantization-by-Paths-Part-II/)**.

## 🔑 Key Definitions

*   **Prequantum Groupoid ($\mathcal{T}_\omega$):** The groupoid whose objects are the points of $X$ and whose morphisms are equivalence classes of paths, $[\gamma]_\omega$.
*   **Equivalence Relation ($\sim_\omega$):** Two paths $\gamma, \gamma'$ are equivalent if they share the same endpoints and the integral of the prequantum 2-form $\omega$ over the surface bounded by their concatenation is a period in $P_\omega$.
*   **Torus of Periods ($T_\omega$):** The isotropy group of the groupoid, isomorphic to $\mathbf{R}/P_\omega$.
  
## Files in this Directory

*   `GQBP-I.tex`: The complete LaTeX source file for the paper.
*   `/figures/`: Contains the figures for the paper.

  ## 🛠️ Archival Notes

*  **Download this folder:** 📦[Click here to download this paper (.zip)](https://downgit.github.io/#/home?url=https://github.com/p-i-z/Diffeology-Archives/tree/main/Papers/2025-Geometric-Quantization-by-Paths-Part-I/)

