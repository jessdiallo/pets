
# pets <img src="man/figures/logo.png" align="right" alt="" width="120" />

The goal of pets is to provide a simple means for people to express
their feelings about pets. At present, the package only contains one
function: `cats()`.

## Installation

You can install the the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jessdiallo/pets")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(pets)

## if you like cats
cats(TRUE)
#> [1] "I love cats!"

## if you don't like cats
cats(FALSE)
#> [1] "I am not a cat person."
```

## Error reporting

If you find a bug, please file an issue on this repository.
