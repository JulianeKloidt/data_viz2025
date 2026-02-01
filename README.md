# The Urban Dividend Gap: Unmasking Inequity in Scotland’s Net Zero Transition

This repository contains the data visualization and validation code for my entry into the Data Lab Visualisation Competition 2025. The project investigates the socio-economic distribution of climate action co-benefits across Scotland, identifying an "Urban Lag" and a regressive "Housing Anomaly" in current Net Zero projections.

## 🎥 5-Minute Project Pitch: 

[\<click here\>](https://www.loom.com/share/97c54820bceb4868ab7812ce574b0798)

## 📊 Project Overview

While reaching Net Zero is often framed as a universal win, this analysis reveals that Scotland’s most populous cities face a "Double Burden": lower per-capita gains and a fractured distribution of rewards.

### Key Findings

-   **The Urban Lag:** Major cities like Glasgow and Edinburgh show lower net gains compared to car-dependent commuter belts.

-   **Compositional Disparity:** Cities show lower potential for "new" physical activity gains because their baseline public transport usage is already high.

-   **The Housing Anomaly:** Vital health benefits from reducing "Excess Cold" are positively correlated with neighborhood affluence (SIMD), suggesting benefits are bypassing those in acute fuel poverty.

## 📂 Repository Structure

-   `data-viz-competition-2025.Rmd`: R Markdown used to generate the four key visualizations.

-   `validation-checks.Rmd`: R Markdown used to perform validation checks.

-   `/data`: Processed .csv files and shapefiles (SIMD and Data Zone boundaries).

-   `/output`: High-resolution versions of the infographic figures and accompanying data tables.

## 🛠️ Installation & Usage

1.  Clone this repository.

2.  Ensure you have R installed with the following libraries: [tidyverse, sf, viridis].

3.  Run `data-viz-competition-2025.Rmd` to reproduce the figures.

4.  Run `validation-checks.Rmd` to investigate inequity in the Net Zero transition for other Scottish cities and for other housing-related variables.

## 📈 Data Sources

The analysis is based on the following publicly available datasets:

-   **Climate Co-benefits Data:** Edinburgh Climate Change Institute via the UK Co-Benefit Atlas.

-   **Scottish Index of Multiple Deprivation (SIMD) 2020:** Available via the Scottish Government website.

-   **Boundary Files:** Geographic Data Zone boundaries sourced from spatialdata.gov.scot.

⚖️ License

This project is licensed under the MIT License - see the LICENSE file for details. The data used is subject to the Open Government Licence v3.0.
