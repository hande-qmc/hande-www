.. title: HANDE
.. slug: index
.. date: 2014-07-16 00:35:00 UTC+01:00
.. tags: 
.. link: 
.. description: 
.. type: text

HANDE
=====

HANDE is an open-source software package for stochastic quantum chemistry under active
development, run by a non-profit community of UK academics headed by Dr Alex Thom (University of Cambridge),
and formerly Dr James Spencer (Imperial College London).

HANDE contains highly scalable implementations of the full configuration interaction
quantum Monte Carlo [1]_ and coupled cluster Monte Carlo [2]_ methods including the
initiator approximation [3]_ and semi-stochastic approach [4]_, as well as the
density matrix quantum Monte Carlo method [5]_.
HANDE can treat a variety of quantum systems, including molecular systems (via
integrals obtained from a quantum chemistry package) and the uniform electron
gas as well as the Hubbard and Heisenberg models.

HANDE version 1.3 can be obtained from https://github.com/hande-qmc/hande.

For any questions on using and/or developing HANDE, please contact Alex in the
first instance:

| Alex Thom, ajwt3@cam.ac.uk

HANDE development team
----------------------

Code, theory, applications, etc:

* Alex Thom (University of Cambridge)
* Nick Blunt (University of Cambridge)
* Fionn Malone (Lawrence Livermore National Laboratory)
* Charlie Scott (University of Cambridge)
* Verena Neufeld (University of Cambridge)
* James Shepherd (University of Iowa)
* James Spencer (Imperial College London)
* Matthew Foulkes (Imperial College London)

Past contributors:

* Seonghoon Choi (was at University of Cambridge, now EPFL Lausanne)
* Thomas Rogers (Imperial College London)
* Will Handley (University of Cambridge)
* Joseph Weston (Imperial College London)
* William Vigor (Imperial College London)
* Ruth Franklin (University of Cambridge)

For an overview of HANDE see

J.S. Spencer, N.S. Blunt, S. Choi, J. Etrych, M.-A. Filip, W.M.C. Foulkes, R.S.T. Franklin, W.J. Handley, F.D. Malone, V.A. Neufeld, R. Di Remigio, T.W. Rogers, C.J.C. Scott, J.J. Shepherd, J. Weston, W.A. Vigor, R. Xu, A.J.W. Thom. The HANDE-QMC project: open-source stochastic quantum chemistry from the ground state up, `arXiv preprint arXiv:1811.11679 (2018) <https://arxiv.org/abs/1811.11679>`_.


Publications
------------
V.A. Neufeld, A.J.W. Thom. Exciting determinants in Quantum Monte Carlo: Loading the dice with fast, low memory weights, `J. Chem. Theory Comput. in press (2019) <https://doi.org/10.1021/acs.jctc.8b00844>`_

J.S. Spencer, V.A. Neufeld, W.A. Vigor, R.S.T. Franklin, A.J.W. Thom. Large scale parallelization in stochastic coupled cluster,  `J. Chem. Phys. 149, 204103 (2018) <https://doi.org/10.1063/1.5047420>`_.

V.A. Neufeld, A.J.W. Thom. A study of the dense uniform electron gas with high orders of coupled cluster, `J. Chem. Phys. 147, 194105 (2017) <https://doi.org/10.1063/1.5003794>`_.

C.J.C. Scott, A.J.W. Thom. Stochastic coupled cluster theory: Efficient sampling of the coupled cluster expansion, `J. Chem. Phys. 147, 124105 (2017) <https://doi.org/10.1063/1.4991795>`_.

\T. Dornheim, S. Groth, F. D. Malone, T. Schoof, T. Sjostrom, W.M.C. Foulkes, M. Bonitz. Ab initio quantum Monte Carlo simulation of the warm dense electron gas, `Phys. Plasmas 24, 056303 (2017) <https://doi.org/10.1063/1.4977920>`_.

F.D. Malone, N.S. Blunt, E.W. Brown, D.K.K. Lee, J.S. Spencer, W.M.C. Foulkes, J.J. Shepherd. Accurate exchange-correlation energies for the warm dense electron gas, `Phys. Rev. Lett. 117, 115701 (2016) <https://doi.org/10.1103/PhysRevLett.117.115701>`_.

