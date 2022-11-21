---
{"dg-publish":true,"permalink":"/math-phys/normal-states/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true,"dgShowFileTree":true,"dgEnableSearch":true}
---


creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

# `=this.file.name`


Let $\mathscr{A}$ be a [[C*-algebras\|C*-algebra]]


# Normal quantum states

From the mathematical point of view, a **normal quantum state** $\rho$ is a trace-class operator on a Hilbert space $\mathcal{H}$ which happens to be non-negative definite, _i.e._, which is such that its spectrum lies in $[0,+\infty)$.  

The reason behind the adjective 'quantum' is due to the fact that $\mathcal{H}$ may be interpreted as the Hilbert space associated with a particular quantum physical system according to standard textbook quantum mechanics, so that $\rho$ represents a physical state of the system. 

The reason behind the adjective 'normal' comes from the mathematical theory of [[C*-algebras\|C*-algebras]] (or [[Math-Phys/JB algebras\|JB-algebras]]) in it is related with the continuity of $\rho$, seen as a linear functional on  the C*-algebra $\mathcal{B}(\mathcal{H})$ of bounded linear operators on $\mathcal{H}$  according to the formula $(\mathbf{a}):=\mathrm{Tr}_{\mathcal{H}}(\rho\mathbf{a})$ with $\mathbf{a}\in\mathcal{B}(\mathcal{H})$, with respect to a particular topology on $\mathcal{B}(\mathcal{H})$.

>[!important] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\mathrm{Tr}_{\mathcal{H}}(\rho)=1$ as part of the definition of a normal quantum state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed.

