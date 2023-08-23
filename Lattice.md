# Basics

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

The *minimum distance* of a lattice $\mathcal{L}$ is the length of a shortest nonzero lattice vector
$$
\lambda_1 (\mathcal{L}) := \min_{v \in \mathcal{L} \setminus \{0\} } \|v\|.
$$
