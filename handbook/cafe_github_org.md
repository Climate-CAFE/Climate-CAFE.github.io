# Climate CAFÉ GitHub Organization

## Climate & Health Tutorials and Code Sharing

CAFÉ RCC has a established a [community GitHub organization](https://github.com/Climate-CAFE) to share code, examples, and tutorials on working with common data formats and sources. We are assembling a collection of standard operating procedures (SOPs) for data processing, integration, harmonization, and analysis with code and tutorials in order to facilitate reproducibility and reusability for the climate and health Community of Practice.  

The CAFÉ Data Management Function team has begun to develop and share code and tutorials that cover tasks such as spatial aggregations, data harmonization, and analysis across languages including R and Python. As the CAFÉ community grows to include more of the climate and health Community of Practice, we will continue to refine and expand these materials to showcase additional analyses platforms (e.g., ArcGIS). We also hope that community members joining the CAFÉ initiative will contribute, share, and reuse code and software within the CAFÉ GitHub.

All code repositories on GitHub whose content is intended to be shared with the CAFÉ research community should be tagged with the [GitHub topic tag](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) `climate-cafe`. This enables anyone in the climate and health community of practice to easily find relevant code repositories simply by searching for the `climate-cafe` term on GitHub, by clicking on the `climate-cafe` topic tag anywhere it appears on GitHub, or by navigating directly to https://github.com/topics/climate-cafe.

## Current Tutorials and Code Walkthroughs

Our team members have created tutorials and code examples for several key data management procedures and common analysis challenges that climate and health researchers may encounter. These tutorials are intended to provide usable example materials that researchers can download and step through on their own.

Many of these materials are still under active development, so please check back regularly for updates.

### Live Tutorials and Code

| Title | Description | Repository Link |
| --- | --- | --- |
| **Population Weighting Raster Data** | Using the gridded meteorological dataset PRISM as an example, this tutorial demonstrates how to aggregate raster data to administrative units (e.g., counties) with population weights. | https://github.com/Climate-CAFE/population_weighting_raster_data |
| **Joining Tabular & Spatial Data** | This repository provides tutorial scripts in R and Python for spatializing and mapping tabular temperature data at the county level. | https://github.com/Climate-CAFE/tabular_spatial_data_join |
| **US Census yearly time series tutorial** | A succinct tutorial for generating time series of socio-economic variables from the US Census Bureau using its API. | https://github.com/Climate-CAFE/census_tutorial |
| **Overview of ZIP Codes and Zip Code Tabulation Areas (ZCTAs)** | This tutorial provides an overview of the differences between ZIP Codes and Zip Code Tabulation Areas and provides code for creating a crosswalk between census blocks and ZCTAs. | https://github.com/Climate-CAFE/zip_codes_and_zctas |

### Under Development

| Title | Description |
| --- | --- |
| **Discrete Variable Spatial Aggregation** | This tutorial will help researchers explore and understand the process of the spatial aggregation for discrete variables. It will provide the Python code to guide you through various steps of producing spatial aggregation from 1km tiff raster to county polygons for the [Koppen-Geiger climate types](https://www.nature.com/articles/sdata2018214) data. |
| **Block and Tract-Level PM2.5 Aggregation** | This tutorial will provide an R walkthrough for downloading [high-resolution PM2.5 point data from SEDAC](https://sedac.ciesin.columbia.edu/data/set/aqdh-pm2-5-component-ec-nh4-no3-oc-so4-50m-1km-contiguous-us-2000-2019), intersecting PM2.5 data with US census blocks, and population-weighting from the block to tract, block-group, and county levels |
| **Nationwide Roads Tract Aggregation** | This tutorial will provide the steps for downloading [TIGER/Line roads data](https://assets.nhgis.org/original-data/gis/TGRSHP2020_TechDoc.pdf) and calculating tract-level sum road lenth measures stratified by road class using R. |
| **Bash Scripting for Climate and Health Research** | This tutorial will give an overview of bash scripting and its potential uses in climate and health research. |

## Expanding Our Efforts

We hope that in addition to learning from these tutorials, community members will see these materials as representative examples of the kinds of materials they can develop and share through the CAFÉ themselves. If you are interested in contributing a tutorial or example workflow to the CAFÉ yourself, please contact us about joining CAFÉ Github organization or having your existing Github repository added to CAFÉ through a new fork, so that we can share your materials with the broader climate and health Community of Practice.
