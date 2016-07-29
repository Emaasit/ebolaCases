
<!-- README.md is generated from README.Rmd. Please edit that file -->
ebolaCases
========

Number of Ebola Cases and Deaths in Affected Countries
-------------------------------------------------------

The R package *ebolaCases* provides data for the total number of probable, confirmed and suspected Ebola cases and deaths in Guinea, Liberia, Sierra Leone, Nigeria, Senegal, Mali, Spain USA, UK and Italy according to [Ebola Data and Statistics](http://apps.who.int/ebola/ebola-situation-reports).

How to install
--------------

You can install the latest release of the package from CRAN like this

``` r
install.packages("ebolaCases")
```

Or you can install the development version from github, which may have some changes that are not yet on CRAN, using `devtools`, like this:

``` r
devtools::install_github("emaasit/ebolaCases", 
                         build_vignettes = TRUE)
library(ebolaCases)
```

License
-------

This package is free and open source software, licensed under GPL (&gt;= 2).

Feedback, contributing, etc.
----------------------------

Please open and issue if you find something that doesn't work as expected or have questions or suggestions. Note that this project is released with a [Guide to Contributing](CONTRIBUTING.md) and a [Contributor Code of Conduct](CONDUCT.md). By participating in this project you agree to abide by its terms.

Acknoweldgement
----------------

Thanks to [The Humanitarian Data Exchange](https://data.humdata.org/) for collecting and hosting these data
