# Diffeology and Arithmetic of Irrational Tori (2025)

> **Author:** Patrick Iglesias-Zemmour
> **Status:** Preprint (2025)

## Abstract

The irrational torus, $T_\alpha$, originally introduced as a geometric model for quasicrystals, is a foundational object in the theory of diffeology. This paper, after recalling its main algebraic properties, provides a comprehensive analysis of a new geometric invariant for this singular space: the group of flows, ${\frak{Fl}}(T_\alpha, \mathbf{R})$. This invariant, which is trivial for all manifolds, arises as the core of the obstruction to the de Rham theorem in the diffeological setting. We provide a complete computation and geometric interpretation of this group, proving the isomorphism ${\frak{Fl}}(T_\alpha, \mathbf{R}) \simeq \mathbf{R} \times \mathrm{coker}(\Delta_\alpha)$. This result establishes a direct link between the intrinsic geometry of the irrational torus and the deep arithmetic (Diophantine) properties of its defining slope.

## Significance of the Paper

This paper delves into the fine geometric structure of the irrational torus, a foundational object in diffeology. It introduces and computes a new, purely diffeological invariant: the **group of flows**, ${\frak{Fl}}(X, \mathbf{R})$, which classifies the $(\mathbf{R},+)$-principal bundles over a diffeological space $X$. While this group is trivial for any manifold, its structure reveals deep geometric and arithmetic information for singular spaces.

The main result is the complete classification of this invariant for the irrational torus $T_\alpha$:

${\frak{Fl}}(T_\alpha, \mathbf{R}) \simeq \mathbf{R} \times \mathrm{coker}(\Delta_\alpha)$, with $\Delta_\alpha(g) = g \circ R_\alpha - g$.

The operator $\Delta_\alpha$ is at the heart of the classical cohomological equation for circle rotations. This theorem establishes a direct and profound link between the intrinsic geometry of $T_\alpha$ and the arithmetic nature of its defining slope $\alpha$:

1.  **For Diophantine $\alpha$**, the cokernel vanishes, and ${\frak{Fl}}(T_\alpha, \mathbf{R}) \simeq \mathbf{R}$. In this "tame" geometric case, every flow can be described by an infinitesimal connection.
2.  **For non-Diophantine (e.g., Liouvillian) $\alpha$**, the cokernel is infinite-dimensional. This reveals a vast family of "exotic" bundles whose non-triviality is purely analytical and cannot be captured by the classical theory of connections. The paper contains an explicit, self-contained proof of this infinite-dimensionality; a result often considered part of the domain's folklore, it was an opportunity to put it somewhere.

This work solidifies the principle that diffeology provides the necessary tools to see how singular spaces retain a precise memory of the arithmetic data used to construct them.

## Files in this Directory

*   `DAAOIT.tex`: The complete, self-contained LaTeX source file for the paper.
*   `/figures`: A directory containing the images used in the paper.
