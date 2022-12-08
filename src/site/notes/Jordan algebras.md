---
{"dg-publish":true,"permalink":"/jordan-algebras/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true,"dgShowInlineTitle":true,"dgShowFileTree":true,"dgEnableSearch":true}
---


 Let $\mathbb{F}$ be a field of characteristic different than $2$. A **Jordan algebra**  over $\mathbb{F}$ is an $\mathbb{F}$-algebra $\mathcal{J}$ whose product, often written as $\{\cdot,\cdot\}$ or $\circ$, satisfies the following properties:

$$ 
\begin{split}

\{x,y\}&=\{y,x\} \\

\{\{x,y\},\{x,x\}\}&=\{x,\{y,\{x,x\}\}\} .

\end{split}

$$

In general, the product is not-associative.

It is customary to write $x^{2}\equiv \{x,x\}$ for all $x\in\mathcal{J}$ and call it the square of $x$. 

Some Jordan algebras are **special** in the following sense. There is an associative algebra $\mathcal{A}$ of which $\mathcal{J}$ is a vector subspace, and the Jordan product in $\mathcal{J}$ can be expressed in terms of the associative product in $\mathcal{A}$ according to

$$
\{x,y\}=\frac{1}{2}\left(xy + yx\right).
$$

Jordan algebras that are not special are called **exceptional**. The typical example of special Jordan algebras is the algebra of bounded, self-adjoint linear operators on a Hilbert space.

# Jordan triple product

Every Jordan algebra is naturally endowed with a so-called **Jordan triple** product. To define it, we first introduce the linear map $M_{x}:\mathcal{J}\rightarrow\mathcal{J}$ given by

$$
M_{x}(y)=\{x,y\},
$$
the linear map $U_{x}:\mathcal{J}\rightarrow\mathcal{J}$ given by

$$
U_{x}=2M_{a} - M_{a^{2}},
$$

and the linear map $U_{x,y}:\mathcal{J}\rightarrow\mathcal{J}$ given by

$$
U_{x,y}=M_{x}M_{y} + M_{y}M_{x} - T_{\{x,y\}}.
$$

Then,  the so-called **Jordan triple product** $\{\cdot,\cdot,\cdot\}\colon\mathcal{J}\times\mathcal{J}\times\mathcal{J}\rightarrow\mathcal{J}$ reads

$$
\{x,y,z\}:=U_{x,z}(y).
$$

If $\mathcal{J}$ is special, then

$$
\{x,y,z\}=\frac{1}{2}\left(xyz + zxy\right).
$$

# Formally real Jordan algebras 

A real Jordan algebra $\mathcal{J}$ is called **formally real** if the sum of any $n$ squares in $\mathcal{J}$ vanishes if and only if all the the terms in the sum vanish individually. The  squares elements in a real, formally real Jordan algebra are also called positive **elements**.
 