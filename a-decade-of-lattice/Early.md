# Ajtai-Dword
- worst to average case reduction
	- Average case short integer solution
- Made a lattice based public key scheme
	- Almost all lattice templates inherit from it
- Pk sizes of $\tilde O(n^4)$
- Sk e Ciphertexts $\tilde O(n^2)$
## Hidden Hyperplanes Problem
let $s \in \mathbb{R}^n$ be a secret random short vector.
- Goal: find s given many points $y_{i} \in \mathbb{R}^n$ such that $\langle s, y_{i} \rangle \approx 0 \; (mod\; 1)$ 

## Cryptosystem
Pkey and Skey are respectiveley a random instance of $\{y_{i}\}$ and it's solution $s$ of the HHP

# NTRU

- First cryptographical construct using polynomial rings
- Compact keys