
<!-- README.md is generated from README.Rmd. Please edit that file -->

# `rGeoCBI`: A burn severity assessment toolkit <img src="man/figures/rGeoCBI.png" align="right" alt="How good was that burn?" width="120" />

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/dbca-wa/rGeoCBI.svg?branch=master)](https://travis-ci.org/dbca-wa/rGeoCBI)
[![Codecov test
coverage](https://codecov.io/gh/dbca-wa/rGeoCBI/branch/master/graph/badge.svg)](https://codecov.io/gh/dbca-wa/rGeoCBI?branch=master)
<!-- badges: end -->

rGeoCBI contains background, digital data capture, analysis, and
visualisation for the calculation of GeoCBI, a composite burn index for
the initial assessment of the short-term burn severity from remotely
sensed data.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
remotes::install_github("dbca-wa/rGeoCBI")
```

## Usage

### Background on GeoCBI

[paper](https://doi.org/10.1016/j.rse.2008.10.011)
[pdf](https://www.researchgate.net/publication/229043914_GeoCBI_A_modified_version_of_the_Composite_Burn_Index_for_the_initial_assessment_of_the_short-term_burn_severity_from_remotely_sensed_data)

Santis, Angela & Chuvieco, Emilio. (2009). GeoCBI: A modified version of
the Composite Burn Index for the initial assessment of the short-term
burn severity from remotely sensed data. Remote Sensing of Environment -
REMOTE SENS ENVIRON. 113. 10.1016/j.rse.2008.10.011. Burn severity
estimation is a key factor in the post-fire management. Previous studies
using remotely sensed data to retrieve burn severity, as measured by the
Composite Burn Index (CBI), have found inconsistencies, since spectral
indices work well in some ecosystems but not in others. These
inconsistencies may be caused by the lack of spectral uniqueness in the
CBI definition, or by the performance of the spectral indices used. This
paper analyses the former aspect, using a simulation analysis to study
the relationships between the CBI and reflectance. Subsequently, a
modified version of this index, called GeoCBI, is proposed to improve
the retrieval of burn severity from remotely sensed data. GeoCBI takes
into account the fraction of cover (FCOV) of the different vegetation
strata used to compute the CBI. Moreover, it also includes the changes
in the leaf area index (LAI) for the intermediate and tall tree strata
(D+E). Field and simulation results show that GeoCBI is more
consistently related to spectral reflectance than CBI for different
ranges of burn severities, while keeping its ecological meaning.

### Data capture

Use supplied Xform to capture data digitally using OpenDataKit.

### Data access

Use ruODK to access captured data.

### Data analysis

Use this package to calculate GeoCBI from captured data.

## Attribution and Citation

`rGeoCBI` was developed, and is maintained, by Florian Mayer for the
Western Australian [Department of Biodiversity, Conservation and
Attractions (DBCA)](https://www.dbca.wa.gov.au/).

The background image in package logo shows the aerial view of a
prescribed burn in the Pilbara. Photo: Paul Rampant (DBCA).

To cite package `rGeoCBI` in publications use:

``` r
citation("rGeoCBI")
#> 
#> To cite rGeoCBI in publications use:
#> 
#>   Florian W. Mayer (2020). rrGeoCBI: A burn severity assessment
#>   toolkit. R package version 0.0.1. https://github.com/dbca-wa/rGeoCBI
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Misc{,
#>     title = {rGeoCBI: A burn severity assessment toolkit},
#>     author = {Florian W. Mayer},
#>     note = {R package version 0.0.1},
#>     year = {2019},
#>     url = {https://github.com/dbca-wa/rGeoCBI},
#>   }
```

## Contribute

Feedback and bug reports are welcome as
[issues](https://github.com/dbca-wa/rGeoCBI/issues).

The development workflow is described in vignette
[Development](https://dbca-wa.github.io/rGeoCBI/articles/dev.html).
