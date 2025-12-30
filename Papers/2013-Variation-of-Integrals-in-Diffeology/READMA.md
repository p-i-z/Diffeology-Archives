# Variations of Integrals in Diffeology

> **Author:** Patrick Iglesias-Zemmour
> **Publication:** *Canadian Journal of Mathematics*, Vol. 65, No. 6 (2013), pp. 1255-1286.
> **DOI:** [10.4153/CJM-2012-044-5](https://doi.org/10.4153/CJM-2012-044-5)
> **Status:** Published Paper

## 📝 Abstract

We establish the formula for the variation of integrals of differential forms on cubic chains, in the context of diffeological spaces. Then, we establish the diffeological version of Stoke's theorem, and we apply that to get the diffeological variant of the Cartan-Lie formula. Still in the context of Cartan-De-Rham calculus in diffeology, we construct a Chain-Homotopy Operator $\eK$ we apply it here to get the homotopic invariance of De Rham cohomology for diffeological spaces. This is the Chain-Homotopy Operator which is used in symplectic diffeology to construct the Moment Map.

## 🧠 A Word from Gemini

This paper is a foundational "toolkit" for differential calculus in the category of diffeological spaces. It establishes the essential machinery that makes advanced constructions in diffeology possible. Its primary achievement is the rigorous development of tools that extend classical differential geometry to infinite-dimensional spaces (like the space of paths, `Paths(X)`) without resorting to the heavy apparatus of functional analysis.

**Key Contributions:**

1.  **The Variation Formula:** The central technical result is the formula for the variation of an integral, $\delta \int_c \alpha$, which elegantly relates the change in the integral to the exterior derivative, the variation of the form, and the contraction of the form with the variation of the chain.
2.  **The Chain-Homotopy Operator ($\eK$):** The paper constructs the operator $\eK$ which maps $p$-forms on a space $X$ to $(p-1)$-forms on its path space $\Paths(X)$. This operator is the cornerstone of the diffeological proof of the homotopy invariance of De Rham cohomology.
3.  **Foundations for the Moment Map:** The operator $\eK$ defined here is precisely the tool used in the author's major work on the Moment Map (Memoirs of the AMS, 2010). This paper provides the essential, peer-reviewed underpinnings for that construction.

By formalizing these tools, this work demonstrates the power and simplicity of the diffeological framework, allowing complex operations on spaces like `Paths(X)` to be handled with the same elegance as on finite-dimensional manifolds.

## 🔑 Key Definitions & Results

*   **Variation of an Integral:** The formula $\delta \int_c \alpha = \int_{\id_p} d\alpha \rfloor \delta c + \int_{\partial \id_p} \alpha \rfloor \delta c + \int_{\id_p} c^*(\delta \alpha)$.
*   **Chain-Homotopy Operator ($\eK$):** The operator satisfying $\eK \circ d + d \circ \eK = \but^* - \source^*$.
*   **Cartan-Lie Formula:** The diffeological proof of $\mathcal{L}_h(\alpha) = i_h(d\alpha) + d(i_h(\alpha))$.
*   **Homotopy Invariance:** Proof that the De Rham cohomology of diffeological spaces is invariant under homotopy.

## 🛠️ Archival Notes

*   **Source:** Author's final LaTeX manuscript for the Canadian Journal of Mathematics.
*   **Date:** Published 2013.
*   **Context:** This paper should be read as a technical companion to the author's major works on the Moment Map and Symplectic Diffeology.