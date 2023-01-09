---
{"dg-publish":true,"permalink":"/c-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true,"dgShowFileTree":true,"dgEnableSearch":true}
---

Complex C*-algebras can be intuitively considered as the abstract, functional-analytic counterpart of the algebra $\mathcal{M}_{n}(\mathbb{C})$ of square matrices with complex entries. 

>[!note] Definition (Involutive algebra)
Let $(A,+,\cdot)$ be an associative, complex algebra. An involution is an anti-linear map $\dagger \colon A\rightarrow A$ whose square is the identity map. The action of $\dagger$ is often written as $x^{\dagger}$. The quadruple $(A,+,\cdot,\dagger)$ is a complex **involutive algebra**.

>[!note] Definition (C*-algebra)
>Let $(A,+,\cdot,\dagger)$ be a complex involutive algebra. If there is a norm $\Vert\cdot\Vert$ on $A$ such that $(A,+,\cdot)$ is a [[Banach algebras\|Banach algebra]], such that $\dagger$ is continuous with respect to the norm topology, and such that
>$$
>\Vert x^{\dagger}\Vert = \Vert x\Vert
>$$
>then $\mathscr{A}=(A,+,\cdot,\dagger,\Vert\cdot\Vert)$ is a complex **C*-algebra**.

Using the involution $\dagger$ it is possible to introduce the notion of self-adjoint or skew-adjoint element in $\mathscr{A}$. This notion generalizes the idea of bounded self-adjoint linear operator typical of Hilbert space theory.

>[!note] (Self-adjoint elements)
>An element $\mathbf{a}\in \mathscr{A}$ is called **self-adjoint** if $\mathbf{a}^{\dagger}=\mathbf{a}$. The space of self-adjoint elements in $\mathscr{A}$ is denoted as $\mathscr{A}_{sa}$, and it is a **real vector space** with respect to the sum of $\mathscr{A}$. If $\mathscr{A}$ is not Abelian, then $\mathscr{A}_{sa}$ is not an algebra with respect to the product of $\mathscr{A}$. However, $\mathscr{A}_{sa}$ is always a [[Jordan algebras\|Jordan algebra]] with respect to the anti-commutator product
>$$
>\{\mathbf{a}, \mathbf{b}\}:=\frac{1}{2}\left(\mathbf{ab} + \mathbf{ba}\right).
>$$ 
>Moreover, $\mathscr{A}_{sa}$ becomes a real Lie algebra with respect to the (scaled) commutator product
>$$
>[\mathbf{a}, \mathbf{b}]:=\frac{1}{2i}\left[\mathbf{ab} - \mathbf{ba}\right].
>$$
>Since both $\{\cdot,\cdot\}$ and $[\cdot,\cdot]$ both come from the associative product in $\mathscr{A}$, they are mutually compatible in the sense that they provide $\mathscr{A}_{sa}$ with the structure of a [[Jordan-Lie-Banach algebras\|Jordan-Lie-Banach algebra]].

Self-adjoint elements are for $\mathscr{A}$ a little bit like what real numbers are for $\mathbb{C}$. Among other things, $\mathscr{A}_{sa}$ possess an order structure related with the notion of square.

>[!note] (Positive elements)
>An element $\mathbf{P}\in\mathscr{A}_{sa}$ is called **positive** if $\mathbf{P}=\mathbf{a}^{2}=\{\mathbf{a},\mathbf{a}\}$ with $\mathbf{a}\in\mathscr{A}_{sa}$.  The set of all positive elements is denoted by $\mathscr{A}_{+}$, and it is a cone in $\mathscr{A}_{sa}$.  



>[!note] (Skew-adjoint elements)
>An element $\mathbf{b}\in\mathscr{A}$ is called **skew-adjoint** if $\mathbf{b}^{\dagger}=-\mathbf{b}$. Every skew-adjoint element $\mathbf{b}$ can be written as $i\mathbf{a}$ with $\mathbf{a}\in\mathscr{A}_{sa}$. Accordingly, it is customary to denote by $i\mathscr{A}_{sa}$ the space of skew-adjoint elements in $\mathscr{A}$, which is then a **real vector space** with respect to the sum of $\mathscr{A}$. Just as $\mathscr{A}_{sa}$, the space of skew-adjoint elements is not an algebra with respect to the product of $\mathscr{A}$. However, it becomes a real Lie algebra with respect to the (scaled) commutator product
>$$
>[\mathbf{a}, \mathbf{b}]:=\frac{1}{2 }\left[\mathbf{ab} - \mathbf{ba}\right].
>$$ 
>Note that we use the same symbol we used for the Lie product in $\mathscr{A}_{sa}$ even if there is no $i$ in the previous expression. 



# States 

The Banach space dual $\mathscr{A}^{*}$ of $\mathscr{A}$ contains all complex-valued, bounded linear functionals on $\mathscr{A}$.

>[!note] Definition (States on C*-algebras)
>
>An element $\omega\in\mathscr{A}^{*}$ such that 
>$$
>\omega(x^{\dagger}x)\geq 0
>$$
>for every $x\in\mathscr{A}$ is a **state** on $\mathscr{A}$.

>[!important] Proposition (ADD CITATION OR PROOF)
>Let $\mathscr{A}$ be a C*-algebra with unit element $\mathbb{I}$, and let $\omega$ be a state. Then it holds that $\Vert \omega \Vert =\omega(\mathbb{I})$.

>[!attention] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.
