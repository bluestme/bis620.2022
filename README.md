
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bis620.2022

<!-- badges: start -->

[![R-CMD-check](https://github.com/bluestme/bis620.2022/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/bluestme/bis620.2022/actions/workflows/R-CMD-check.yaml)
[![codecov](https://codecov.io/gh/bluestme/bis620.2022/branch/main/graph/badge.svg?token=LWLNP38CUE)](https://codecov.io/gh/bluestme/bis620.2022)
[![test-coverage-check](https://github.com/bluestme/bis620.2022/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/bluestme/bis620.2022/actions/workflows/test-coverage.yaml)
[![lint](https://github.com/bluestme/bis620.2022/actions/workflows/lint.yaml/badge.svg)](https://github.com/bluestme/bis620.2022/actions/workflows/lint.yaml)
<!-- badges: end -->

The goal of bis620.2022 is to analyze the Accelerometry Data. It
contains the dataset of a toy accelerometry dataset from UKBiobank where
x is an object inherited from data.frame. It is assumed to have a time,
X, Y, and Z column along with either a time or freq column.

Two related functions are included, with one calculating spectral
signature by taking the modulus of the Fourier coefficients of the
signal and one plot function and one plotting UKBiobank Accelerometry
Data.

## Installation

You can install the development version of bis620.2022 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("bluestme/bis620.2022")
```
