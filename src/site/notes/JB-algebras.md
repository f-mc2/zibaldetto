---
{"dg-publish":true,"permalink":"/jb-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---


>[!note] Definition (Jordan Banach algebras)
>Let $\mathcal{J}$ be a real Jordan algebra. If there is a norm $||\cdot||$ on $\mathcal{J}$ making it a real Banach space such that
>$$
>\Vert\{x,y\}\Vert\leq\,\Vert x\Vert \;\Vert y\Vert ,
>$$
>which means that $\{,\}$ is continuous with respect to $||\cdot||$, we say that $\mathcal{J}$ is a **real Jordan Banach algebra** (note how we write $\mathcal{J}$ instead of the more correct $(\mathcal{J},||\cdot||)$).

>[!note] Definition (JB-algebras)
>If the real Jordan Banach algebra $\mathcal{J}$ satisfies the additional properties
>$$
>\begin{split}
>1) \quad & \Vert x^{2} \Vert = \Vert x \Vert^{2}  \\ & \\
>2) \quad & \Vert x^{2} \Vert \leq \Vert x^{2} + y^{2}\Vert
>\end{split}
>$$
>for all $x,y\in\mathcal{J}$, then it is called a **JB-algebra**.

The typical example of JB-algebra is the space of [[C*-algebras#Self-adjoint elements\|self-adjoint elements of a C*-algebra]] $\mathscr{A}$ for which the Jordan product is given by the anti-commutator determined by the underlying associative product.

JB-algebras are an appropriate generalization of [[Jordan algebras\|real, formally real Jordan algebras]] to the possibly infinite-dimensional case.

# States 

>[!note] Definition (States on JB-algebras)
>Let $\mathcal{J}$ be a JB-algebra. A bounded linear functional $\omega\in\mathcal{J}^{*}$ is a state if 
>$$
>\omega(x^{2})=\omega(\{x,x\})\geq 0
>$$
>for all $x\in\mathcal{J}$.


>[!important] Proposition (ADD CITATION OR PROOF)
>Let $\mathscr{A}$ be a JB-algebra with unit element $\mathbb{I}$, and let $\omega$ be a state. Then it holds that $\Vert \omega \Vert =\omega(\mathbb{I})$.

>[!attention] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.
