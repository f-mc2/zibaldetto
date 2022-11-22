---
{"dg-publish":true,"permalink":"/jordan-algebras-et-similia/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---


creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

# Jordan Algebras

 Let $\mathbb{F}$ be a field of characteristic different than $2$. A **Jordan algebra**  over $\mathbb{F}$ is an $\mathbb{F}$-algebra $\mathcal{J}$ whose product, often written as $\{\cdot,\cdot\}$ or $\circ$, satisfies the following properties:

$$ 
\begin{split}

\{x,y\}&=\{y,x\} \\

\{\{x,y\},\{x,x\}\}&=\{x,\{y,\{x,x\}\}\} .

\end{split}

$$

In general, the product is not-associative.

It is customary to write $x^{2}\equiv \{x,x\}$ for all $x\in\mathcal{J}$ and call it the square of $x$. 

A real Jordan algebra $\mathcal{J}$ is called **formally real** if the sum of any $n$ squares in $\mathcal{J}$ vanishes if and only if all the the terms in the sum vanish individually. The  squares elements in a real, formally real Jordan algebra are also called positive **elements**.

# JB algebras

Let $\mathcal{J}$ be a [[Jordan algebras\|real Jordan algebra]]. If there is a norm $||\cdot||$ on $\mathcal{J}$ making it a real Banach space such that

$$
||\{x,y\}||\leq\,||x||\;||y||,
$$

which means that $\{,\}$ is continuous with respect to $||\cdot||$, we say that $\mathcal{J}$ is a **real Jordan Banach algebra** (note how we write $\mathcal{J}$ instead of the more correct $(\mathcal{J},||\cdot||)$).

If the real Jordan Banach algebra $\mathcal{J}$ satisfies the additional properties

$$
\begin{split}
1) \quad & ||x^{2}|| = || x ||^{2}  \\ & \\
2) \quad & ||x^{2} || \leq ||x^{2} + y^{2}||
\end{split}
$$

for all $x,y\in\mathcal{J}$, then it is called a **JB algebra**.

The typical example of JB algebra is the space of self-adjoint elements of a [[C*-algebras\|C*-algebra]] $\mathscr{A}$ for which the Jordan product is given by the anti-commutator determined by the underlying associative product.