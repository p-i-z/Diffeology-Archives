# The Moment Maps in Diffeology

> **Author:** Patrick Iglesias-Zemmour
> **Publication:** A Memoir of the American Mathematical Society (AMS).
>
> **Official Version:** [Link to the publication on the AMS website](https://www.ams.org/books/memo/0972/)

> **MSC2000:** 53C99, 53D30, 53D20
> **Keywords:** Diffeology, Moment Map, Symplectic Geometry

This memoir presents a complete generalization of the theory of moment maps to the category of Diffeology. The classical theory, a cornerstone of symplectic geometry, was traditionally limited to the smooth actions of Lie groups on finite-dimensional manifolds. This work rebuilds the theory from the ground up on a purely covariant basis, creating a framework that applies universally to any smooth action of any diffeological group on any diffeological space equipped with a closed 2-form.

This generalization is not merely an extension; it is a reformulation that reveals the deeper, underlying principles of the moment map, allowing it to handle infinite-dimensional spaces (like function spaces) and singular spaces (like orbifolds or irrational tori) with the same natural elegance as classical manifolds.

## A New Foundation for the Moment Map

The central innovation of this work is to free the theory from its reliance on "contravariant" objects like Lie algebras and vector fields. This is not merely a technical choice to handle ill-behaved objects in diffeology; it is a fundamental philosophical shift away from what can be called the "mirage of the Lie algebra."

The new foundation is built on the following key principles:

1.  **From the Lie Algebra Mirage to Covariant Momenta:** In classical geometry, the moment map takes values in the dual of the Lie algebra. However, in the infinite-dimensional setting of diffeology (e.g., for the group of diffeomorphisms), the link between the Lie algebra and the group is broken. While a tangent space at the identity exists, the exponential map is not locally surjective—there are diffeomorphisms arbitrarily close to the identity that are not the flow of any vector field. The Lie algebra exists, but it no longer controls the group.

    This memoir recognizes this "dead end" and takes a different path. Instead of trying to reconstruct the geometry from the narrow channel of the tangent space, it works directly with the group itself. The "space of momenta" is redefined on a purely **covariant** basis as the space of left-invariant 1-forms on the diffeological group, denoted $\mathcal G^*$. This space is well-defined for any diffeological group and serves as the natural, global target for the moment map, allowing the construction of invariants that the Lie algebra "cannot see."

2.  **A "Paths-First" Approach:** Instead of working directly on the space $\mathcal X$, the construction is lifted to the space of all smooth paths, $\mathcal{P}aths(\mathcal X)$. Using the chain-homotopy operator ($\mathcal K$), the closed 2-form $\omega$ on $\mathcal X$ is integrated to produce a canonical, group-invariant 1-form on $\mathcal{P}aths(\mathcal X)$. This allows for the construction of a "paths moment map" ($\Psi$) in a universal and straightforward manner.

3.  **Systematic Treatment of Obstructions:** The theory naturally identifies and explains the two fundamental obstructions to perfect symmetry:
    *   **The Holonomy Group ($\Gamma$):** A subgroup of $\mathcal G^*$ arising from the fundamental group of $\mathcal X$. Its non-triviality is precisely the obstruction for an action to be **Hamiltonian**.
    *   **Souriau's Class ($\sigma$):** A cohomology class in $H^1(\mathcal G, \mathcal G^*/\Gamma)$. Its non-triviality is the obstruction for the moment map to be **equivariant**.

## Key Results and Concepts

Building on this new foundation, the memoir develops a complete suite of tools for a generalized symplectic geometry.

*   **Universal Moment Map:** The theory is applied to the action of the *entire group of automorphisms* $\mathop{\mathrm{Diff}}(\mathcal X, \omega)$, yielding a **universal moment map** ($\mu_\omega$) and universal obstructions ($\Gamma_\omega, \sigma_\omega$) that are intrinsic to the space itself.

*   **Hamiltonian Diffeomorphisms:** This universal construction leads to a new, intrinsic definition of the group of **Hamiltonian diffeomorphisms**, $\mathop{\mathrm{Ham}}(\mathcal X, \omega)$, as the largest connected subgroup of $\mathop{\mathrm{Diff}}(\mathcal X, \omega)$ with a vanishing holonomy group.

*   **Symplectic Manifolds as Coadjoint Orbits:** The theory provides a rigorous proof, free of functional analysis, for the principle that "every symplectic manifold is a coadjoint orbit." It shows that a universal moment map identifies a symplectic manifold with a coadjoint orbit of its group of symplectomorphisms.

*   **Broad Applications:** The power of the framework is demonstrated through a wide range of examples that are inaccessible to the classical theory, including:
    *   Singular "symplectic irrational tori."
    *   Infinite-dimensional spaces, such as the space of 1-forms on a surface.
    *   Orbifolds, such as the "corner" and "cone" orbifolds.
    *   The infinite projective space and the Virasoro coadjoint orbits.

## Files in this Directory

*   `TMMID.tex`: The original LaTeX source file for the memoir.
