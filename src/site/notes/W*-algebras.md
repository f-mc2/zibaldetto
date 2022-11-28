---
{"dg-publish":true,"permalink":"/w-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true,"dgShowFileTree":true,"dgEnableSearch":true}
---


A complex [[C*-algebras\|C*-algebra]] $\mathscr{A}$ which is the dual space of a Banach space $\mathscr{A}_{*}$ is called a complex W*-algebra. The Banach space $\mathscr{A}_{*}$ is called the **predual** of $\mathscr{A}$.

# Normal states

A [[C*-algebras#States\|state]] $\omega$ on the [[W*-algebras\|W*-algebra]] $\mathscr{A}$ seen as a C*-algebra is called normal if it is the image of some $\tilde{\omega}\in\mathscr{A}_{*}$ through the canonical identification map $i\colon \mathscr{A}_{*}\rightarrow (\mathscr{A}_{*})^{**}=\mathscr{A}^{*}$.

>[!important] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.

In particular, when $\mathscr{A}=\mathcal{B}(\mathcal{H})$, a normal state $\rho$ is a trace-class operator on the Hilbert space $\mathcal{H}$ which happens to be non-negative definite, _i.e._, which is such that its spectrum lies in $[0,+\infty)$. The action of $\rho$ on $\mathcal{B}(\mathcal{H})$ is
$$
\rho(x):=\mathrm{Tr}_{\mathcal{H}}(\rho\,x)
$$
for every $x\in\mathcal{B}(\mathcal{H})$. Often, these states are called **normal quantum states** because of their intimate connection with the standard Hilbert space formulation of Quantum Mechanics.