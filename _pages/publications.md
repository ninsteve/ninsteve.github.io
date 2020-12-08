---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#submitted">Submitted Articles (4)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#journal">Journal Articles (3)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#proceedings">Proceedings (9)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#software">Software (7)</a>
</p>
<p style="margin-top:0.5em; margin-bottom:0.5em">
  <a href="#theses">Theses (2)</a>
</p>

You can also find my publications on my
<a target="blank_" href="{{ author.googlescholar }}">Google Scholar</a>
and <a target="blank_" href="{{ author.orcid }}">ORCID</a> profiles.

<style>
  p {
    word-wrap: break-word;
    overflow-wrap: break-word;
  }
</style>

---

## <a name="submitted"></a>Submitted Articles ##

1.  R. S. Beddig, P. Benner, I. Dorschky, T. Reis, P. Schwerdtner, M. Voigt, and
    <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://arxiv.org/abs/2010.06331">Structure-preserving model reduction
    for dissipative mechanical systems</a>. e-print 2010.06331, arXiv, 2020.
    math.OC. URL: https://arxiv.org/abs/2010.06331  
    <button id="morBedBDetal20-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://arxiv.org/abs/2007.11269">Structure-preserving
    interpolation for model reduction of parametric bilinear systems</a>.
    e-print 2007.11269, arXiv, 2020. math.NA.
    URL: https://arxiv.org/abs/2007.11269  
    <button id="morBenGW20a-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner, S. Gugercin, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://arxiv.org/abs/2005.00795">Structure-preserving
    interpolation of bilinear control systems</a>. e-print 2005.00795,
    arXiv, 2020. math.NA. URL: https://arxiv.org/abs/2005.00795  
    <button id="morBenGW20-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://arxiv.org/abs/2002.12682">MORLAB &ndash; The Model Order
    Reduction LABoratory</a>. e-print 2002.12682, arXiv, 2020. cs.MS.
    URL: https://arxiv.org/abs/2002.12682  
    <button id="morBenW20c-pop" class="btn btn--inverse">BibTeX</button>

---

## <a name="journal"></a>Journal Articles ##

1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1016/j.laa.2020.06.024">Frequency- and time-limited
    balanced truncation for large-scale second-order systems</a>. <i>Linear
    Algebra Appl.</i>, 2020. article in press. doi:10.1016/j.laa.2020.06.024  
    <button id="morBenW20b-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/s10444-020-09750-w">Hankel-norm approximation
    of large-scale descriptor systems</a>. <i>Adv. Comput. Math.</i>,
    46(3):40, 2020. doi:10.1007/s10444-020-09750-w  
    <button id="morBenW20d-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess">
    
1.  J. Saak, D. Siebelts, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1515/auto-2019-0027">A comparison
    of second-order model order reduction methods for an artificial
    fishtail</a>. <i>at-Automatisierungstechnik</i>, 67(8):648&ndash;667, 2019.
    doi:10.1515/auto-2019-0027  
    <button id="morSaaSW19-pop" class="btn btn--inverse">BibTeX</button>

---

## <a name="proceedings"></a>Proceedings ##
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1007/978-3-030-52200-1_43">MORLAB &ndash; A model
    order reduction framework in MATLAB and Octave</a>. In A. M. Bigatti, J.
    Carette, J. H. Davenport, M. Joswig, and T. de Wolff, editors,
    <i>Mathematical Software &ndash; ICMS 2020</i>, volume 12097 of 
    <i>Lecture Notes in Comput. Sci.</i>, pages 432&ndash;441.
    Springer International Publishing, Cham, 2020.
    doi:10.1007/978-3-030-52200-1_43  
    <button id="morBenW20e-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2019-fa-1.30">
    Frequenz- und zeitbeschränktes balanciertes
    Abschneiden für Systeme zweiter Ordnung</a>. In T. Meurer and F.
    Woittennek, editors, <i>Tagungsband GMA-FA 1.30 'Modellbildung,
    Identifikation und Simulation in der Automatisierungstechnik' und
    GMA-FA 1.40 'Systemtheorie und Regelungstechnik', Workshops in Anif,
    Salzburg, 23.-27.09.2019, pages 460&ndash;474, 2019.
    URL: http://www.control.tf.uni-kiel.de/files/gma/2019/Tagungsband2019.pdf  
    <button id="morBenW19d-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2019-fa-1.30">
    MORLAB – Model Order Reduction LABoratory</a>. In T. Meurer and F.
    Woittennek, editors, <i>Tagungsband GMA-FA 1.30 'Modellbildung,
    Identifikation und Simulation in der Automatisierungstechnik' und
    GMA-FA 1.40 'Systemtheorie und Regelungstechnik', Workshops in Anif,
    Salzburg, 23.-27.09.2019, pages 337&ndash;342, 2019.
    URL: http://www.control.tf.uni-kiel.de/files/gma/2019/Tagungsband2019.pdf  
    <button id="morBenW19c-pop" class="btn btn--inverse">BibTeX</button>
    
1.  R. S. Beddig, P. Benner, I. Dorschky, T. Reis, P. Schwerdtner, M. Voigt, and
    <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201900224">Model reduction for
    second-order dynamical systems revisited</a>. <i>Proc. Appl. Math.
    Mech.</i>, 19(1):e201900224, 2019. doi:10.1002/pamm.201900224  
    <button id="morBedBDetal19-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess">
    
