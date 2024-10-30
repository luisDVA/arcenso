
<!-- README.md is generated from README.Rmd. Please edit that file -->

# **ARcenso** <img src="man/figures/logo.png" align="right" height="138"/>

<!-- badges: start -->
<!-- badges: end -->

## Overview

This project was supported by the [rOpenSci Champions
Program](https://ropensci.org/blog/2024/02/15/champions-program-champions-2024/)
2023-2024, with [Andrea Gomez Vargas](https://github.com/SoyAndrea) as
the main developer and [Luis D. Verde
Arregoitia](https://github.com/luisDVA) as the mentor.

**arcenso** is a package under development that will allow access to the
official data of the national population censuses in Argentina from the
National Institute of Statistics and Census - INDEC. Currently, the
results of the historical censuses of 1970, 1980, 1991, 2001, 2010 and
2022 are available in different formats through physical books, PDFs,
Excel files or in REDATAM, without having a unified system or format
that allows working with the data of these six census periods as a
database. In addition, the presentation of the data is not homogeneous
between the periods, making it difficult to make historical or serial
comparisons of the available information.

This package aims to make census data available, homogenized and ready
to use. It will include the census data from 1970 to 2022. Having a
package of census information will allow the public and private sectors,
citizens and other actors in society to access current and historical
information on Argentina’s population, households and housing in a more
accessible way.

## Installation

You can install the development version of arcenso from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("SoyAndrea/arcenso")
```

## Main functions

**arcenso** provides

- `get_census()`: get a list with the tables currently available in the
  package

- `check_repository()`: reports the tables currently available in the
  package

## Usage

``` r
library(arcenso)

## basic example code

# get_census(year = 1970)
```
