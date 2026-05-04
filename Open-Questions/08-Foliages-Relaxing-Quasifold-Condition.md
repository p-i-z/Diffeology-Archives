# Open Question 8: Foliages: Relaxing the Quasifold Condition

> **Date Added:** April 3, 2026
> — **Status:** Open

### Context

Orbifolds and quasifolds are defined locally as quotients of open subsets of $\mathbf{R}^n$ by actions of countable subgroups of the affine group. This local structure guarantees that the quotient projection admits a generating family (a "strict nebula") for which the preimage of any point is countable, hence discrete in the sense of diffeology. This discrete preimage property is essential for the construction of a C*-algebra associated to the space (via a structure groupoid) and for establishing Morita equivalence.

However, a broader class of spaces satisfies the same discrete preimage condition. Consider any foliation on a manifold. The leaf space (in French: *feuillage*) admits a generating family given by the projections of transversals. In a foliation, a leaf intersects a transversal in at most a countable set, hence discrete. Therefore, every leaf space of a foliation satisfies the discrete preimage condition.

### The Problem

- **Definition:** Call a diffeological space $X$ a *foliage* (from the French *feuillage*, space of leaves) if it admits a generating family $\mathcal F$ such that for every $x \in X$, the set $\mathrm{ev}^{-1}(x) \subset \mathcal N$ is discrete (where $\mathcal N = \coprod_{F \in \mathcal F} \mathrm{dom}(F)$ and $\mathrm{ev}: \mathcal N \to X$ is the evaluation map).

- **Observation:** Every leaf space of a foliation on a manifold is a foliage. Thus, the class of foliages includes all orbifolds, all quasifolds, and all leaf spaces of foliations.

- **Questions:**
  1. Can we relax the local quotient condition defining quasifolds to the weaker discrete preimage condition, thereby obtaining a larger class of spaces (foliages) that still admits a C*-algebra via the structure groupoid construction?
  2. For leaf spaces of foliations, does this construction recover the classical C*-algebra of the foliation (in the sense of Connes)?
  3. When do two foliages (e.g., leaf spaces of two foliations) give Morita-equivalent C*-algebras? this should include being diffeomorphic but is it all?

### References

[1] Iglesias-Zemmour, P. "Lectures on Diffeology", Chapter B31: Foliation and Diffeology.

[2] Iglesias-Zemmour, P. & Karshon, Y. "Orbifolds as Diffeologies", *Transactions of the AMS*, 362.6 (2010): 2811–2831.

[3] Iglesias-Zemmour, P. & Prato, E. "Quasifolds, Diffeology and Noncommutative Geometry", *Journal of Noncommutative Geometry*, 15.2 (2021): 509–548.

[4] Connes, A. "A survey of foliations and operator algebras", *Proceedings of Symposia in Pure Mathematics*, 38 (1982): 521–628.
