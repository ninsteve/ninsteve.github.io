---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
--- 

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

## Software Packages ##

* **MORLAB (Model Order Reduction LABoratory)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://www.gnu.org/licenses/agpl-3.0">
  <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
  alt="License: AGPLv3+" class="badge"></a>
  &nbsp;*Latest Version: 5.0*<br/>
  This toolbox is a collection of MATLAB routines for model order reduction of 
  dynamical systems based on the solution of matrix equations.
  The implementation is based on spectral projection methods, e.g., methods 
  based on the matrix sign function and the matrix disk function.
  For details and references see the official <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/morlab">project website</a>, 
  the <a target="_blank" 
  href="https://morwiki.mpi-magdeburg.mpg.de/morwiki/index.php/MORLAB">MORwiki 
  entry</a> and the latest <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.842658">Zenodo upload</a>.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.842658">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationMORLAB-pop" class="btn btn--inverse">Citation</button>

* **SOMDDPA (Second-Order Modally-Damped Dominant Pole Algorithm)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a>
  &nbsp;*Latest Version: 2.0*<br/>
  For model order reduction via modal truncation, dominant poles have been 
  proven to be an efficient and accurate approach.
  In case of modally-damped second-order systems, it is possible to extend the 
  idea of dominant poles in a structure-preserving fashion to the mechanical 
  system case.
  This package contains a structure-preserving implementation in MATLAB and 
  Octave of the dominant pole algorithm for modally-damped second-order systems.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553901">Zenodo</a> and checkout my
  <a target="_blank" href="https://doi.org/10.25673/38617">dissertation</a>
  for the theoretical background.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.2553901">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.25673/38617">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationSOMDDPA-pop" class="btn btn--inverse">Citation</button>

* **SOLBT (Limited Balanced Truncation for Large-Scale Sparse Second-Order 
  Systems)**<br/>
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a>
  &nbsp;*Latest Version: 3.0*<br/>
  In practical applications, only local approximations of system's behavior in 
  frequency or time domain are needed.
  This package extends the idea of frequency- and time-limited balanced 
  truncation to large-scale sparse mechanical systems of second-order type with 
  an implementation in MATLAB and Octave.
  Find the latest upload on <a target="_blank" 
  href="https://doi.org/10.5281/zenodo.2553925">Zenodo</a>.
  Check out the corresponding <a target="_blank" 
  href="https://doi.org/10.1016/j.laa.2020.06.024">paper</a> for the
  theoretical background.<br/>
  <a target="blank_" href="https://doi.org/10.5281/zenodo.2553925">
  <button class="btn btn--inverse">Download</button></a>
  <a target="blank_" href="https://doi.org/10.1016/j.laa.2020.06.024">
  <button class="btn btn--inverse">Documentation</button></a>
  <button id="citationSOLBT-pop" class="btn btn--inverse">Citation</button>

---

## Contributions to other Projects ##

* **M-M.E.S.S. (Matrix Equation Sparse Solvers Library)**:
  <a target ="_blank"
  href="https://en.wikipedia.org/wiki/Open-source_software">
  <img src="../images/open_source_symbol.png" alt="Open Source Software"
  class="opensource"></a>
  <a href="https://opensource.org/licenses/BSD-2-Clause">
  <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
  alt="License: BSD 2-Clause" class="badge"></a><br/>
  From version 1.0.1 up to version 2.2, I made continuously updates in the 
  MATLAB version of the <a target="_blank" 
  href="https://www.mpi-magdeburg.mpg.de/projects/mess">M.E.S.S. library</a>
  involving among other an implementation of the Riccati iteration, the RADI
  method and several bug fixes.
  For more details on my contributions see the <a target="_blank"
  href="https://gitlab.mpi-magdeburg.mpg.de/mess/mmess-releases/-/blob/master/CONTRIBUTORS.md">contributors file</a> and checkout the latest version on
  <a target="_blank" href="https://doi.org/10.5281/zenodo.632897">Zenodo</a>.

---

## <a name="codepackages"></a>Supplementary code packages and data ##

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5793356">Code, data and results for
    numerical experiments in &ldquo;A unifying framework for tangential
    interpolation of structured bilinear control systems&rdquo;
    (version 1.0)</a>,
    June 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5793356">10.5281/zenodo.5793356</a><br />
    <button id="supWer22c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2206.01657"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6403121">Code, data and results for
    numerical experiments in &ldquo;Multi-fidelity robust controller design
    with gradient sampling&rdquo;
    (version 1.0)</a>,
    May 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6403121">10.5281/zenodo.6403121</a><br />
    <button id="supWer22b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2205.15050"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"
    alt="License: GPLv3" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.6308400">Code, data and results for
    numerical experiments in &ldquo;A low-rank solution method for Riccati
    equations with indefinite quadratic terms&rdquo;
    (version 2.0)</a>,
    March 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.6308400">10.5281/zenodo.6308400</a><br />
    <button id="supWer22a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5902997">Code, data and results for
    numerical experiments in &ldquo;On the sample complexity of stabilizing
    linear dynamical systems from data&rdquo;
    (version 1.0)</a>,
    February 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5902997">10.5281/zenodo.5902997</a><br />
    <button id="supWer22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2203.00474"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  Q. Aumann and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5836047">Code, data and results for
    numerical experiments in &ldquo;Structured model order reduction for
    vibro-acoustic problems using interpolation and balancing methods&rdquo;
    (version 1.0)</a>,
    January 2022. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5836047">10.5281/zenodo.5836047</a><br />
    <button id="supAumW22-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2201.06518"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5155993">Code, data and results for
    numerical experiments in &ldquo;A low-rank solution method for riccati
    equations with indefinite quadratic terms&rdquo; (version 1.0)</a>,
    November 2021. doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.5155993">10.5281/zenodo.5155993</a><br />
    <button id="supWer21c-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s11075-022-01331-w"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5539944">Code, data and results for
    numerical experiments in &ldquo;Structured vector fitting framework for
    mechanical systems&rdquo; (version 1.0)</a>, October 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.5539944">10.5281/zenodo.5539944</a><br />
    <button id="supWer21b-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.48550/arXiv.2110.09220"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>

