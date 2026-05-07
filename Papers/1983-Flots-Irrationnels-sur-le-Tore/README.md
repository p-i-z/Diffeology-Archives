# Exemple de groupes difféologiques: flots irrationnels sur le tore (1983 Preprint)

> **Authors:** Paul Donato, Patrick Iglesias-Zemmour
> **Preprint:** CPT-83/P.1524, Centre de Physique Théorique, Marseille (July 1983)
> **Publication:** *Comptes Rendus de l'Académie des Sciences, Série I, Mathématique*, **301**(4), pp. 127–130, 1985.

## Summary

This paper presents the first application of the theory of *groupes différentiels* (differential groups), recently introduced by J.-M. Souriau, to a singular geometric object. In doing so, it introduces the category of *espaces différentiels* (differential spaces)—the precursor to modern diffeology—and defines smooth maps between them. The object of study is the **irrational torus** $`\mathcal{T}_\alpha = T^2 / [\alpha]`$, where $`[\alpha]`$ is the dense winding of a line with irrational slope $`\alpha`$ on the 2-torus—a space with trivial topology but a rich diffeology.

## Historical Significance

This 1983 preprint represents a pivotal moment in the development of diffeology. While Souriau's initial axiomatization focused on *groupes différentiels* (differential groups), this work was the first to apply these ideas to a truly "singular" space, demonstrating the theory's power beyond its original scope.

Its key contributions to the development of the theory are:

1.  **The First Diffeological Singular Space:** The "irrational torus" served as the foundational example of a diffeological space that is not a manifold, paving the way for the study of orbifolds, function spaces, and other generalized spaces.

2.  **The Birth of "Espaces Différentiels":** This paper marks the beginning of the generalization from "diffeological groups" to "diffeological spaces." A key moment is the introduction of smooth maps between these new kinds of spaces. The authors themselves signal the novelty of this concept by placing the term "espace différentiel" in quotes and giving the definition explicitly:

>  Les applications différentiables de $`\mathcal{T}_\alpha`$ à valeurs dans un "espace différentiel" $`E`$, sont les applications $`\varphi : \mathcal{T}_\alpha \to E`$ telles que pour tout $`f`$ élément de $`D(\mathbf{R}^n,\mathcal{T}_\alpha)`$, $`\varphi \circ f`$ est un élément de $`D(\mathbf{R}^n,E)`$. En particulier les difféomorphismes de $`\mathcal{T}_\alpha`$ à $`E`$ sont les bijections bi-différentiables.

This conceptual step—defining a category of spaces with a plot-based smooth structure—was essential for building the broader theory of diffeology as it is known today.

## Key Mathematical Results

The paper establishes several fundamental results about the irrational torus $`\mathcal{T}_\alpha`$ as a diffeological space:

*   **Universal Covering:** The universal covering of $`\mathcal{T}_\alpha`$ is shown to be the real line, $`\mathbf{R}`$.
*   **First Homotopy Group:** The fundamental group, $`\pi_1(\mathcal{T}_\alpha)`$, is computed to be $`\mathbf{Z} \times \mathbf{Z}`$.
*   **Classification:** It is proven that two irrational tori, $`\mathcal{T}_\alpha`$ and $`\mathcal{T}_\beta`$, are diffeomorphic if and only if $`\alpha`$ and $`\beta`$ are equivalent modulo the action of the modular group $`\mathrm{GL}(2,\mathbf{Z})`$.
*   **Diffeomorphism Group:** The group of diffeomorphisms, $`\text{Diff}(\mathcal{T}_\alpha)`$, is fully characterized. A significant distinction emerges: the group of connected components is $`\mathbf{Z}_2`$ for non-quadratic irrationals, but $`\mathbf{Z}_2 \times \mathbf{Z}`$ for quadratic irrationals.

## Files in this Directory

This directory contains the complete archival record for the paper on irrational tori, which originated as a 1983 preprint and was published in 1985.

| File | Description |
|------|-------------|
| **`DIZ83.tex`** | Modern, living LaTeX source file. Transcribed and formatted for modern compilation. Serves as the basis for future corrections or updates. |
| **`DIZ83-preprint-1983.pdf`** | PDF scan of the original **1983 CPT preprint** (CPT-83/P.1524). Historical reference as first circulated. |
| **`DIZ83-published-1985.pdf`** | PDF scan of the final, peer-reviewed article as published in the *Comptes Rendus de l'Académie des Sciences* (1985). The official version of record. |
| **`PIZ83.pdf`** | Clean transcription PDF generated from `DIZ83.tex`. A modern, readable typeset version of the paper for easy reference. |

### Notes on the Modern LaTeX Source (`DIZ83.tex`)

- **Semantic Macros:** This paper uses the common semantic macro system from `../../Common/Diffeology-macros.tex`. Macros like `\fieldR`, `\ringZ`, `\Matrix`, `\Vector`, and `\FundamentalGroup()` provide machine-readable semantic meaning alongside human readability.

- **Notation Notes:** 
  - The irrational torus appears as `\Torus_{\alpha}` (overridden to calligraphic `\cT` for historical fidelity)
  - Projection maps use `\Proj_{\alpha}` instead of the original `\pi_{\alpha}` to avoid conflict with the fundamental group $`\pi_1`$
  - See the Historical Note in the `.tex` file for full details on transcription choices

## Citation

If citing this work, please refer to the published version:

> Donato, P., & Iglesias-Zemmour, P. (1985). Exemple de groupes difféologiques: flots irrationnels sur le tore. *Comptes Rendus de l'Académie des Sciences, Série I, Mathématique*, 301(4), 127-130.

For the preprint version (historical reference):

> Donato, P., & Iglesias, P. (1983). Exemple de groupes différentiels: flots irrationnels sur le tore. Preprint CPT-83/P.1524, Centre de Physique Théorique, Marseille.