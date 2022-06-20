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
density matrix quantum Monte Carlo method [5]_ and unitary coupled cluster Monte Carlo
algorithms [6]_.
HANDE can treat a variety of quantum systems, including molecular systems (via
integrals obtained from a quantum chemistry package) and the uniform electron
gas as well as the Hubbard and Heisenberg models.

HANDE version 1.6 can be obtained from https://github.com/hande-qmc/hande.

There is a HANDE users mailing list where you can ask questions and get announcements of releases. See https://groups.google.com/g/hande-user where you can view any posts and sign up.

For any questions on using and/or developing HANDE, please contact the mailing list or Alex:

| Alex Thom, ajwt3@cam.ac.uk

HANDE development team
----------------------

Code, theory, applications, etc:

* Alex Thom (University of Cambridge)
* Nick Blunt (University of Cambridge)
* Fionn Malone (Lawrence Livermore National Laboratory)
* Matthew Foulkes (Imperial College London)
* Charlie Scott (University of Cambridge)
* Verena Neufeld (University of Cambridge, now Columbia University)
* James Shepherd (University of Iowa)
* Roberto Di Remigio (University of Tromsø and Virginia Tech)
* Maria-Andreea Filip (University of Cambridge)
* Hayley Petras (University of Iowa)
* Christopher Bradley (Imperial College London)
* Tiger Zhang (University of Cambridge)
* William Van Benschoten (University of Iowa)
* Brian Zhao (University of Cambridge)

Past contributors:

* James Spencer (Former Lead Developer, Imperial College London)
* Seonghoon Choi (was at University of Cambridge, now EPFL Lausanne)
* Thomas Rogers (Imperial College London)
* Will Handley (University of Cambridge)
* Joseph Weston (Imperial College London)
* William Vigor (Imperial College London)
* Ruth Franklin (University of Cambridge)

For an overview of HANDE see

J.S. Spencer, N.S. Blunt, S. Choi, J. Etrych, M.-A. Filip, W.M.C. Foulkes, R.S.T. Franklin, W.J. Handley, F.D. Malone, V.A. Neufeld, R. Di Remigio, T.W. Rogers, C.J.C. Scott, J.J. Shepherd, J. Weston, W.A. Vigor, R. Xu, A.J.W. Thom. The HANDE-QMC project: open-source stochastic quantum chemistry from the ground state up, `J. Chem. Theory Comput. 15, 3, 1728-1742 (2019) <https://pubs.acs.org/doi/10.1021/acs.jctc.8b01217>`_.


Publications
------------
T.M. Mihm, W.Z. Van Benschoten, J.J. Shepherd, `J. Chem. Phys. 154, 024113 (2021) <https://doi.org/10.1063/5.0033408>`_.

M-A. Filip, A.J.W. Thom. A stochastic approach to unitary coupled cluster, `J. Chem. Phys. 153, 214106 (2020) <https://doi.org/10.1063/5.0026141>`_.

V.A. Neufeld, A.J.W. Thom. Accelerating Convergence in Fock Space Quantum Monte Carlo Methods, `J. Chem. Theory Comput. 16, 3, 1503-1510 (2020) <https://doi.org/10.1021/acs.jctc.9b01023>`_.

M-A. Filip, C.J.C. Scott, A.J.W. Thom. Multireference Stochastic Coupled Cluster, `J. Chem. Theory Comput. 15, 12, 6625-6635 (2019) <https://doi.org/10.1021/acs.jctc.9b00741>`_.

H.R. Petras, D.S. Graham, S.K. Ramadugu, J.D. Goodpaster, J.J. Shepherd. Fully Quantum Embedding with Density Functional Theory for Full Configuration Quantum Monte Carlo, `J. Chem. Theory Comput. 15, 10, 5332-5342 (2019) <https://doi.org/10.1021/acs.jctc.9b00571>`_.

V.A. Neufeld, A.J.W. Thom. Exciting determinants in Quantum Monte Carlo: Loading the dice with fast, low memory weights, `J. Chem. Theory Comput. 15, 1, 127-140 (2019) <https://doi.org/10.1021/acs.jctc.8b00844>`_

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

Our team has received funding and resources from EPSRC, the Royal Society, the Royal Commission for
the Exhibition of 1851, ARCHER Leadership Grant, EPSRC Centre for Doctoral Training in Computational
Methods for Materials Science, Sims Fund, St John's College Cambridge, Magdalene College Cambridge, 
Cambridge Trust, the Thomas Young Centre, the Walters-Kundert Next Generation Fellowship Fund, the 
Department of Energy.

References
----------

.. [1] Fermion Monte Carlo without fixed nodes a game of life, death, and annihilation in Slater determinant space, G.H. Booth, A.J.W. Thom, A. Alavi, J. Chem. Phys., 131 054106 (2009).
.. [2] Stochastic Coupled Cluster Theory, A.J.W. Thom, Phys. Rev. Lett. 105, 263004 (2010).
.. [3] Survival of the Fittest: Accelerating Convergence in Full Configuration-Interaction Quantum Monte Carlo , D. Cleland, G.H. Booth, A. Alavi, J. Chem. Phys., 132, 041103 (2010).
.. [4] Semistochastic Projector Monte Carlo Method.  F. Petruzielo, A. Holmes, H. Changlani, M. Nightingale, C. Umrigar, Phys. Rev. Lett. 109, 230201 (2012).
.. [5] Density-matrix quantum Monte Carlo method.  N.S. Blunt, T. W. Rogers, J. S. Spencer, and W. M. C. Foulkes,  Phys. Rev. B, 89, 245124 (2014).
.. [6] A stochastic approach to unitary coupled cluster. M-A. Filip, A.J.W. Thom, J. Chem. Phys. 153, 214106 (2020).

