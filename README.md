# Tutorial 1.0: How to use the indiGO R Package

This repository contains a Quarto project that demonstrates the usage of the he **indiGO (Indicators in Generalized Outputs)** R-package which is designed to analyze and display global indicators of the status and trends in nature in a generalized and systematic way. The indiGO package can be found in the [indiGO R package repository](https://github.com/hetzerj/indiGO).

## Overview

The indiGO R-package provides an open-access framework that enables users to access annually and globally aggregated indicators as described in the [first Global Assessment Report on Biodiversity and Ecosystem Services](https://doi.org/10.5281/zenodo.3831673) of the Intergovernmental Science-Policy Platform on Biodiversity and Ecosystem Services (IPBES, 2019). It follows the standardization of indicators outlined in the supplemental material of the Global Assessment Report, [Chapter 2.2: Status and Trends – Nature](https://doi.org/10.5281/zenodo.3832005).

The package provides a flexible framework for handling a wide variety of indicators, not limited to a specific region, ecosystem, or time period. The generalized outputs are broad and adaptable, allowing users to apply them to various generalized data sets or indicator types across global or regional scales. Additionally, indiGO allows users to include their own data, enabling local data integration for customized indicator analysis.

<<<<<<< HEAD
-   **Available Indicators**: Lists all the indicators provided by the **IA** package.
=======
-   **Available Indicators**: Lists all the indicators provided by the indiGO R package.
>>>>>>> bac8815 (renaming the readme files to indiGO_Tutorial1.0)
-   **Function Demonstrations**: Shows how the core functions of the package work, using practical examples.
-   **Plotting Figures**: Provides instructions and examples for visualizing the indicators using the package's functions.

## How to Access the Tutorial

<<<<<<< HEAD
-   Displays all available indicators in the package.
-   Demonstrates how to apply various functions within the package to analyze indicators.
-   Shows how to generate and customize plots for visualizing indicator data.
-   Includes rendered output via GitHub Pages to allow users to view the documentation and examples directly online.

## How to Access the Quarto Project

The Quarto project is rendered as a website using GitHub Pages. You can access the live version of the documentation [here](https://hetzerj.github.io/IA_quarto/).
=======
The Tutorial is rendered as a website using GitHub Pages. You can access the live version of the documentation [here](https://hetzerj.github.io/IA_quarto/).
>>>>>>> bac8815 (renaming the readme files to indiGO_Tutorial1.0)

## Download and Install the indiGO R Package

You can download and install the **indiGO** R package directly from the [indiGO R package repository](https://github.com/hetzerj/indiGO) using the following commands in R:

``` r
# Install devtools if not already installed
install.packages("devtools")

# Install IA package from GitHub
devtools::install_github("hetzerj/indiGO")
```
