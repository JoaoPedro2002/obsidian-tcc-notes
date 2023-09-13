# Short Integer Solution (SIS)

Given many uniformly random elements of a large finite additive group, find a  sufficiently “short” nontrivial integer combination of them that sums to zero.

Parameters: $n$ and $q$ define the group $\mathbb{Z}^{n}_q$, a positive real $\beta$ and a  number $m$ of group elements.
- $n$ is the main hardness parameter;
- $m$ is secondary;
- $q > \beta$   as both being at least a small polynomial $n$.


**Definition($SIS_{n,q,\beta,m}$)**: Given $m$ uniformly random vectors $\pmb{a_{i}} \in \mathbb{Z}^n_q$, forming the columns of a matrix $\pmb{A} \in \mathbb{Z}^{n \times m}_q$, find a nonzero integer vector $\pmb{z} \in \mathbb{Z}^m$ of norm $\|\pmb{z}\| \leq \beta$  such that
$$
f_{\pmb{A}}(\pmb{z}) := \pmb{Az} = \sum_{i}\pmb{a}_{i}\cdot z_{i} = 0 \in \mathbb{Z}^n_q
$$

