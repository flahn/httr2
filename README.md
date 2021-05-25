
<!-- README.md is generated from README.Rmd. Please edit that file -->

# httr2

<!-- badges: start -->

[![R-CMD-check](https://github.com/r-lib/httr2/workflows/R-CMD-check/badge.svg)](https://github.com/r-lib/httr2/actions)
[![Codecov test
coverage](https://codecov.io/gh/r-lib/httr2/branch/master/graph/badge.svg)](https://codecov.io/gh/r-lib/httr2?branch=master)
<!-- badges: end -->

httr2 is a ground up rewrite of httr with two main goals:

-   Create a pipeable API that makes the request object explicit.

-   Solve problems that were out of scope for httr but make writing API
    wrappers a pain (e.g. rate-limiting, retries, non-standard oauth, …)

## Installation

You can install the released version of httr2 from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("httr2")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("r-lib/httr2")
```

## 