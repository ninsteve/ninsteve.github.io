---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
--- 

## Software Packages ##

* **MORLAB (Model Order Reduction LABoratory)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a><br/>
  This toolbox is a collection of MATLAB routines for model order reduction of 
  dynamical systems based on the solution of matrix equations.
  The implementation is based on spectral projection methods, e.g., methods 
  based on the matrix sign function and the matrix disk function.
  For details and references see the official <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/morlab">project website</a>, 
  the <a target="_blank" 
  href="https://morwiki.mpi-magdeburg.mpg.de/morwiki/index.php/MORLAB">MORwiki 
  entry</a> and the latest <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.842658">Zenodo upload</a>.

* **SOMDDPA (Second-Order Modally-Damped Dominant Pole Algorithm)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a><br/>
  For model order reduction via modal truncation, dominant poles have been 
  proven to be an efficient and accurate approach.
  In case of modally-damped second-order systems, it is possible to extend the 
  idea of dominant poles in a structure-preserving fashion to the mechanical 
  system case.
  This package contains a structure-preserving implementation in MATLAB and 
  Octave of the dominant pole algorithm for modally-damped second-order systems.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553901">Zenodo</a>.

* **SOLBT (Limited Balanced Truncation for Large-Scale Sparse Second-Order 
  Systems)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://www.gnu.org/licenses/gpl-3.0">
  <img src="https://img.shields.io/badge/License-GPLv3+-blue.svg"
  alt="License: GPL v3" class="badge"></a><br/>
  In practical applications, only local approximations of system's behavior in 
  frequency or time domain are needed.
  This package extends the idea of frequency- and time-limited balanced 
  truncation to large-scale sparse mechanical systems of second-order type with 
  an implementation in MATLAB and Octave.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553925">Zenodo</a>.
  Check out the corresponding <a target="_blank" 
  href="https://doi.org/10.1016/j.laa.2020.06.024">paper</a> for the theoretical 
  background.

---

## Contributions to other Projects ##

* **M-M.E.S.S. (Matrix Equation Sparse Solvers Library)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://www.gnu.org/licenses/gpl-2.0">
  <img src="https://img.shields.io/badge/License-GPL%20v2+-orange.svg"
  alt="License: GPL v2+" class="badge"></a><br/>
  Starting in version 1.0.1, I made continuously updates in the MATLAB version 
  on the MATLAB version of the <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/mess">M.E.S.S. library</a>
  involving among other an implementation of the Riccati iteration, the RADI
  method and several bug fixes.
  For more details see the <a target="_blank"
  href="https://gitlab.mpi-magdeburg.mpg.de/mess/mmess-releases/-/blob/master/CONTRIBUTORS.md">contributors file</a>.

---

## Codes and Results for Reported Numerical Experiments ##

Reproducability and reusability of numerical experiments is an important topic 
in computer-based science.
The following list contains contains public uploads of scripts and numerical 
results from numerical experiments reported in corresponding papers:

* <a target="_black" href="https://zenodo.org/record/4507759">MATLAB and Python 
  scripts and results</a> for the experiments reported in
  > P. Benner, J. Heiland, and <strong>S. W. R. Werner</strong>. <a
  > target="blank_" href="https://arxiv.org/abs/2103.01608">Robust 
  > output-feedback stabilization for incompressible flows using low-dimensional 
  > H-infinity-controllers</a>. e-print 2103.01608, arXiv, 2021. math.OC.
  > URL: https://arxiv.org/abs/2103.01608

* <a target="_black" href="https://zenodo.org/record/3865495">MATLAB scripts and 
  routines</a> for the experiments reported in
  > P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
  > href="https://arxiv.org/abs/2002.12682">MORLAB &ndash; The Model Order
  > Reduction LABoratory</a>. e-print 2002.12682, arXiv, 2020. cs.MS.
  > URL: https://arxiv.org/abs/2002.12682

* <a target="_black" href="https://zenodo.org/record/2563874">MATLAB scripts and 
  routines</a>, as well as <a target="_black" 
  href="https://zenodo.org/record/2564050">numerical results</a> for the 
  experiments reported in
  > J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
  > target="blank_" href="https://doi.org/10.1515/auto-2019-0027">A comparison
  > of second-order model order reduction methods for an artificial
  > fishtail</a>. <i>at-Automatisierungstechnik</i>, 67(8):648&ndash;667, 2019.
  > doi:10.1515/auto-2019-0027
