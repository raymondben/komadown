
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Travis-CI Build Status](https://travis-ci.org/jolars/komadown.svg?branch=master)](https://travis-ci.org/jolars/komadown) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/jolars/komadown?branch=master&svg=true)](https://ci.appveyor.com/project/jolars/komadown) [![Coverage Status](https://img.shields.io/codecov/c/github/jolars/komadown/master.svg)](https://codecov.io/github/jolars/komadown?branch=master)

komadown
========

komadown provides [rmarkdown](http://rmarkdown.rstudio.com/) templates for the [KOMA-Script classes](https://komascript.de/) (currently only koma-scartcl). It is intended only for pdf (LaTeX) output.

It wraps around [bookdown](https://github.com/rstudio/bookdown) to enable cross-referencing throughout.

Installation
------------

You can install komadown from github with:

``` r
# install.packages("devtools")
devtools::install_github("jolars/komadown")
```

You will also need

``` r
install.packages(c("rmarkdown", "bookdown"))
```

License
-------

See the [license](LICENSE).
