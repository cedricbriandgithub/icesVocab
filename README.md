[![Build Status](https://travis-ci.org/ices-tools-prod/icesVocab.svg?branch=master)](https://travis-ci.org/ices-tools-prod/icesVocab)
[![codecov](https://codecov.io/gh/ices-tools-prod/icesVocab/branch/master/graph/badge.svg)](https://codecov.io/gh/ices-tools-prod/icesVocab)
[![GitHub release](https://img.shields.io/github/release/ices-tools-prod/icesVocab.svg?maxAge=2592001)]()
[![CRAN Status](http://www.r-pkg.org/badges/version/icesVocab)](https://cran.r-project.org/package=icesVocab)
[![CRAN Monthly](http://cranlogs.r-pkg.org/badges/icesVocab)](https://cran.r-project.org/package=icesVocab)
[![CRAN Total](http://cranlogs.r-pkg.org/badges/grand-total/icesVocab)](https://cran.r-project.org/package=icesVocab)
[![License](https://img.shields.io/badge/license-GPL%20(%3E%3D%202)-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

[<img align="right" alt="ICES Logo" width="17%" height="17%" src="http://ices.dk/_layouts/15/1033/images/icesimg/iceslogo.png">](http://ices.dk)

icesVocab
=========

icesVocab provides R functions that access the
[web services](http://vocab.ices.dk/services/POX.aspx) of the
[ICES](http://ices.dk) [Vocabularies](http://vocab.ices.dk) database of
reference codes.

icesVocab is implemented as an [R](https://www.r-project.org) package and
available on [CRAN](https://cran.r-project.org/package=icesVocab).

Installation
------------

icesVocab can be installed from CRAN using the `install.packages` command:

```R
install.packages("icesVocab")
```

Usage
-----

For a summary of the package:

```R
library(icesVocab)
?icesVocab
```

References
----------

ICES Vocabularies database:
http://vocab.ices.dk

ICES Vocabularies web services:
http://vocab.ices.dk/services/POX.aspx

Development
-----------

icesVocab is developed openly on
[GitHub](https://github.com/ices-tools-prod/icesVocab).

Feel free to open an
[issue](https://github.com/ices-tools-prod/icesVocab/issues) there if you
encounter problems or have suggestions for future versions.

The current development version can be installed using:

```R
install.packages("icesVocab", repos = c("https://ices-tools-prod.r-universe.dev", "https://cloud.r-project.org"))
```
