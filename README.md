# McMaster Kinesiology letterhead template

This repository contains the necessary files to produce a basic letter suitable for manuscript cover letters, references, etc.

## Requirements

To compile PDF documents in `R`, you will need to have a LaTeX distribution installed. The easiest way to achieve this on any operating system is with the `tinytex` package:
```r
install.packages("tinytex")

# After installing the package, run the following to finalize installation
tinytex::install_tinytex()

# If using RStudio, restart RStudio and then confirm you have installed successfully
tinytex::is_tinytex()
```

The letterhead template depends on the `R` package `linl` (https://cran.r-project.org/web/packages/linl/index.html), which can be installed from CRAN:
```r
install.packages("linl")
```
Thanks and appreciation to Dirk Eddelbuettel and Aaron Wolen for their work on the `linl` package.
