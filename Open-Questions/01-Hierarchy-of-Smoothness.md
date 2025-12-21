# Open Question 1: The Hierarchy of Smoothness in Singular Spaces

> **Date Added:** December 21, 2025

### Context

In the theory of singular spaces (such as orbifolds and quasifolds), there are three competing definitions of a "morphism:"

1.  **Satake's Morphisms:** These are maps that locally lift to equivariant smooth maps between charts.
    *   **Limitation:** This definition fails to form a category. As Satake himself noted, the composition of two such maps is not guaranteed to be a map of the same type. In his foundational paper, he wrote:

      > "The notion of $C^\infty$-map thus defined is inconvenient in the point that a composite of two $C^\infty$-maps defined in a different choice of defining families is not always a $C^\infty$ map."

3.  **Stack Morphisms (Generalized Maps):** These are spans or bibundles that perfectly preserve the underlying groupoid structure.
    *   **Limitation:** This forms a robust category, but at the cost of abandoning point-set spaces in favor of more abstract objects like toposes.

4.  **Diffeological Morphisms:** These are maps that preserve the smooth structure by sending plots to plots.
    *   **Limitation:** This forms a robust category of point-set spaces, but as demonstrated in, these maps do not always lift equivariantly.

### The Problem

We know these definitions are distinct. Specifically, Diffeology admits smooth maps (such as the counter-example presented in) that are not Satake-morphisms. This raises a fundamental question about the relationship between these structures.

*   **Question:** Details the relation between these behaviors. Can we classify the obstruction that prevents a Diffeological morphism from being a Satake (or Stack) morphism?

### References

 Satake, I. "The Gauss-Bonnet Theorem for V-manifolds." *Journal of the Mathematical Society of Japan*, Vol. 9, No. 4 (1957), p. 469, footnote.

 Iglesias-Zemmour, P., Karshon, Y., and Zadka, M. "Orbifolds as Diffeology." *Transactions of the American Mathematical Society*, Vol. 362, No. 6 (2010).
