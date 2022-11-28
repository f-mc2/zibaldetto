---
{"dg-publish":true,"permalink":"/on-the-groupoid-picture-of-qm/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---

## Things for "Phyiscs report"

- Spectroscopy and atomic systems ---> groupoids
- Stern-Gerlach ---> groupoids
- Given $\mathcal{H}$, by means of an orthornormal basis I can build the pair groupoid of $\mathbb{N}$.
- Groupoids help in determining the Heisenberg cut through the selection of a M.A.S.A.

1) Introduction (Spectroscopy/Heisenberg)
2) Groupoids and Schwinger's algebra of selective measurements (Stern-Gerlach experiment)
3) Groupoids and Feynman Q.M. (two-slit experiment) (states and observables)
4) Dynamics (Schwinger's dynamical principle) (Stern-Gerlach experiment/Ahranov-Bohm experiment/ Zeeman effect)
5) Composition (Einstein-Podolski-Rosen experiments)

## A sloppy recollection of Feynman's ideas

> (**Feynman's axiom 0**)  The experimental setting we use to describe a system provides a set of "events" $\epsilon$ which are subsets of $\Omega\times T$ where $\Omega$ is the "outcome space" and $T$ is the "time set".

> (**Feynman's axiom 1**) There is a complex number (a.k.a. **amplitude**) associated with every event: $\epsilon \rightarrow \varphi(\epsilon)$. The amplitude of $\epsilon$ is the "sum" of the amplitudes of all alternative ways the event can occur.

> (**Feynman's axiom 2**) The "chance" of event $\epsilon$ is $P(\epsilon):=|\varphi(\epsilon)|^{2}$. This should give a statistical interpretation.

> (**Feynman's axiom 3**) There is a determination equation describing the evolution of $\varphi$.

>(**Feynman's axion 4**) The probability amplitude of a path is proportional to the exponential of a (Lagrangian) action on the path.

## The groupoidal axioms

>(**Groupoidal axiom 1**) Intuitively speaking, the experimental setting we use to describe a system provides a set $\mathbf{G}_{0}$ of **outcomes** and a set $\mathbf{G}_{1}$ of transitions $\alpha\colon x \rightsquigarrow y$ among outcomes $x,y\in\mathbf{G}_{0}$. Mathematically speaking, we have a [[Groupoid\|groupoid]] $\mathsf{G}$ of which $\mathbf{G}_{0}$ is the base space and $\mathbf{G}_{1}$ is the space of morphisms. Since we want to incorporate aspects of probability theory, we will actually need the notion of [[Measure groupoid\|measure groupoid]] $(\mathsf{G},[\mu])$. 

To every measure groupoid $(\mathsf{G},[\mu])$ it is possible to associate a von Neumann algebra $\mathscr{V}_{\mu}(\mathsf{G})$ called the [[Groupoid von Neumann algebra\|groupoid von Neumann algebra]] of $(\mathsf{G},[\mu])$.

>(**Groupoidal axiom 2**) The **observables** of the theory are self-adjoint elements in $\mathscr{V}_{\mu}(\mathsf{G})$.

>(**Groupoidal axiom 3**) The **states** of the theory are the [[States on algebras\|mathematical states]] of $\mathscr{V}_{\mu}(\mathsf{G})$.

>(**Groupoidal axiom 4**) An event is a measurable subset of $\mathbf{G}_{1}$. The amplitude is then $\varphi(\epsilon)=\rho(\mathcal{X}_{\epsilon})$ where $\rho$ is a state on the groupoid von Neumann algebra $\mathscr{V}_{\mu}(\mathsf{G})$ and $\mathcal{X}_{\epsilon}$ is the characteristic function of $\epsilon\subseteq\mathbf{G}_{1}$.

>(**Groupoidal axiom 5**) The "chance" of the event $\epsilon$ is $P(\epsilon)=|\varphi(\epsilon)|^{2}$, which turns out to be a [Quantum measure according to Sorkin](https://arxiv.org/abs/gr-qc/9401003).

>(**Groupoidal axiom 6**) There are two ways of composing physical systems: direct products of groupoids; free product of groupoids. These two composition laws answer different "physical questions".

