Trapped Charged Data Analysis: Task View
================
Sebastian Kreutzer
(last update: 2018-12-31)





<!-- README.md was auto-generated by README.Rmd. Please DO NOT edit by hand!-->

# About

In analogy of the [CRAN task view
lists](https://cran.rstudio.com/web/views/), this list is a collection
of freely available software for the broader framework trapped charged
dating (e.g., luminescence and ESR data analysis). Software tools are
ordered alphabetically within the task sections. The collection is not
limited to R packages.

**Your software is missing?** Please let me know via
<https://github.com/RLumSK/luminescence-tv/issues>

# Mission tasks

### Age calculation

  - **DRAC** <img width=53px src='images/web_service.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Dose rate
    and luminescence age calculator (v1.2 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <http://www.aber.ac.uk/en/dges/research/quaternary/luminescence-research-laboratory/dose-rate-calculator/>
    <br />*<small>Durcan, J.A., King, G.E., Duller, G.A.T., 2015. DRAC:
    Dose Rate and Age Calculator for trapped charge dating. Quaternary
    Geochronology 28, 54–61. doi:
    <https://doi.org/10.1016/j.quageo.2015.03.012></small>*

### Chronological modelling

  - **ArchaeoChron** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Provides a
    list of functions for the Bayesian modeling of archaeological
    chronologies. The Bayesian models are implemented in ‘JAGS’ (‘JAGS’
    stands for Just Another Gibbs Sampler. It is a program for the
    analysis of Bayesian hierarchical models using Markov Chain Monte
    Carlo (MCMC) simulation. See <http://mcmc-jags.sourceforge.net/> and
    “JAGS Version 4.3.0 user manual”, Martin Plummer (2017)
    <https://sourceforge.net/projects/mcmc-jags/files/Manuals/>.). The
    inputs are measurements with their associated standard deviations
    and the study period. The output is the MCMC sample of the posterior
    distribution of the event date with or without radiocarbon
    calibration. (v0.1 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=ArchaeoChron> <br />
  - **ArchaeoPhases** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Provides a
    list of functions for the statistical analysis of archaeological
    dates and groups of dates. It is based on the post-processing of the
    Markov Chains whose stationary distribution is the posterior
    distribution of a series of dates. Such output can be simulated by
    different applications as for instance ‘ChronoModel’ (see
    <http://www.chronomodel.fr>), ‘Oxcal’ (see
    <https://c14.arch.ox.ac.uk/oxcal.html>) or ‘BCal’ (see
    <http://bcal.shef.ac.uk/>). The only requirement is to have a csv
    file containing a sample from the posterior distribution. (v1.3 |
    Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=ArchaeoPhases> <br />
  - **BayLum** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Bayesian
    analysis of luminescence data and C-14 age estimates. Bayesian
    models are based on the following publications: Combes, B. &
    Philippe, A. (2017) <doi:10.1016/j.quageo.2017.02.003> and Combes et
    al (2015) <doi:10.1016/j.quageo.2015.04.001>. This includes, amongst
    others, data import, export, application of age models and
    palaeodose model. (v0.1.3 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=BayLum> <br />*<small>Philippe,
    A., Guérin, G., Kreutzer, S., 2019. BayLum - An R package for
    Bayesian analysis of OSL ages: An introduction. Quaternary
    Geochronology 49, 16–24. doi:
    <https://doi.org/10.1016/j.quageo.2018.05.009></small>*
  - **ChronoModel** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' />
    <br />Chronological Modelling of Archaeological Data using Bayesian
    Statistics with an advanced graphical user interface (v1.5 |
    Windows, macOS) <br /><img width=20px src='images/url_valid.svg' />
    <https://chronomodel.com> <br />
  - **RChronoModel** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Provides a
    list of functions for the statistical analysis and the
    post-processing of the Markov Chains simulated by ChronoModel (see
    <http://www.chronomodel.fr> for more information). ChronoModel is a
    friendly software to construct a chronological model in a Bayesian
    framework. Its output is a sampled Markov chain from the posterior
    distribution of dates component the chronology. The functions can
    also be applied to the analyse of mcmc output generated by Oxcal
    software. (v0.4 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=RChronoModel> <br />

### Dose rate modelling

  - **DosiVox** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A Geant
    4-based software for dosimetry simulations relevant to luminescence
    and ESR dating techniques (v2018-12-03 | Linux)
    <br /><img width=20px src='images/url_valid.svg' />
    <http://www.iramat-crp2a.cnrs.fr/spip/spip.php?article144&lang=fr>
    <br />*<small>Martin, L., Incerti, S., Mercier, N., 2015. DosiVox:
    Implementing Geant 4-based software for dosimetry simulations
    relevant to luminescence and ESR dating techniques. Ancient TL 33,
    1–10.</small>*
  - **DosiVox2D** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_unpublished.svg' /> <br />A Geant
    4-based software for dosimetry simulations relevant to luminescence
    and ESR dating techniques; simplified version in comparison to
    DosiVox (v2018-12-03 | Linux)
    <br /><img width=20px src='images/url_valid.svg' />
    <http://www.iramat-crp2a.cnrs.fr/spip/spip.php?article144&lang=fr>
    <br />
  - **RCarb** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Translation
    of the ‘MATLAB’ program ‘Carb’ (Nathan and Mauz 2008
    <doi:10.1016/j.radmeas.2007.12.012>; Mauz and Hoffmann 2014) for
    dose rate modelling for carbonate-rich samples in the context of
    trapped charged dating (e.g., luminescence dating) applications.
    (v0.1.2 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=RCarb> <br />

### ESR data analysis

  - **ESR** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_unpublished.svg' /> <br />R
    package ESR for plotting and analysing ESR spectra in dating
    applications (v2018-12-06 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://github.com/tzerk/ESR> <br />
  - **MCDoseE** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Dose
    response curve fitting, dose evaluation for ESR dating (v | MatLab)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.sciencedirect.com/science/article/pii/S1871101417300626?via%3Dihub>
    <br />*<small>Joannes-Boyau, R., Duval, M., Bodin, T., 2017. MCDoseE
    2.0 A new Markov Chain Monte Carlo program for ESR dose response
    curve fitting and dose evaluation. Quaternary Geochronology 44,
    1–25. doi: <https://doi.org/10.1016/j.quageo.2017.11.003></small>*

### Gamma-ray spectrometry

  - **gammaSpec** <img width=55px src='images/r_scripts.svg' />
    <img width=90px src='images/status_unpublished.svg' /> <br />A
    collection of functions to analyse gamma spectra (v2017-07-17 |
    Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://github.com/tzerk/gammaSpec> <br />

### Luminescence data analysis

  - **Analyst** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />The standard
    programme to analyse luminescence data (v4.57 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <http://users.aber.ac.uk/ggd/> <br />*<small>Duller, G.A.T., 2015.
    The Analyst software package for luminescence data: overview and
    recent improvements. Ancient TL 33, 35–42.</small>*
  - **Luminescence** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A collection
    of various R functions for the purpose of Luminescence dating data
    analysis. This includes, amongst others, data import, export,
    application of age models, curve deconvolution, sequence analysis
    and plotting of equivalent dose distributions. (v0.8.6 | Windows,
    Linux, macOS) <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=Luminescence>
    <br />*<small>Kreutzer, S., Schmidt, C., Fuchs, M.C., Dietze, M.,
    Fischer, M., Fuchs, M., 2012. Introducing an R package for
    luminescence dating analysis. Ancient TL 30, 1–8.</small>*
  - **numOSL** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Package for
    optimizing regular numeric problems in optically stimulated
    luminescence dating, such as: equivalent dose calculation, dose rate
    determination, growth curve fitting, decay curve decomposition,
    statistical age model optimization, and statistical plot
    visualization. (v2.6 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=numOSL> <br />*<small>Peng, J.,
    Dong, Z., Han, F., Long, H., Liu, X., 2013. R package numOSL:
    numeric routines for optically stimulated luminescence dating.
    Ancient TL 31, 41–48.</small>*
  - **PTanalyse** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Proprietary
    software to analyse TR-OSL data (v1.51 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.nutech.dtu.dk/english/products-and-services/radiation-instruments/tl_osl_reader/software>
    <br />*<small> </small>*
  - **RLanalyse** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Proprietary
    software to analyse radiofluorescence data (BIN/BINX-file input
    required) (v1.3 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.nutech.dtu.dk/english/products-and-services/radiation-instruments/tl_osl_reader/software>
    <br />*<small> </small>*
  - **tgcd** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Deconvolving
    thermoluminescence glow curves according to the general-order
    empirical expression or the semi-analytical expression derived from
    the one trap- one recombination (OTOR) model using a modified
    Levenberg-Marquardt algorithm. It provides the possibility of
    setting constraints or fixing any of parameters. It offers an
    interactive way to initialize parameters by clicking with a mouse on
    a plot at positions where peak maxima should be located. The optimal
    estimate is obtained by “trial-and-error”. It also provides routines
    for simulating first-order, second-order, and general-order glow
    peaks (curves). (v2.0 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=tgcd> <br />*<small>Peng, J.,
    Dong, Z., Han, F., 2016. tgcd: An R package for analyzing
    thermoluminescence glow curves. SoftwareX 1–9. doi:
    <https://doi.org/10.1016/j.softx.2016.06.001></small>*
  - **TLdating** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A series of
    function to make thermoluminescence dating using the MAAD or the SAR
    protocol. This package completes the R package “Luminescence.”
    (v0.1.3 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=TLdating>
    <br />*<small>Strebler, D., Burow, C., Brill, D., Br ckner, H.,
    2017. Using R for TL dating. Quaternary Geochronology 37, 97–107.
    doi: <https://doi.org/10.1016/j.quageo.2016.09.001></small>*

### Luminescence data visualisation

  - **Viewer** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_abandoned.svg' />
    <br />Proprietary software to visualise luminescence data recorded
    in BIN/BINX-files (v4.4 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.nutech.dtu.dk/english/products-and-services/radiation-instruments/tl_osl_reader/software>
    <br />*<small> </small>*
  - **Viewer+** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Proprietary
    software to visualise luminescence data recorded in BIN/BINX-files;
    sucessor of Viewer (v1.43 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.nutech.dtu.dk/english/products-and-services/radiation-instruments/tl_osl_reader/software>
    <br />*<small> </small>*

### Miscellaneous

  - **XRFanalyse** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Proprietary
    software to analyse XRF data recorded with a Risø OSL/TL attachement
    (v1.12 | Windows)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.nutech.dtu.dk/english/products-and-services/radiation-instruments/tl_osl_reader/software>
    <br />*<small> </small>*

### Modelling

  - **KMS** <img width=55px src='images/r_scripts.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Collection
    of functions to simulate kinetic models for quartz luminescence
    production (v2018-07-11 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://github.com/pengjunUCAS/KMS> <br />*<small>Peng, J.,
    Pagonis, V., 2016. Simulating comprehensive kinetic models for
    quartz luminescence using the R program KMS. Radiation Measurements
    86, 63–70. doi:
    <https://doi.org/10.1016/j.radmeas.2016.01.022></small>*
  - **RLumModel** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A collection
    of functions to simulate luminescence signals in quartz and Al2O3
    based on published models. (v0.2.3 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=RLumModel>
    <br />*<small>Friedrich, J., Kreutzer, S., Schmidt, C., 2016.
    Solving ordinary differential equations to understand luminescence:
    “RLumModel” an advanced research tool for simulating luminescence
    in quartz using R. Quaternary Geochronology 35, 88–100. doi:
    <https://doi.org/10.1016/j.quageo.2016.05.004></small>*

### Plotting

  - **RLumShiny** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A collection
    of ‘shiny’ applications for the R package ‘Luminescence’. These
    mainly, but not exclusively, include applications for plotting
    chronometric data from e.g. luminescence or radiocarbon dating. It
    further provides access to bootstraps tooltip and popover
    functionality and contains the ‘jscolor.js’ library with a custom
    ‘shiny’ output binding. (v0.2.1 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=RLumShiny> <br />*<small>Burow,
    C., Kreutzer, S., Dietze, M., Fuchs, M.C., Fischer, M., Schmidt, C.,
    Brückner, H., 2016. RLumShiny - A graphical user interface for the R
    Package ’Luminescence’. Ancient TL 34, 22–32.</small>*

### Teaching

  - **LumReader** <img width=55px src='images/r_package.svg' />
    <img width=90px src='images/status_active.svg' /> <br />A series of
    functions to estimate the detection windows of a luminescence reader
    based on the filters and the photomultiplier (PMT) selected. These
    functions also allow to simulate a luminescence experiment based on
    the thermoluminesce (TL) or the optically stimulated luminescence
    (OSL) properties of a material. (v0.1.0 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://CRAN.R-project.org/package=LumReader> <br />

### Visualisation

  - **DensityPlotter** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Java
    application for Kernel Density Estimation plots (v8.4 | Windows,
    Linux, macOS) <br /><img width=20px src='images/url_valid.svg' />
    <https://www.ucl.ac.uk/~ucfbpve/densityplotter/>
    <br />*<small>Vermeesch, P., 2012. On the visualisation of detrital
    age distributions. Chemical Geology, v.312-313, 190-194, doi:
    10.1016/j.chemgeo.2012.04.021 0</small>*
  - **RadialPlotter** <img width=53px src='images/application.svg' />
    <img width=90px src='images/status_active.svg' /> <br />Java
    software to create radial plots (v9.4 | Windows, Linux, macOS)
    <br /><img width=20px src='images/url_valid.svg' />
    <https://www.ucl.ac.uk/~ucfbpve/radialplotter/>
    <br />*<small>Vermeesch, P., 2009, RadialPlotter: a Java application
    for fission track, luminescence and other radial plots, Radiation
    Measurements, 44, 4, 409-410</small>*