1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.5532539">Code, data and results for
    numerical experiments in &ldquo;Robust output-feedback stabilization for
    incompressible flows using low-dimensional
    \\(\mathcal{H}_{\infty}\\)-controllers&rdquo; (version 2.0)</a>,
    October 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.5532539">10.5281/zenodo.5532539</a><br />
    <button id="supHeiW21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>
    
1.  R. Jendersie and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4745518">Results of numerical
    experiments in &ldquo;A comparison
    of numerical methods for model reduction of dense discrete-time
    systems&rdquo; (version 1.0)</a>, May 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4745518">10.5281/zenodo.4745518</a><br />
    <button id="supJenW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2021-0035"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4650422">Results of numerical
    experiments in &ldquo;Structure-Preserving Model Reduction for Mechanical
    Systems&rdquo; (version 1.0)</a>, April 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4650422">10.5281/zenodo.4650422</a><br />
    <button id="supWer21a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.25673/38617"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4650402">Code and data for numerical
    experiments in &ldquo;Structure-Preserving Model Reduction for Mechanical
    Systems&rdquo; (version 1.0)</a>, April 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4650402">10.5281/zenodo.4650402</a><br />
    <button id="supWer21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.25673/38617"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/BSD-2-Clause">
    <img src="https://img.shields.io/badge/License-BSD%202--Clause-orange.svg"
    alt="License: BSD 2-Clause" class="badge"></a>
    
1.  J. Heiland and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.4507759">Code, data and results for
    numerical experiments in &ldquo;Robust output-feedback stabilization for
    incompressible flows using low-dimensional
    \\(\mathcal{H}_{\infty}\\)-controllers&rdquo; (version 1.0)</a>,
    March 2021. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.4507759">10.5281/zenodo.4507759</a><br />
    <button id="supHeiW21-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/s10589-022-00359-x"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green.svg"
    alt="License: MIT" class="badge"></a>
    
1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3865495">Parametric and two-step model
    reduction using M-M.E.S.S. and MORLAB (version 1.1)</a>, June 2020. doi:<a
    target="blank_" href="https://doi.org/10.5281/zenodo.3865495">10.5281/zenodo.3865495</a><br />
    <button id="supSaaW20a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  J. Saak and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3678213">Parametric and two-step model
    reduction using M-M.E.S.S. and MORLAB (version 1.0)</a>, February 2020.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.3678213">10.5281/zenodo.3678213</a><br />
    <button id="supSaaW20-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1007/978-3-030-72983-7_19"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-AGPLv3+-blue.svg"
    alt="License: AGPLv3+" class="badge"></a>
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.5281/zenodo.2564050">Reduction
    results for an artificial fish tail (version 19-02-14)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2564050">10.5281/zenodo.2564050</a><br />
    <button id="supSaaSW19a-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2019-0027"><button
    class="btn btn--inverse">Paper</button></a>
    <a target="_blank" href="https://en.wikipedia.org/wiki/Open_access">
    <img src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess"></a>
    <a href="https://creativecommons.org/licenses/by/4.0">
    <img src="https://licensebuttons.net/l/by/3.0/88x31.png"
    alt="License: CC BY 4.0" class="badge"></a>
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.5281/zenodo.2563874">Second order
    reduction comparison for the fishtail model (version 1.0)</a>, February 2019.
    doi:<a target="blank_" href="https://doi.org/10.5281/zenodo.2563874">10.5281/zenodo.2563874</a><br />
    <button id="supSaaSW19-pop" class="btn btn--inverse">BibTeX</button>
    <a target="blank_" href="https://doi.org/10.1515/auto-2019-0027"><button
    class="btn btn--inverse">Paper</button></a>
    <a target ="_blank"
    href="https://en.wikipedia.org/wiki/Open-source_software">
    <img src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource"></a>
    <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/badge/License-GPLv3-blue.svg"
    alt="License: GPLv3" class="badge"></a>

<!-- Javascripts for Buttons and BibTeX content. -->

<div id="includedBibTeX"></div>
<div id="includedCitation"></div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.css"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
<script> 
  $(function(){
    $("#includedBibTeX").load("{{ base_path }}/files/software/bibtex.html");
    $("#includedCitation").load("{{ base_path }}/files/software/citation.html");
  });
</script>
