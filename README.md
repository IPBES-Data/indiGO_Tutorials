# Tutorials for the indiGO R Package

This repository contains tutorials that demonstrate the usage of the **indiGO (Indicators in Generalized Outputs)** R package, which is designed to analyze and display indicators of the status and trends in nature in a generalized and systematic way. The indiGO package can be found in the [indiGO R package repository](https://github.com/IPBES-Data/indiGO).

## Overview

The indiGO R package provides an open-access framework that enables users to access annually aggregated indicators as described in the [first Global Assessment Report on Biodiversity and Ecosystem Services](https://doi.org/10.5281/zenodo.3831673) by the Intergovernmental Science-Policy Platform on Biodiversity and Ecosystem Services (IPBES, 2019). It follows the standardization of indicators outlined in the supplementary material of the Global Assessment Report, [Chapter 2.2: Status and Trends – Nature](https://doi.org/10.5281/zenodo.3832005).

The package offers a flexible framework for handling a wide variety of indicators, not limited to a specific region, ecosystem, or time period. Its generalized outputs are broad and adaptable, allowing users to apply them to various data sets or indicator types across global or regional scales. Additionally, indiGO allows users to include their own data, enabling local data integration for customized indicator analysis.

-   **Available Indicators**: The package includes a variety of indicator data sets. The tutorials provided here demonstrate how to browse and load them.
-   **Function Demonstrations**: The tutorials cover basic and advanced functionalities of the package, using practical examples.
-   **Plotting Figures**: Users can follow instructions to visualize indicators and create standardized figures using the package’s functions.

Tutorials are written in Quarto documents that are rendered as HTML websites and published using GitHub Pages. Links to the tutorials can be found below.

## Download and Install the indiGO R Package

You can download and install the **indiGO** R package directly from the [indiGO R package repository](https://github.com/IPBES-Data/indiGO) using the following commands in R:

``` r
# Install devtools if not already installed
install.packages("devtools")

# Install indiGO package from GitHub
devtools::install_github("hetzerj/indiGO")
```

## Tutorial 1.0: How to Use the indiGO R Package

This tutorial provides an overview of the core functionalities of the package, including browsing, loading, and displaying indicators in generalized outputs. You can access the live version of the documentation here: [Tutorial 1.0: How to Use the indiGO R Package](https://ipbes-data.github.io/indiGO_Tutorials/).
