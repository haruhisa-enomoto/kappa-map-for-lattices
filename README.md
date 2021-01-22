# Kappa map for lattices in sage
This module is for [SageMath](https://www.sagemath.org/).
This adds methods to
a Sage class [`FiniteLatticePoset`](https://doc.sagemath.org/html/en/reference/combinat/sage/combinat/posets/lattices.html#sage.combinat.posets.lattices.FiniteLatticePoset)
which compute the (extended) kappa (dual) map.

Since it's written in Python 3, **it only works on Sage version 9.x or later**.

For a finite semidistributive lattice, the kappa map is a bijective map from the set of join-irreducible elements to the set of meet-irreducible elements, and the inverse map is the kappa dual map. See [BCZ] and [RST] for the detail.
The extended kappa map was introduced in [BCZ], which extends the kappa map by using canonical join representations of elements.

These maps naturally arise in the representation theory of algebra.

## Definitions and Usage
See [manual](Manual.ipynb).

## References

- [BCZ] E. Barnard, G. Todorov, S. Zhu,
  Dynamical Combinatorics and Torsion Classes,
  J. Pure Appl. Algebra 225 (2021), no. 9, 106642.
- [RST] N. Reading, D. E. Speyer, H. Thomas,
  The fundamental theorem of finite semidistributive lattices,
  arXiv:1907.08050.