1.  P. Benner, J. Heiland, and <strong>S. W. R. Werner</strong>. <a
    target="blank_" href="https://doi.org/10.1016/j.ifacol.2019.08.005">Robust
    controller versus numerical model uncertainties for stabilization of
    Navier-Stokes equations</a>. <i>IFACPapersOnLine</i>,
    52(2):25&ndash;29, 2019. 3rd IFAC/IEEE CSS Workshop on Control of Systems
    Governed by Partial Differential Equation CPDE 2019.
    doi:10.1016/j.ifacol.2019.08.005  
    <button id="BenHW19-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201800083">Balancing related model
    reduction with the MORLAB toolbox</a>. <i>Proc. Appl. Math. Mech.</i>,
    18(1):e201800083, 2018. doi:10.1002/pamm.201800083  
    <button id="morBenW18a-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1016/j.ifacol.2018.03.092">Model reduction of
    descriptor systems with the MORLAB toolbox</a>. <i>IFAC-PapersOnLine 9th
    Vienna International Conference on Mathematical Modelling MATHMOD 2018,
    Vienna, Austria, 21&ndash;23 February 2018</i>, 51(2):547&ndash;552, 2018.
    doi:10.1016/j.ifacol.2018.03.092  
    <button id="morBenW18-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_access_symbol.png" alt="Open Access Published"
    class="openaccess">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://www.control.tf.uni-kiel.de/en/gma-fa-1.40/archiv-1/workshop-2017-fa-1.30">
    MORLAB - Modellreduktion in MATLAB</a>. In T. Meurer and F. Woittennek,
    editors, <i>Tagungsband GMA-FA 1.30 'Modellierung, Identifikation und
    Simulation in der Automatisierungstechnik' und GMA-FA 1.40 'Theoretische
    Verfahren der Regelungstechnik', Workshop in Anif, Salzburg,
    18.-22.09.2017</i>, pages 508&ndash;517, 2017. URL:
    http://http://www.control.tf.uni-kiel.de/files/gma/2017/Tagungsband2017.pdf  
    <button id="morBenW17b-pop" class="btn btn--inverse">BibTeX</button>
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.1002/pamm.201710379">On the transformation formulas
    of the Hankel-norm approximation</a>. <i>Proc. Appl. Math. Mech.</i>,
    17(1):823&ndash;824, 2017. doi:10.1002/pamm.201710379  
    <button id="morBenW17-pop" class="btn btn--inverse">BibTeX</button>

---

## <a name="software"></a>Software ##
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3332706">SOMDDPA &ndash; Second-Order
    Modally-Damped Dominant Pole Algorithm (version 1.1)</a>, 2020.
    doi:10.5281/zenodo.3332706  
    <button id="morBenW20a-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3331592">Limited balanced truncation
    for large-scale sparse second-order systems (version 2.0)</a>, 2020.
    doi:10.5281/zenodo.3331592  
    <button id="morBenW20-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.3332716">MORLAB &ndash; Model Order
    Reduction LABoratory (version 5.0)</a>, 2019. see also:
    http://www.mpi-magdeburg.mpg.de/projects/morlab.
    doi:10.5281/zenodo.3332716  
    <button id="morBenW19b-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.2553926">Limited balanced truncation
    for large-scale sparse second-order systems (version 1.0)</a>, 2019.
    doi:10.5281/zenodo.2553926  
    <button id="morBenW19a-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.2553902">SOMDDPA &ndash; Second-Order
    Modally Damped Dominant Pole Algorithm (version 1.0)</a>, 2019.
    doi:10.5281/zenodo.2553902  
    <button id="morBenW19-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.1574083">MORLAB – Model Order Reduction
    LABoratory (version 4.0)</a>, 2018.
    see also: http://www.mpi-magdeburg.mpg.de/projects/morlab.
    doi:10.5281/zenodo.1574083  
    <button id="morBenW18b-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    [![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
    
1.  P. Benner and <strong>S. W. R. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.5281/zenodo.842659">MORLAB-3.0 – model order
    reduction laboratory</a>, 2017. see also:
    http://www.mpi-magdeburg.mpg.de/projects/morlab. doi:10.5281/zenodo.842659  
    <button id="morBenW17a-pop" class="btn btn--inverse">BibTeX</button>
    <image src="../images/open_source_symbol.png" alt="Open Source Software"
    class="opensource">
    <img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg"
    alt="License: AGPL v3" class="opensource">

---

## <a name="theses"></a>Theses ##
1.  <strong>S. Werner</strong>. <a target="blank_"
    href="https://doi.org/10.25673/4507">Hankel-norm approximation of descriptor
    systems</a>. Master's thesis, Otto-von-Guericke-Universität, Magdeburg,
    Germany, 2016. doi:10.25673/<wbr>4507  
    <button id="morWer16-pop" class="btn btn--inverse">BibTeX</button>
    
1.  <strong>S. Werner</strong>. Numerische Berechnung der Eigenwerte großer
    Hamiltonisch-positiver Matrizen. Bachelor's thesis,
    Otto-von-Guericke-Universität, Magdeburg, Germany, 2014.  
    <button id="Wer14-pop" class="btn btn--inverse">BibTeX</button>


<!-- Javascripts for Buttons and BibTeX content. -->

<div id="includedBibTeX"></div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/magnific-popup.css"/>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.1.0/jquery.magnific-popup.min.js"></script>
<script> 
  $(function(){
    $("#includedBibTeX").load("{{ base_path }}/files/publications/bibtex.html"); 
  });
</script>
