---
editor_options: 
  markdown: 
    wrap: 72
---

@readme

# The Urban Dividend Gap: Unmasking Inequity in Scotland’s Net Zero Transition

This repository contains the data processing and visualization code for
my entry into the [Data Lab Visualisation Competition
2025](https://thedatalab.com/data-visualisation-competition-2025/). The
project investigates the socio-economic distribution of climate action
co-benefits across Scotland, identifying an "Urban Lag" and a regressive
"Housing Anomaly" in current Net Zero projections.

## 📊 Project Overview

While reaching Net Zero is often framed as a universal win, this
analysis reveals that Scotland’s most populous cities face a "Double
Burden": lower per-capita gains and a fractured distribution of rewards.

### Key Findings

-   **The Urban Lag:** Major cities like Glasgow and Edinburgh show
    lower net gains compared to car-dependent commuter belts.

-   **Compositional Disparity:** Cities show lower potential for "new"
    physical activity gains because their baseline public transport
    usage is already high.

-   **The Housing Anomaly:** Vital health benefits from reducing "Excess
    Cold" are positively correlated with neighborhood affluence (SIMD),
    suggesting benefits are bypassing those in acute fuel poverty.

## 📂 Repository Structure

-   `data-viz-competition-2025.Rmd`: R script used to generate the four
    key visualizations.

-   `/data`: Processed `.csv` files and shapefiles (SIMD and Data Zone
    boundaries).

-   `/output`: High-resolution versions of the infographic figures and
    accompanying data tables.

## 🛠️ Installation & Usage

1.  Clone this repository.

2.  Ensure you have R installed with the following
    libraries: `[tidyverse, sf, viridis]`.

3.  Run `data-viz-competition-2025.Rmd` to reproduce the figures.

## 📈 Data Sources

The analysis is based on the following publicly available datasets:

-   **Climate Co-benefits Data:** Edinburgh Climate Change Institute via
    the [UK Co-Benefit Atlas](https://ukcobenefitsatlas.net).

-   **Scottish Index of Multiple Deprivation (SIMD) 2020:** Available
    via the [Scottish
    Government](https://www.spatialdata.gov.scot/geonetwork/srv/eng/catalog.search#/metadata/02866b0b-66e5-46ab-9b1c-d433dc3c2fae)
    website.

-   **Boundary Files:** Geographic Data Zone boundaries sourced
    from [spatialdata.gov.scot](https://spatialdata.gov.scot/).

## ⚖️ License

This project is licensed under the MIT License - see the `LICENSE` file
for details. The data used is subject to the [Open Government Licence
v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
