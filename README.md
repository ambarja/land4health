
<!-- README.md is generated from README.Rmd. Please edit that file -->

# land4health <img src="man/figures/land4health.svg" align="right" width="100" style="margin-left: 10px;"/> ![lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange)

## Overview

**land4health** is a tool developed within the HARMONIZE project to
analyze frequency-grouped, weighted, and multi-source environmental
indicators. The tool comprises a R package with comprehensive
documentation, including usage examples and parameter selection
guidelines tailored to specific case studies.

The functions that are part of the tool allow for:

- Calculation of zonal statistics, such as **mean**, **maximum**,
  **minimum**, **median**, **standard deviation**, **variance**,
  **sum**, and **min-max range** of climate variables

- Processing of environmental data by grouping indicators by frequency
  and applying weights.

- Visualization of spatial and temporal patterns of environmental
  indicators.

## Dependencies

<table>
<colgroup>
<col style="width: 29%" />
<col style="width: 70%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="man/figures/logo_rgee.png" width="200"/></td>
<td><strong>rgee</strong><br />
R binding package that uses reticulate to wrap the Earth Engine Python
API and provide R users with a familiar interface,</td>
</tr>
</tbody>
</table>

## Installation

You can install the development version of land4health from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("harmonize-tools/land4health")
```

## How to Start

To start using the `land4health` package, you can load it with
`library(land4health)`.

``` r
# Load the package
library(land4health)
```

When you load the package, you should see the following welcome message:

    #> ── Welcome to land4health ──
    #>  🌍 land4health provides tools for analyzing frequency-grouped, weighted, and multi-source environmental indicators.
    #>  Currently, `land4health` supports the following features:
    #>  ✔ Zonal statistics calculation (e.g., MEAN, MAXIMUM, MINIMUM, MEDIAN)
    #>  ✔ Multi-source data integration and harmonization
    #>  ✔ Export and visualization of results
    #>  ℹ For more information, use `?land4health` or `help(package = 'land4health')`.

## Organization

<img src="man/figures/logo_InnovaLab.png" alt="Health Innovation Laboratory, Institute of Tropical Medicine &apos;Alexander von Humboldt&apos;" width="200"/>

**Health Innovation Laboratory, Institute of Tropical Medicine
“Alexander von Humboldt”**  
Universidad Peruana Cayetano Heredia (Lima, Peru)
