# Open Question 4: Diffeological Integration and Gromov-Witten Invariants

> **Date Added:** January 12, 2026
> — **Status:** Open

### Context

In String Theory and Mirror Symmetry, physical predictions rely on **Enumerative Geometry**, specifically the calculation of Gromov-Witten invariants. These are defined as integrals over the moduli space of pseudo-holomorphic curves $\overline{\mathcal{M}}_{g,n}$.
*   **Fact:** In the algebraic or stack context, points in the moduli space with internal symmetries (automorphisms of order $k$) contribute fractionally ($1/k$) to the total count.
*   **Fact:** Diffeology naturally defines moduli spaces as quotients of functional spaces. However, the standard diffeological quotient is set-theoretic, collapsing orbits to single points.

### The Problem

While Diffeology correctly describes the smooth structure of the moduli space, there is a tension between the "flattening" effect of the quotient map and the need to retain "fractional" data for integration. The stabilizer data exists implicitly within the local plots of the diffeology, but we lack a standard integration theory to extract it.

*   **Question:** Can we develop a native **Diffeological Measure Theory** that automatically detects the local structure groupoid (the "local group" of the plot) to recover these fractional counts? Specifically, is there a formula for integration over a diffeological quotient that yields Gromov-Witten invariants without reverting to the heavy machinery of 2-categories?

### References

[1] Kontsevich, M., and Manin, Y. "Gromov-Witten classes, quantum cohomology, and enumerative geometry." *Communications in Mathematical Physics*, 164.3 (1994): 525-562.

[2] Iglesias-Zemmour, P. *Diffeology*. Mathematical Surveys and Monographs, 185, AMS (2013). (Chapter 1 on Quotients).
