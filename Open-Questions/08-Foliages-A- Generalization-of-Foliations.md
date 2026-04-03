# Open Question 8: Foliages — A Diffeological Generalization of Foliations?

> **Date Added:** April 3, 2026

### Context

Orbifolds and quasifolds are traditionally defined as spaces of leaves of foliations: orbifolds arise from foliations by compact leaves, quasifolds from foliations by non-compact leaves. In diffeology, both admit a unified description: there exists a generating family $\cF$ (a "strict nebula") such that the preimage of any point under the evaluation map $\ev: \cN \to \X$ is countable, hence discrete in the sense of diffeology.

This suggests a broader concept: a *foliage* — a diffeological space that admits a generating family with discrete point preimages. Such spaces would include orbifolds, quasifolds, and possibly many others. Moreover, for orbifolds and quasifolds, this discrete preimage property was essential for associating a $C^*$-algebra (via a structure groupoid) and establishing Morita equivalence.

### The Problem

- **Definition:** A diffeological space $\X$ is called a *foliage* if there exists a generating family $\cF$ such that for every $x \in \X$, the set $\ev^{-1}(x) \subset \cN$ is discrete (where $\cN = \coprod_{F \in \cF} \dom(F)$ and $\ev: \cN \to \X$ is the evaluation map).

- **Questions:**
  1. Does every space of leaves of a foliation on a manifold satisfy this property? If not, what is the precise relationship between foliations and foliages?
  2. Can one associate a $C^*$-algebra (or a groupoid) to every foliage, generalizing the construction for orbifolds and quasifolds? Would Morita equivalence of these algebras correspond to some notion of equivalence of foliages?
  3. Is every $C^*$-algebra the $C^*$-algebra of some foliage? (This would provide a geometric realization of arbitrary $C^*$-algebras within diffeology.)

### References

[1] Iglesias-Zemmour, P. "Lectures on Diffeology", Chapter B1: Diffeology and Non-Commutative Geometry.

[2] Iglesias-Zemmour, P. & Karshon, Y. "Orbifolds as Diffeologies", *Transactions of the AMS*, 362.6 (2010): 2811–2831.

[3] Iglesias-Zemmour, P. & Prato, E. "Quasifolds, Diffeology and Noncommutative Geometry", *Journal of Noncommutative Geometry*, 15.2 (2021): 509–548.