
# Open Question 1: The Hierarchy of Smoothness in Singular Spaces

> **Date Added:** December 21, 2025

### Context

In the theory of singular spaces (orbifolds, quasifolds), there are three competing definitions of a "morphism":

1.  **Satake's Morphisms:** Maps that locally lift to equivariant smooth maps between charts: Fails to form a category because composition is not stable without changing atlases, see:

>   Ichiro Satake, *The Gauss-Bonnet Theorem for V-manifolds*. Journal of the Mathematical Society of Japan, Vol. 9, No. 4,  (1957). Footnote at page 469.
>
>   "The notion of $C^\infty$-map thus defined is inconvenient in the point that a composite of two $C^\infty$-maps defined in a different choice of defining families is not always a $C^\infty$ map."

2.  **Stack Morphisms (Generalized Maps):** Spans or bibundles that preserve the groupoid structure perfectly: Forms a category, but the objects cease to be point-set spaces; they become toposes.
3.  **Diffeological Morphisms:** Maps taking plots to plots: Forms a robust category of point-set spaces, but maps do not always lift equivariantly, see

>   Patrick Iglesias, Yael Karshon and Moshe Zadka. *Orbifolds as Diffeology*. Transactions AMS, **362**:6 (June 2010).


### The Problem

We know these definitions are distinct. Specifically, Diffeology admits "Monster" maps (like IKZ's counter-example) that are smooth but are not Satake-morphisms.

*   **Question:** Can we classify the obstruction that prevents a Diffeological morphism from being a Satake (or Stack) morphism?

*   **Conjecture:** The obstruction lies in the non-triviality of a specific cohomology class associated with the "twisting" of the stabilizer groups along the map. Is there a characteristic class that measures this "failure of equivariance"?
