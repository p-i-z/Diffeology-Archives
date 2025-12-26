# 03-Singularities-on-Corners

> **Date Added:** December 26, 2025

**Related Work:** [Bosonic and Fermionic Singularities in Diffeology](../Papers/2025-Bosonic-and-Fermionic-Singularities-in-Diffeology/)

## Statement of the Problem

Let $\mathcal{C}_n = [0,\infty[^n \subset \mathbb{R}^n$ be the standard $n$-corner equipped with the subset diffeology. Let $\mathcal{S}^k(\mathcal{C}_n)$ be the space of smooth symmetric covariant $k$-tensors on $\mathcal{C}_n$.

In a recent work (Iglesias-Zemmour, 2025), we established the structure of $\mathcal{S}^2(\mathcal{C}_2)$ (the quadrant). We showed that while the diagonal terms (e.g., $dx_1 \otimes dx_1$) can support singularities of the type $1/x_1$, the cross terms (e.g., $dx_1 \otimes dx_2$) must be regular.

**The question is to generalize this decomposition to arbitrary degree $k$ and dimension $n$.**

Specifically, we conjecture that the "Singular Capacity" of a tensor component depends on the multiplicity of the indices in the tensor product.

## Conjecture

Let $\tau$ be a symmetric $k$-tensor on $\mathcal{C}_n$. In the standard coordinates $(x_1, \dots, x_n)$, a component of the tensor can be written as:

$$
\tau_{i_1 \dots i_k}(x) \, dx_{i_1} \otimes \dots \otimes dx_{i_k}
$$

Let $m_j$ be the **multiplicity** of the index $j$ in the sequence $(i_1, \dots, i_k)$. That is, $m_j$ is the number of times the differential $dx_j$ appears in the term.

We conjecture that the coefficient function $\tau_{i_1 \dots i_k}(x)$ can admit a singularity of the form:

$$
\frac{1}{x_1^{p_1} \dots x_n^{p_n}}
$$

if and only if, for every $j \in \{1, \dots, n\}$:

$$
p_j \le \left\lfloor \frac{m_j}{2} \right\rfloor
$$

## Motivation and Context

This question is a natural extension of the "Bosonic/Fermionic" dichotomy observed in the 2025 preprint.

*   **Differential Forms (Fermionic):** For antisymmetric tensors, the multiplicity of any index is at most 1. Thus $\lfloor 1/2 \rfloor = 0$. This recovers the known result that differential forms on corners must be regular (they cannot see the boundary).
*   **Metrics (Bosonic):** For a metric on the quadrant ($k=2$), the term $dx_1^2$ has $m_1=2$, allowing $p_1=1$ (a singularity $1/x_1$). The term $dx_1 dx_2$ has $m_1=1, m_2=1$, forcing $p_1=0, p_2=0$ (regularity).

Proving this general combinatorial rule would provide a complete classification of the singularities allowed by Diffeology on corners. It likely requires analyzing the invariance of the pullback by the squaring map $\text{sq}(u_1, \dots, u_n) = (u_1^2, \dots, u_n^2)$ under the action of the group $\Gamma = (\mathbb{Z}_2)^n$.

## References

1.  P. Iglesias-Zemmour, *Bosonic and Fermionic Singularities in Diffeology*, Preprint, 2025.
2.  S. Gürer and P. Iglesias-Zemmour, *Differential Forms on Manifolds with Boundary and Corners*, Indagationes Mathematicae, 30(5), 2019.
