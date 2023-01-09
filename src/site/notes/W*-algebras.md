---
{"dg-publish":true,"permalink":"/w-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true,"dgShowFileTree":true,"dgEnableSearch":true}
---


In the finite-dimensional case, a [[C*-algebras\|C*-algebra]] $\mathscr{A}$ is always reflexive and isomorphic to its dual. Moreover, given a [[C*-algebras#States\|faithful state]] $\omega$, we can define
$$
\langle\mathbf{a}\mid\mathbf{b}\rangle_{\omega}:=\omega(\mathbf{a}^{\dagger}\,\mathbf{b})
$$
for every $\mathbf{a},\mathbf{b}\in\mathscr{A}$, which induces a Hilbert space structure on $\mathscr{A}$. The norm induced by this Hilbert space structure is equivalent to the norm-topology of $\mathscr{A}$ as a C\*-algebra because [all the norms on finite-dimensional vector spaces are equivalent](https://planetmath.org/allnormsonfinitedimensionalvectorspacesareequivalent), so that the norm topology of $\mathscr{A}$ is Hilbertizable. 

Nothing similar is possible in infinite-dimensions because, among other things, there is no reflexive infinite-dimensional C\*-algebra. However, it can happen that $\mathscr{A}$ is the dual space of some Banach space, as it is the case for the Abelian C\*-algebra $\mathcal{L}^{\infty}(M,\mu)$. This type of C\*-algebras presents a very rich theory that not always be extended to general C\*-algebras, thus deserving their own name.


>[!note] Definition (W\*-algebra)
>A complex [[C*-algebras\|C*-algebra]] $\mathscr{M}$ which is the dual space of a Banach space  $\mathscr{M}_{*}$ is called a complex W\*-algebra. The Banach space $\mathscr{M}_{*}$ is called the **predual** of $\mathscr{M}$.

 

# Normal states

A [[C*-algebras#States\|state]] $\omega$ on the [[W*-algebras\|W*-algebra]] $\mathscr{A}$ seen as a C*-algebra is called normal if it is the image of some $\tilde{\omega}\in\mathscr{A}_{*}$ through the canonical identification map $i\colon \mathscr{A}_{*}\rightarrow (\mathscr{A}_{*})^{**}=\mathscr{A}^{*}$.

>[!attention] Remark
>Some, if not most, authors prefer to also impose the normalization condition  $\Vert\omega\Vert=1$ as part of the definition of a state. I prefer to drop such a normalization condition because it [[Normalized vs un-normalized states\|seems artificial to me]] and can always be imposed if/when needed. 
>States satisfying the normalization condition will be referred to as **normalized states**.

In particular, when $\mathscr{A}=\mathcal{B}(\mathcal{H})$, a normal state $\rho$ is a trace-class operator on the Hilbert space $\mathcal{H}$ which happens to be non-negative definite, _i.e._, which is such that its spectrum lies in $[0,+\infty)$. The action of $\rho$ on $\mathcal{B}(\mathcal{H})$ is
$$
\rho(x):=\mathrm{Tr}_{\mathcal{H}}(\rho\,x)
$$
for every $x\in\mathcal{B}(\mathcal{H})$. Often, these states are called **normal quantum states** because of their intimate connection with the standard Hilbert space formulation of Quantum Mechanics.

>[!important] Theorem ([Connes-Stormer-1978](https://www.sciencedirect.com/science/article/pii/002212367890085X))
>
>Let $\mathscr{M}$ be a factor of type $III_{1}$ with separable predual. For every normal states $\omega,\rho$ and for every $\epsilon>0$ there exist a unitary element $\mathbf{U}\in\mathscr{M}$ such that 
>$$
>||\omega_{\mathbf{U}} - \rho||<\epsilon
>$$
>where $\omega_{\mathbf{U}}(\mathbf{x})=\omega(\mathbf{U}^{\dagger}\mathbf{xU} )$.


