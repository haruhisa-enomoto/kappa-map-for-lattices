# Kappa map for lattices in SageMath
[kappa.py](kappa.py) in this repository is for [SageMath](https://www.sagemath.org/).
This adds methods to
a Sage class [`FiniteLatticePoset`](https://doc.sagemath.org/html/en/reference/combinat/sage/combinat/posets/lattices.html#sage.combinat.posets.lattices.FiniteLatticePoset)
which compute the (extended) kappa (dual) map for finite lattices.

For a finite semidistributive lattice, the kappa map is a bijective map from the set of join-irreducible elements to the set of meet-irreducible elements, and the inverse map is the kappa dual map. See [BCZ] and [RST] for the detail.
The extended kappa map was introduced in [BCZ], which extends the kappa map by using canonical join representations of elements.

These maps naturally arise in the representation theory of algebra.

## Author
[Haruhisa Enomoto](http://haruhisa-enomoto.github.io/)

## Definitions and Usage

- [Manual](https://nbviewer.jupyter.org/github/haruhisa-enomoto/kappa-map-for-lattices/blob/main/Manual.ipynb).

- [Notes for representation theorists](https://nbviewer.jupyter.org/github/haruhisa-enomoto/kappa-map-for-lattices/blob/main/for-rep-theorists.ipynb?flush_cache=true):
I **strongly recommend you to read this** if you are working with representation theory of algebras, not just a lattice theory: this explains how the kappa map arises in the rep-theory, and demonstrates how to use `kappa.py` to study bricks and torsion classes.

## References

- [BCZ] E. Barnard, G. Todorov, S. Zhu,
  Dynamical combinatorics and torsion classes,
  J. Pure Appl. Algebra 225 (2021), no. 9, 106642.
- [RST] N. Reading, D. E. Speyer, H. Thomas,
  The fundamental theorem of finite semidistributive lattices,
  arXiv:1907.08050.
