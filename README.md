# Kappa map for lattices in SageMath
This module [kappa.py](kappa.py) is for [SageMath](https://www.sagemath.org/).
This adds methods to
a Sage class [`FiniteLatticePoset`](https://doc.sagemath.org/html/en/reference/combinat/sage/combinat/posets/lattices.html#sage.combinat.posets.lattices.FiniteLatticePoset)
which compute the (extended) kappa (dual) map.

For a finite semidistributive lattice, the kappa map is a bijective map from the set of join-irreducible elements to the set of meet-irreducible elements, and the inverse map is the kappa dual map. See [BCZ] and [RST] for the detail.
The extended kappa map was introduced in [BCZ], which extends the kappa map by using canonical join representations of elements.

These maps naturally arise in the representation theory of algebra.

## Definitions and Usage

- See [manual](https://nbviewer.jupyter.org/github/haruhisa-enomoto/kappa-map-for-lattices/blob/main/Manual.ipynb).

- If you are studying representation theory of algebras, we **recommend** to read [note for rep-theorists](https://nbviewer.jupyter.org/github/haruhisa-enomoto/kappa-map-for-lattices/blob/main/for-rep-theorists.ipynb) for motivation.

## References

- [BCZ] E. Barnard, G. Todorov, S. Zhu,
  Dynamical combinatorics and torsion classes,
  J. Pure Appl. Algebra 225 (2021), no. 9, 106642.
- [RST] N. Reading, D. E. Speyer, H. Thomas,
  The fundamental theorem of finite semidistributive lattices,
  arXiv:1907.08050.
