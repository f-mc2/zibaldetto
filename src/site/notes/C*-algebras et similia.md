---
{"dg-publish":true,"permalink":"/c-algebras-et-similia/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":true,"dgShowInlineTitle":false,"dgShowFileTree":true,"dgEnableSearch":true}
---



creation date: **`=this.file.ctime`** 
date of last modification: **`=this.file.mtime`**

# Banach algebras

Let $(B,+,\cdot)$ be an associative algebra over $\mathbb{R}$ or $\mathbb{C}$. Assume there is a norm $\Vert\cdot\Vert$ on $(B,+)$ making it a Banach space and such that
$$
\Vert xy\Vert \leq \Vert x\Vert \; \Vert y\Vert,
$$
so that the product is continuous. Then $\mathcal{B}=(B,+,\cdot,\Vert\cdot\Vert)$ is said to be a **Banach algebra** over $\mathbb{R}$ or $\mathbb{C}$.

# Involutive algebras

Let $(A,+,\cdot)$ be an associative, complex algebra. An involution is an anti-linear map $\dagger \colon A\rightarrow A$ whose square is the identity map. The action of $\dagger$ is often written as $x^{\dagger}$. The quadruple $(A,+,\cdot,\dagger)$ is a complex **involutive algebra**.

# C*-algebras

Let $(A,+,\cdot,\dagger)$ be a complex involutive algebra. If there is a norm $\Vert\cdot\Vert$ on $A$ such that $(A,+,\cdot)$ is a Banach algebra, such that $\dagger$ is continuous with respect to the norm topology, and such that
$$
\Vert x^{\dagger}\Vert = \Vert x\Vert
$$
then $\mathscr{A}=(A,+,\cdot,\dagger,\Vert\cdot\Vert)$ is a complex **C*-algebra**.

# W*-algebras

A complex C*-algebra $\mathscr{A}$ which is the dual space of a Banach space $\mathscr{A}_{*}$ is called a complex W*-algebra. The Banach space $\mathscr{A}_{*}$ is called the **predual** of $\mathscr{A}$, and it can be proved that it is unique (up to Banach space isomorphisms).

