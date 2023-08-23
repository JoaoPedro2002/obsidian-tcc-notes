# Basics

For a real number $x \in \mathbb{R}$: 
	$\lfloor x \rfloor$ denote the largest integer not greater then $x$;
	$\lfloor x \rceil := \lfloor x + \frac{1}{2} \rfloor$ denote the integer closest to $x$, with ties broken upward;

## Definition

### Lattice

A n-dimensional *lattice* $\mathcal{L}$ is any subset of $\mathbb{R}^{n}$ that is both:
1. An *addictive subgroup*: $0 \in \mathcal{L}$, and $-x, x + y \in \mathcal{L}$ for every $x, y \in \mathcal{L}$ 
2.  *discrete*: every $x \in \mathcal{L}$  has a neighborhood in $\mathbb{R}^{n}$ in which $x$ is the only lattice point

*Examples:*

- Integer Lattice: $\mathbb{Z}^n$ 
- Scaled Lattice: $c \mathcal{L}$ for any real number c and lattice $\mathcal{L}$
- Checkerboard Lattice:  $\{x \in \mathbb{Z}^{n} : \sum_i x_{i} \text{ is even}\}$ 

### Minimum Distance

The *minimum distance* of a lattice $\mathcal{L}$ is the length of a shortest nonzero lattice vector:
$$
\lambda_1 (\mathcal{L}) := \min_{v \in \mathcal{L} \setminus \{0\} } \|v\|.
$$
[[Definitions#Euclidean Norm]]: $\|\cdot\|$
The $i$th  successive minimum $\lambda_{i}(\mathcal{L})$  is the smallest $r$ such that $\mathcal{L}$ has $i$ linearly independent vectors of norm at most $r$.

### Group Property

Quotient group $\mathbb{R}^{n} / \mathcal{L}$ of cosets
$$
c + \mathcal{L} = \{c + v : v \in \mathcal{L} \}, \;\;\; c \in \mathbb R,
$$
with the usual induced addiction operation: 
$$(c_{1}+ \mathcal{L}) + (c_{2}+ \mathcal{L}) = (c_{1}+ c_{2}) + \mathcal{L} $$
### Fundamental Domain
A *fundamental domain of* $\mathcal{L}$ is a set $\mathcal{F} \subset \mathbb{R}^n$ that contains exactly one representative $\overline c \in (c + \mathcal{L}) \cap \mathcal{L}$ of every coset $c + \mathcal{L}$.
	For example, the half-open intervals $[0,1)$   and $[-\frac{1}{2}, \frac{1}{2})$  are fundamental domains of the integer lattice $\mathbb{Z}$, where $c + \mathbb{Z}$ has representatives $c - \lfloor c \rfloor$ and $c - \lfloor c \rceil$, respectively.

