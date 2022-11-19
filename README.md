
# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to  make regular expressions more exciting! It provides convenience functions to make some common tasks with string manipulation and regular expressions a bit easier.

## Installation

You can install the development version of regexcite like so:

``` r
# install.packages("devtools")
devtools::install_github("jennybc/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
str_split_one(x, pattern = ",", n = 2)
#> [1] "alfa"                "bravo,charlie,delta"

y <- "192.168.0.1"
str_split_one(y, pattern = stringr::fixed("."))
#> [1] "192" "168" "0"   "1"
```

