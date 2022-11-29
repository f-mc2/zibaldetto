---
{"dg-publish":true,"permalink":"/on-the-groupoid-picture-of-qm/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---


# Motivation for measured groupoids

We require the _act of faith_ of believing that we can associate transitions among outcomes of experiments as a basic building block. Specifically, given an outcome space $\Omega$ that we are able to characterize **operationally** (think to the **configuration space** of classical mechanics and its [phylosophically-distinguished status](https://www.abebooks.com/9780471903390/Dynamical-Systems-Differential-Geometric-Approach-0471903396/plp)), we describe the physical situations we are interested in by means of transitions among elements in $\Omega$. This transitions are abstract (virtual) entities encoding some kind of effective physical interactions that have direct consequences from the point of view of what we can experimentally determine in $\Omega$. We also assume (associative) composability and invertibility among transitions. We thus arrive at an [[Groupoid\|algebraic groupoid]] $\Gamma\rightrightarrows\Omega$ as our foundational mathematical object. This is the counterpart of the Hilbert space/C*-algebra in our formalism.


Given the algebraic groupoid $\Gamma\rightrightarrows \Omega$, we assume a measurable structure on $\Omega$ and perhaps a $\sigma$-finite measure $\mu$ so that we end up with a classical Kolmogorov space. A possible way to interpret this situation is that we want a kind of generalization of probability (measure) theory that is well-adapted to discuss quantum-like situations. 

We argue now that, under additional technical conditions, we obtain the structure of [[Measured groupoids\|measured groupoid]] on $\Gamma$.

Given $\Gamma\rightrightarrows \Omega$ we also have the sequence
$$
1\rightarrow\Gamma_{0}\stackrel{\mathrm{i}}{\rightarrow}\Gamma\stackrel{\pi}{\rightarrow} P(\Omega)
$$
where $\Gamma_{0}$ is group fibration
$$
\Gamma_{0}=\bigcup_{x\in\Omega}\Gamma_{x}
$$
where $\Gamma_{x}$ is the isotropy subgroup of $\Gamma$ at $x\in\Omega$, where $P(\Omega)$ is the total space of the groupoid $P(\Omega)\rightrightarrows\Omega$ where
$$
P(\Omega)=\left\{(x,y)\in\Omega\times\Omega\,|\quad \exists \alpha\in\Gamma\Longrightarrow\; y=t(\alpha),\;x=s(\alpha)\right\} ,
$$
 and $\pi=t\times s$. If $\Gamma$ is connected then $P(\Omega)$ is the pair groupoid of $\Omega$, otherwise it is a subgroupoid of the pair groupoid.
 
Using the measurable structure on $\Omega$ we can give the measurable product structure to $\Omega\times\Omega$ so that the pair groupoid and $P(\Omega)$ become [[Measured groupoids#Measurable groupoids\|measurable groupoids]]. From the purely algebraic point of view, there is always (???) a section $\sigma$ for $\pi$. We endow $\Gamma$ with the smallest measurable structure such that the maps $\mathrm{i},\pi,\sigma$ are all measurable maps. 

>[!attention] **Assumption** 
>We focus only on those cases for which this measurable structure on $\Gamma$ exists. It should be then checked that it holds
>$$
>\Gamma\cong P(\Omega)\times_{\Omega}\Gamma_{0}=\left\{((y,x),\mathrm{g})\in P(\Omega)\times\Gamma_{0}\,|\quad \mathrm{pr}(\mathrm{g})=x \right\},
>$$
>where the projection on $\Gamma_{0}$ is the obvious one, with a measurable isomorphism.

If there is a measure $\mu$ on $\Omega$, we immediately get the measure $\Lambda=\mu\otimes\tilde{\mu}$ on $\Omega\times \Omega$ (where $\tilde\mu$ is mutually absolutely continuous with respect to $\mu$).  The measure $\Lambda$ is naturally desintegrated as
$$
\Lambda(A)=\int_{\Omega}\nu^{x}(A)\mathrm{d}\Lambda(x)
$$
where $\nu^{x}$ is a measure on $\Omega\times\Omega$ with support on $(\mathrm{pr}_{1})^{-1}(x)$. 

We can obtain a measure $\Phi$ on $P(\Omega)$ setting
$$
\Phi(A):=\mu\otimes\tilde{\mu}(A) .
$$
Obviously, if $P(\Omega)$ is of measure zero in $\Omega\times\Omega$, then $\Phi$ is trivial and we should think of something else.

>[!attention] **Assumption**
>We focus on all those cases in which $\Phi$ is well-defined and can be desintegrated analogously to $\Lambda$. 

If $\Gamma_{x}$ is nice enough, it admits a $\sigma$-finite, left-invariant measure (_e.g._, a left Haar measure) $\eta^{x}$.

>[!attention] **Assumption**
>We assume all $\Gamma_{x}$ possess a $\sigma$-finite, left-invariant measure $\eta^{x}$ and that all things are compatible to the point that
>$$
>\tau(A)=\int_{A}\nu^{x}\otimes \eta^{x}(A)\mathrm{d}\mu(x)
>$$
is a good measure on $\Gamma\cong P(\Omega)\times_{\Omega}\Gamma_{0}$ for which $\nu^{x}\otimes \eta^{x}$ is left-equivariant and $\sigma$-finite.

# From measured groupoids to algebras

Once we have a measured groupoid $(\Gamma,[\tau])$ we can build some algebras. The idea is to use complex-valued, measurable functions on $\Gamma$ lying in a vector space $\mathcal{A}$ for which
$$
f\star_{\nu}g(\alpha)=\int_{\Gamma}f(\beta)g(\beta^{-1}\circ \alpha)\mathrm{d}\nu^{t(\alpha)}(\beta) 
$$
is in $\mathcal{A}$ for every $f,g\in\mathcal{A}$, for which 
$$
f^{\dagger}(\alpha):=\overline{f(\alpha^{-1})}
$$
is in $\mathcal{A}$ for every $f\in\mathcal{A}$, and for which $\Pi_{f}$ defined by
$$
\Pi_{f}(\psi)=f\star_{\nu}\psi
$$
determines a bounded linear operator on $\mathcal{H}_{\tau}(\Gamma)=\mathcal{L}^{2}(\Gamma,\tau)$ such that 
$$
\Pi^{\dagger}_{f}=\Pi_{f^{\dagger}}
$$
for every $f\in \mathcal{A}$.

>[!note] **Definition** 
>The groupoid von Neumann algebra $\mathscr{V}_{\tau}(\Gamma)$ of $(\Gamma,[\tau])$ is the double commutant of $\Pi(\mathcal{A})$, while the reduced groupoid C*-algebra $\mathscr{C}_{\tau}(\Gamma)$ of $(\Gamma,[\tau])$ is the norm-closure of $\Pi(\mathcal{A})$. Clearly, these algebra sdepend on the explicit choice of $\tau$ in $[\tau]$.





