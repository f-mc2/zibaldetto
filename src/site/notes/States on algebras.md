---
{"dg-publish":true,"permalink":"/states-on-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---


creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

# States on C*-algebras

Let $\mathscr{A}$ be a [[C*-algebras et similia\|C*-algebra]]. An element $\omega\in\mathscr{A}^{*}$ (_i.e._, a bounded linear functional) such that 
$$
\omega(x^{\dagger}x)\geq 0
$$
for every $x\in\mathscr{A}$ is a **state** on $\mathscr{A}$.

# Normal states on W*-algebras

A state $\omega$ on the [[C*-algebras et similia#W*-algebras\|W*-algebra]] $\mathscr{A}$ is called normal if it is the image of some $\tilde{\omega}\in\mathscr{A}_{*}$ through the canonical identification map $i\colon \mathscr{A}_{*}\rightarrow (\mathscr{A}_{*})^{**}=\mathscr{A}^{*}$.

In particular, when $\mathscr{A}=\mathcal{B}(\mathcal{H})$, a normal state $\rho$ is a trace-class operator on the Hilbert space $\mathcal{H}$ which happens to be non-negative definite, _i.e._, which is such that its spectrum lies in $[0,+\infty)$. The action of $\rho$ on $\mathcal{B}(\mathcal{H})$ is
$$
\rho(x):=\mathrm{Tr}_{\mathcal{H}}(\rho\,x)
$$
for every $x\in\mathcal{B}(\mathcal{H})$. Often, these states are called **normal quantum states** because of their intimate connection with the standard Hilbert space formulation of Quantum Mechanics.

# States on JB algebras

Let $\mathcal{J}$ be a [[Jordan algebras et similia#JB algebras\|JB algebra]]. A bounded linear functional $\omega\in\mathcal{J}^{*}$ is a state if 
$$
\omega(x^{2})=\omega(\{x,x\})\geq 0
$$
for all $x\in\mathcal{J}$.


>[!important] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state on all types of algebras considered here (when the algebra has a unit element $\mathbb{I}$ it holds that $\Vert \omega \Vert =\omega(\mathbb{I})$). I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.
