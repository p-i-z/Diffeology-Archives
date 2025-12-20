# The Boman Paradox

> **Author:** Patrick Iglesias-Zemmour
> **Status:** Preprint (2025)

## Abstract

It is a commonly held view in the foundations of mathematics, descending from Klein's Erlangen Program, that a geometry is determined by a topological space and a group of symmetries acting upon it. In this note, we present a rigorous counter-example to this intuition: the *Wire Plane* ($\cW$).

We prove that $\cW$ shares the exact same topology as the standard Euclidean plane $\RR^2$ and that its group of diffeomorphisms is algebraically identical to the standard group $\Diff(\RR^2)$. Yet, these two spaces are geometrically distinct: the standard plane has dimension 2, while the Wire Plane has dimension 1.

This phenomenon, which we call the *Boman Paradox* in reference to the theorem that underlies the group isomorphism, is resolved by observing that the identity map between the groups is not a diffeomorphism. Furthermore, we show that the space cannot be reconstructed as the quotient of its group. This result demonstrates that the "geometry" is not contained in the abstract group, nor in the topology. Rather, the *local structure precedes the global symmetry*: the space defines the group, but the group is insufficient to reconstruct the space.

## Significance of the Paper

This paper challenges the foundational principle, descending from Klein's Erlangen Program, that a geometry can be fully characterized by a topological space and its group of symmetries. It provides a definitive counter-example through the construction of the **Wire Plane**, a diffeological space that is topologically and algebraically indistinguishable from the standard Euclidean plane, yet possesses a different dimension.

The core of the paper is the **Boman Paradox**:
1.  The Wire Plane $\cW$ and the standard plane $\RR^2$ are shown to be homeomorphic.
2.  Their groups of diffeomorphisms, $\Diff(\cW)$ and $\Diff(\RR^2)$, are proven to be algebraically isomorphic via the identity map, a result that relies on Boman's Theorem.
3.  Despite this, their geometries diverge fundamentally: $\dim(\cW) = 1$, while $\dim(\RR^2) = 2$.

The paradox is resolved by demonstrating that the algebraic isomorphism between the groups is not a *diffeomorphism* in the diffeological sense. The **diffeological groups** are distinct because the smooth structure of $\Diff(\cW)$ is strictly finer—more rigid—than that of $\Diff(\RR^2)$.

The paper concludes that the local smooth structure (the diffeology) is a primary ingredient of geometry that cannot be recovered from the abstract symmetry group alone. The arrow of definition is irreversible: the space defines its diffeological group, but the group is insufficient to reconstruct the space. This refines the Kleinian ideal, showing that a geometry is determined not by the abstract group, but by the inseparable pair of the diffeological space and the specific diffeological structure of its symmetry group.

## Files in this Directory

*   `TBP.tex`: The complete, self-contained LaTeX source file for the paper.
*   `/figures`: A directory containing the images used in the paper.