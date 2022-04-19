# You can make an R package too!

Talk given at the Bioinformatics group at the University of York, UK

**Slides: [You can make an R package too!](https://bit.ly/3mma-bio-pkg)**

Based on [R Packages](https://r-pkgs.org/) [@wickham2020], Data Science for Modern and Open Research: You can make an R package too! [@rand2021], [Forwards Package development modules](https://github.com/forwards/workshops) [@rand]

Licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />

## Summary

-   Why make a package?

-   Where packages come from and where do they live?

-   Package States

-   How to make a minimal documented package and check it using the `devtools` approach

-   Components of a minimal package

## Learning Objectives

by the end of this session you will able to:

-   explain the rationale for writing packages
-   describe the different states a package can be in
-   create a minimal package and explain its key components
-   add functions with `usethis:use_r()`
-   use the package interactively with `devtools::load_all()`
-   use `devtools::check()` to execute `R CMD` check
-   add a license with `usethis::use_mit_license()`
-   add documentation using **`roxygen2`** and `devtools::document()`
-   add package dependencies with `usethis::use_package()`

## Prerequisites

You should have

-   [R and RStudio](prerequisite-guides/install-r-rstudio.md)
-   [R build toolchain](prerequisite-guides/install-pkg-dev-tools.md): Rtools(windows) or XCode (mac) or r-base-dev
-   the following packages: `devtools` and `assertthat`
-   optionally git, a GitHub account and verified it can talk to RStudio

You can verify your system is set up by running:

`devtools::has_devel()`

in the console
