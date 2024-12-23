# Code Management Guidelines: <img src="img/logo.png" align="right" height="150"/> R and GitHub Starter Kit for New Team Members

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/) [![DOI](https://zenodo.org/badge/896263653.svg)](https://doi.org/10.5281/zenodo.14510774) [![pages-build-deployment](https://github.com/StringhiniLab/GitHubProceduresLab/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/StringhiniLab/GitHubProceduresLab/actions/workflows/pages/pages-build-deployment)

## Description
This book aims to provide a **basic usage guide** for new lab members regarding the **handling of data and code** with **R** and **GitHub** platform.

It provides:

- A series of steps for **onboarding**.

- Instructions on **programs to install**.

- A guide to **starting a project**.

- Recommendations on **best practices**.

- Instructions on how to **push** locally created code to GitHub using **RStudio**.

## Installation and Setup 
Follow these steps only in case you want to edit the book:

1. **Clone the repository**:
```bash
git clone git@github.com:StringhiniLab/GitHubProceduresLab.git
```
2. **Install dependencies** using `renv`:
```r
install.packages("renv")
renv::restore()
```
3. Open the project in **RStudio** and compile the book running:
```bash
quarto render
```
## Contact
If you have any questions or suggestions, please contact open a [GitHub issue](https://github.com/StringhiniLab/GitHubProceduresLab/issues).

## Code of Conduct
  
Please note that the github_procedures project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.

## Cite Us
If you use this manual, please cite it as follows:

**D'Andrea, F., & Stringhini, S. Code Management Guidelines: R and GitHub Starter Kit for New Team Members. https://github.com/StringhiniLab/GitHubProceduresLab. *https://doi.org/10.5281/zenodo.14510774***

## Session Info
The current environment setup is managed using `renv` to ensure reproducibility. The session info is as follows:

```r
R version 4.2.1 (2022-06-23)
Platform: aarch64-apple-darwin20 (64-bit)
Running under: macOS Monterey 12.5

Matrix products: default
LAPACK: /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/lib/libRlapack.dylib

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

attached base packages:
[1] stats     graphics  grDevices datasets  utils     methods   base     

other attached packages:
[1] usethis_3.1.0

loaded via a namespace (and not attached):
 [1] fansi_1.0.6       withr_3.0.2       rprojroot_2.0.4   utf8_1.2.4       
 [5] lifecycle_1.0.4   magrittr_2.0.3    pillar_1.9.0      rlang_1.1.4      
 [9] cli_3.6.3         renv_1.0.3        rstudioapi_0.17.1 fs_1.6.5         
[13] whisker_0.4.1     vctrs_0.6.5       tools_4.2.1       glue_1.8.0       
[17] purrr_1.0.2       compiler_4.2.1    pkgconfig_2.0.3   clipr_0.8.0      
[21] tibble_3.2.1   
```