J.J. Shepherd, T.M. Henderson, G.E. Scuseria. Using full configuration interaction quantum Monte Carlo in a seniority zero space to investigate the correlation energy equivalence of pair coupled cluster doubles and doubly occupied configuration interaction, `J. Chem. Phys. 144, 094112 (2016) <http://dx.doi.org/10.1063/1.4942770>`_.

W.A. Vigor, J.S. Spencer, M.J. Bearpark, A.J.W. Thom. Understanding and improving the efficiency of full configuration interaction quantum Monte Carlo, `J. Chem. Phys. 144, 094110 (2016) <http://dx.doi.org/10.1063/1.4943113>`_.

J.S. Spencer, A.J.W. Thom. Developments in stochastic coupled cluster theory: The initiator approximation and application to the uniform electron gas, `J. Chem. Phys. 144, 084108 (2016) <http://dx.doi.org/10.1063/1.4942173>`_.

R.S.T. Franklin, J.S. Spencer, A. Zoccante, A.J.W. Thom. Linked coupled cluster Monte Carlo, `J Chem. Phys. 144, 044111 (2016) <http://dx.doi.org/10.1063/1.4940317>`_.

J.S. Spencer, N.S. Blunt, W.A. Vigor, F.D. Malone, W.M.C. Foulkes, J.J. Shepherd, A.J.W. Thom. Open-Source Development Experiences in Scientific Software: The HANDE Quantum Monte Carlo Project, `J. Open Research Software 3(1), 9 (2015) <http://dx.doi.org/10.5334/jors.bw>`_.

W.A. Vigor, J.S. Spencer, M.J. Bearpark, A.J.W. Thom. Minimising biases in full configuration interaction quantum Monte Carlo, `J. Chem. Phys. 142, 104101 (2015) <http://dx.doi.org/10.1063/1.4913644>`_.

F.D. Malone, N.S. Blunt, J.J. Shepherd, D.K.K. Lee, J.S. Spencer, W.M.C. Foulkes. Interaction picture density matrix quantum Monte Carlo, `J. Chem. Phys. 143, 044116 (2015) <http://dx.doi.org/10.1063/1.4927434>`_.

J.J. Shepherd, G.E. Scuseria, J.S. Spencer. Sign problem in full configuration interaction quantum Monte Carlo: Linear and sublinear representation regimes for the exact wave function, `Phys. Rev. B 90, 155130 (2014) <http://dx.doi.org/10.1103/PhysRevB.90.155130>`_.

N.S. Blunt, T.W. Rogers, J.S. Spencer, W.M.C. Foulkes. Density-matrix quantum Monte Carlo method, `Phys. Rev. B, 89, 245124 (2014) <http://dx.doi.org/10.1103/PhysRevB.89.245124>`_.

J.S. Spencer, N.S. Blunt, W.M.C. Foulkes. The sign problem and population dynamics in the full configuration interaction quantum Monte Carlo method, `J. Chem. Phys. 136, 054110 (2012) <http://dx.doi.org/10.1063/1.3681396>`_.

Funding
-------

Our team receives funding from EPSRC, the Royal Society, the Royal Commission for
the Exhibition of 1851, ARCHER Leadership Grant, EPSRC Centre for Doctoral Training in Computational
Methods for Materials Science, Sims Fund, St John's college Cambridge.
We are also grateful for a research environment provided by the Thomas Young Centre.

References
----------

.. [1] Fermion Monte Carlo without fixed nodes a game of life, death, and annihilation in Slater determinant space, G.H. Booth, A.J.W. Thom, A. Alavi, J. Chem. Phys., 131 054106 (2009).
.. [2] Stochastic Coupled Cluster Theory, A.J.W. Thom, Phys. Rev. Lett. 105, 263004 (2010).
.. [3] Survival of the Fittest: Accelerating Convergence in Full Configuration-Interaction Quantum Monte Carlo , D. Cleland, G.H. Booth, A. Alavi, J. Chem. Phys., 132, 041103 (2010).
.. [4] Semistochastic Projector Monte Carlo Method.  F. Petruzielo, A. Holmes, H. Changlani, M. Nightingale, C. Umrigar, Phys. Rev. Lett. 109, 230201 (2012).
.. [5] Density-matrix quantum Monte Carlo method.  N.S. Blunt, T. W. Rogers, J. S. Spencer, and W. M. C. Foulkes,  Phys. Rev. B, 89, 245124 (2014).
