# Open Question 2: Is Distribution Theory Intrinsic to Diffeology?

> **Date Added:** December 26, 2025

### Context

In Diffeology, we observe that objects traditionally classified as "distributions" (generalized functions) often appear as standard smooth geometric objects, provided we look at the correct space. There are two striking instances of this phenomenon:

1.  **Symplectic Geometry (The Moment Map):**
    The moment map $\mu$ for a diffeological group $G$ acting on a presymplectic space $M$ is defined as taking its values in the space of left-invariant 1-forms on the group, $\Omega^1_{\text{inv}}(G)$ [1].
    *   **Example:** For the group $G = \mathcal{C}^\infty(\Sigma, \mathbb{R})$ acting on the space of 1-forms, the moment map is given by $\mu(\alpha) = d[f \mapsto \int_\Sigma f d\alpha]$.
    *   **Observation:** Classically, the functional $f \mapsto \int f d\alpha$ is viewed as a distribution (a current). In Diffeology, it is simply a smooth 1-form on the functional space $G$.

2.  **Singular Geometry (Tensors on Corners):**
    As shown in the study of the half-line and quadrant [2], symmetric tensors can support singularities (e.g., $dx^2/x$) that are "regularized" by the plots.
    *   **Observation:** The tensor behaves like a distribution with a specific "singular capacity" determined by its rank ($\kappa(k) = \lfloor k/2 \rfloor$), yet it remains a smooth section of the tensor bundle in the diffeological sense.

### The Problem

Classically, analysis on singular spaces or infinite-dimensional spaces requires the introduction of Topological Vector Spaces and the theory of Schwartz distributions (duals of nuclear spaces, etc.). However, Diffeology seems to handle these objects geometrically via the functional diffeology of duals and the testing of tensors by plots.

*   **Question:** Does Diffeology need to import an independent theory of distributions, or is the "Theory of Distributions" simply the study of **Differential Forms on Functional Diffeological Spaces** and **Tensors on Singular Spaces**?

### Hypothesis

It is likely that Diffeology contains its own intrinsic theory of generalized functions.
*   A "distribution" is not a singular functional on smooth functions; it is a **smooth form** on a "large" (functional) space.
*   A "singular field" is not a meromorphic section; it is a **smooth tensor** on a "singular" space (tested by plots).

The open task is to formalize the dictionary between the analytic properties of distributions (order, support, wavefront set) and the geometric properties of these diffeological forms and tensors.

### References

[1] Iglesias-Zemmour, P. *The Moment Maps in Diffeology*. Memoirs of the American Mathematical Society, Vol. 207, No. 972 (2010).

[2] Iglesias-Zemmour, P. "Bosonic and Fermionic Singularities in Diffeology." *Proceedings of the American Mathematical Society* (Submitted, 2025).