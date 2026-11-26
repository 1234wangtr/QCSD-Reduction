# On the NP-Completeness of Worst-Case (2,1)-Quasi-Cyclic Syndrome Decoding

**Authors:** Tianrui Wang, Anyu Wang (corresponding author), and Xiaoyun Wang

This repository contains the paper *On the NP-Completeness of Worst-Case (2,1)-Quasi-Cyclic Syndrome Decoding*.

## Overview

We study the worst-case $(2,1)$-Quasi-Cyclic Syndrome Decoding problem ($\mathsf{QCSD}_{n,w}$) over $R_n = \mathbb{F}_2[X]/(X^n - 1)$: given explicit polynomials $h, s \in R_n$ and an integer $w \ge 0$, decide whether there exist $x, y \in R_n$ satisfying $x + hy = s$ with equal block weights $|x| = |y| = w$.

- We give a deterministic polynomial-time reduction from 3-Dimensional Matching ($3\mathrm{DM}$) proving that worst-case $\mathsf{QCSD}_{n,w}$ is NP-complete in the low-weight regime $w < \sqrt{n}$.
- The same reduction establishes the NP-completeness of the relaxed upper-bound variant requiring $|x|, |y| \le w$.
- The result extends unconditionally to prime block lengths (and to primes with $2$ as a primitive root under GRH, where $h$ is a unit in $R_n^\times$), as well as to general fixed systematic $(a, b)$-QCSD instances ($1 \le b < a$).