---
{"dg-publish":true,"permalink":"/math-phys/ig-and-jordan-algebras/","dgPassFrontmatter":true}
---


creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

# `=this.file.name`

## Introduction


Here I would like to discuss about what I think is an interesting connection between Jordan algebras, the symplectic aspects of [Kirillov's theory of coadjoint orbits](https://en.wikipedia.org/wiki/Orbit_method), the [[F-R tensor fin-dim\|F-R tensor fin-dim]] on strictly positive measures on a discrete and finite sample space, and the [[B-H tensor fin-dim\|B-H tensor fin-dim]] on faithful [[Math-Phys/Normal states\|normal quantum states]].

The thorough mathematical treatment of what I am about to discuss can be found in the work ["What can Lie algebras tell us about Jordan algebras"](https://arxiv.org/abs/2112.09781) written in collaboration with Jürgen Jost and Lorenz Schwachhöfer.

Let me start discussing why I am interested in (positive functionals on) Jordan algebras. 

Part of my research is devoted to the study of [classical and quantum information geometry](https://math.stackexchange.com/a/4221413/86146). On the one hand, classical information geometry deals with differential geometric aspects of suitable families of probability distributions on a measure space $(\mathcal{X},\mu)$ associated with a given classical system. On the other hand, quantum information geometry deals with differential geometric aspects of suitable families of quantum states, that is, positive semi-definite, trace-class operators with unit trace on the complex Hilbert space $\mathcal{H}$ of associated with a given quantum system.

It is clear that  classical information geometry and quantum information geometry are formulated using different mathematical settings, however, it is also true that some similarities and analogies between these two “theories” are - more often than not - remarked and exploited by people working in these fields. However, upon closer inspection, it can be realized that classical and quantum information geometry can actually be formulated using the same mathematical framework, and that framework is that of states on real, formally real  Jordan algebras. 


A real Jordan algebra $\mathcal{J}$ is a real, possibly non-associative algebra such that its product, often written as $\{\cdot,\cdot\}$, satisfies the following properties:

$$ 
\begin{split}

\{x,y\}&=\{y,x\} \\

\{\{x,y\},\{x,x\}\}&=\{x,\{y,\{x,x\}\}\} .

\end{split}

$$

A real Jordan algebra $\mathcal{J}$ is called **formally real** if the sum of any $n$ squares in $\mathcal{J}$ vanishes if and only if all the the terms in the sum vanish individually. The  squares elements in a real, formally real Jordan algebra are also called positive elements, and every bounded linear functional on $\mathcal{J}$ which takes non-negative values on positive elements is called **positive**. 

We will see that classical probability distributions and [[Math-Phys/Normal states\|normal quantum states]] are both concrete instances of positive linear functional on suitable real, formally real Jordan algebras.

By means of integration theory, we see that probability distributions on $(\mathcal{X},\mu)$ can actually  be considered as linear functional on the algebra $\mathcal{F}(\mathcal{X})$ of real-valued, measurable functions on $(\mathcal{X},\mu)$. The pointwise product in $\mathcal{F}(\mathcal{X})$ is commutative and associative, and it is not hard to see that $\mathcal{F}(\mathcal{X})$ is an example of real, formally real Jordan algebra which is also associative.  One key feature  of probability distributions is that, as linear functionals on $\mathcal{F}(\mathcal{X})$, they always take non-negative values on non-negative functions in $\mathcal{F}(\mathcal{X})$.  Clearly, every non-negative function $f\in \mathcal{F}(\mathcal{X})$ can be written as $f=g^2=\{g,g\}$ for some $g\in\mathcal{F}(\mathcal{X})$,  thus we can say that probability distributions take non-negative values on positive elements of the Jordan algebra $\mathcal{F}(\mathcal{X})$. If we want additional analytic structures, we should actually pass from $\mathcal{F}(\mathcal{X})$ to $\mathcal{L}^{\infty}(\mathcal{X},\mu)$ which is also a Banach space and thus a [[Math-Phys/JB algebras\|JB algebras]]. 

 

The “same picture” arises when we look at quantum information geometry from the point of view of real, formally real Jordan algebras, with the exception that, in the quantum case, we need a different Jordan algebra which is no longer associative. Specifically, trace-class operators on $\mathcal{H}$ are an ideal in the associative, complex algebra $\mathcal{B}(\mathcal{H})$ of bounded linear operators on $\mathcal{H}$. The complex algebra $\mathcal{B}(\mathcal{H})$  also possesses a bounded involution map $\dagger$, that is, an anti-linear, bounded map such that its square is the identity. Concretely, the involution map $\dagger$ sends $\mathbf{a}$ into its adjoint $\mathbf{a}^{\dagger}$. Since $(\mathbf{a}^{\dagger})^{\dagger}=\mathbf{a}$, it follows that every element $\mathbf{a}\in\mathcal{B}(\mathcal{H})$ can be written as $\mathbf{a}=\mathbf{x} + i\mathbf{y}$ where $\mathbf{x},\mathbf{y}\in\mathcal{B}(\mathcal{H})$ are such that $\mathbf{x}=\mathbf{x}^{\dagger}$ and $\mathbf{y}=\mathbf{y}^{\dagger}$. Elements like $\mathbf{x}$ and $\mathbf{y}$ are precisely the bounded, self-adjoint linear operators on $\mathcal{B}(\mathcal{H})$, and the set of all such operators is denoted as $\mathcal{B}_{sa}(\mathcal{H})$. Now, $\mathcal{B}_{sa}(\mathcal{H})$ is not a complex subspace of $\mathcal{B}(\mathcal{H})$ but it is a real vector space on its own - actually, it becomes a Banach space under the "same" norm of $\mathcal{B}(\mathcal{H})$. Moreover, if we exploit the associative product in $\mathcal{B}(\mathcal{H})$ to define the anti-commutator product 

$$  
\{\mathbf{x},\mathbf{y}\}:=\frac{1}{2}\left(\mathbf{x}\mathbf{y} +\mathbf{y}\mathbf{x}\right)
$$
in  $\mathcal{B}_{sa}(\mathcal{H})$, we obtain that $\mathcal{B}_{sa}(\mathcal{H})$ with the anti-commutator product given above becomes a real Jordan algebra which is easily seen to be also formally real. Clearly, positive elements in  $\mathcal{B}_{sa}(\mathcal{H})$ are nothing but bounded, positive semi-definite linear operators on $\mathcal{H}$. Now, since trace-class operators form an ideal in $\mathcal{B}(\mathcal{H})$, given a trace-class operator $\rho$, the expression $Tr(\rho\mathbf{a})$ is finite for every $\mathbf{a}\in\mathcal{B}(\mathcal{H})$. In particular, if $\rho$ is positive semi-definite and $\mathbf{a}$ is self-adjoint, we have that every such $\rho$ defines a bounded linear functional on the real, formally real Jordan algebra $\mathcal{B}_{sa}(\mathcal{H})$ which takes non-negative values on positive elements.

 
At this point, we can say that classical and quantum information geometry both deal with differential geometric aspects of suitable families  of positive linear functionals on real, formally real Jordan algebras.  This instance gives us a common mathematical background in which to place classical and quantum information geometry, and thus leads us to conjecture that some of the geometrical entities emerging in these fields are actually different manifestations of the same geometrical entities when everything is looked at a through the unifying perspective offered by Jordan algebras. 

The purpose of this note is to "prove" this conjecture for one very important type of geometrical entity appearing in both classical and quantum information geometry. Specifically, the Fisher-Rao metric tensor and the Bures-Helstrom metric tensor.  






The resulting manifolds are examples of [[Parametric models on JB-algebras\|parametric models of normal states on JB-algebras]].

