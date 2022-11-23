---
{"dg-publish":true,"permalink":"/c-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---

---

creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

---


>[!note] Definition (Involutive algebra)
Let $(A,+,\cdot)$ be an associative, complex algebra. An involution is an anti-linear map $\dagger \colon A\rightarrow A$ whose square is the identity map. The action of $\dagger$ is often written as $x^{\dagger}$. The quadruple $(A,+,\cdot,\dagger)$ is a complex **involutive algebra**.

>[!note] Definition (C*-algebra)
>Let $(A,+,\cdot,\dagger)$ be a complex involutive algebra. If there is a norm $\Vert\cdot\Vert$ on $A$ such that $(A,+,\cdot)$ is a [[Banach algebras\|Banach algebra]], such that $\dagger$ is continuous with respect to the norm topology, and such that
>$$
>\Vert x^{\dagger}\Vert = \Vert x\Vert
>$$
>then $\mathscr{A}=(A,+,\cdot,\dagger,\Vert\cdot\Vert)$ is a complex **C*-algebra**.

# Self-adjoint elements

# Positive elements 

# Invertible elements

# States 

>[!note] Definition (States on C*-algebras)
>
>Let $\mathscr{A}$ be a C*-algebra. An element $\omega\in\mathscr{A}^{*}$ (_i.e._, a bounded linear functional) such that 
>$$
>\omega(x^{\dagger}x)\geq 0
>$$
>for every $x\in\mathscr{A}$ is a **state** on $\mathscr{A}$.

>[!important] Proposition (ADD CITATION OR PROOF)
>Let $\mathscr{A}$ be a C*-algebra with unit element $\mathbb{I}$, and let $\omega$ be a state. Then it holds that $\Vert \omega \Vert =\omega(\mathbb{I})$.

>[!attention] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.
