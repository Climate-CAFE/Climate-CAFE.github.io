# Example Datasets in the CAFE Dataverse Collection


## Wildfire Smoke Dataset [Dataverse Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VHNJBD)
- **Description:** This dataset contains daily aggregated measurements of daily PM2.5 from ambient wildfire smoke in the contiguous United States, spanning from 2006 to 2016. The data is sourced from a study by Childs et al. (2022), titled "Daily Local-Level Estimates of Ambient Wildfire Smoke PM2.5 for the Contiguous US" published in Environmental Science & Technology.

  To compute the standardized weight across different zip codes, we computed the weight calculation on a 10km grid. To compute the weight, we obtain area-weights that add up to 1 in each polygon of zip codes. This enabled us to calculate the smoke values per zip code for the aforementioned period. Those interested in replicating our data processing pipeline can access it at [GitHub Repository](https://github.com/NSAPH-Data-Processing/smoke_aggregation).

- **Metadata:**
  ```markdown
  dataset_name: Wildfire Smoke Dataset
  description: Daily aggregated measurements of PM2.5 from ambient wildfire smoke in the contiguous United States.
  
  files:
    - daily_zip_2006.csv
    - daily_zip_2006.csv
    - ...
  
  data_profile:
    time_coverage: 2006-2016
    spatial_coverage: zipcodes
    unit: μg/m3
  ```

## PM2.5 Components Dataset [Dataverse Link](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/2NT5CV)
- **Description:** This dataset provides comprehensive insights into the annual distribution of PM2.5 (Particulate Matter with a diameter of 2.5 micrometers or smaller) components across different Zip Code Tabulation Areas (ZCTAs). PM2.5 is a critical air pollutant with potential health and environmental impacts. This data highlights the individual components that contribute to PM2.5 levels, offering valuable information for air quality research and policymaking. This dataset is processed and aggregated from Randall Martin's PM2.5 components data. Those interested in replicating our data processing pipeline can access it at [GitHub Repository](https://github.com/NSAPH-Data-Processing/pm25_components_randall_martin)

  The dataset covers various PM2.5 components, including:
  - BC (Black Carbon)
  - NH4 (Ammonium)
  - NIT (Nitrate)
  - OM (Organic Matter)
  - SO4 (Sulfate)
  - SOIL (Soil Dust)
  - SS (Sea Salt)

- **Metadata:**
  ```markdown
  dataset_name: PM2.5 Components Dataset
  description: Annual distribution of PM2.5 components across different Zip Code Tabulation Areas (ZCTAs).
  
  files:
    - V4NA03_PM25_NA_200001_200012-RH35_zcta.tab
    - V4NA03_PM25_NA_200101_200112-RH35_zcta.tab
    - ...
  
  data_profile:
    time_coverage: 2006-2016
    spatial_coverage: ZCTA
    unit: μg/m3
  ```


## ZIP to ZCTA Crosswalks Dataset [Dataverse Link]()
- **Description:** This dataset contains cleaned crosswalks obtained from the UDS Mapper at [UDS Mapper](https://udsmapper.org/zip-code-to-zcta-crosswalk/). The aim is to create a unified zip2zcta crosswalk for multi-year use, including retired zip codes and resolving ambiguities. Those interested in replicating our data processing pipeline can access it at [GitHub Repository](https://github.com/NSAPH-Data-Processing/zip2zcta_master_xwalks)


- **Data Description:**
  - **Time Coverage:** N/A
  - **State Coverage:** All US states
  - **Population Coverage:** N/A
  - **Unit:** Zipcode, ZCTA

- **Codebook:**
  - `zip` (character): 5-digit ZIP code used by USPS.
  - `zcta` (character): 5-digit ZIP Code Tabulation Area (ZCTA) code used by the US Census Bureau.
  - `year_match` (int): Year of zip and zcta match.
  - `census_edition` (character): Census data edition/version.
  - `state` (character): U.S. state or territory.
  - `is_area` (boolean): ZIP code type flag (ZIP Code Area).
  - `is_self_mapped` (boolean): ZIP code type flag (Directly maps to ZCTA).
  - `is_post_office` (boolean): ZIP code type flag (Post Office or large volume customer).
  - `info` (character): Additional context or information.
  - `min_match` (int): Minimum year match.
  - `max_match` (int): Maximum year match.
  - `year_matches` (int): Number of year matches.
  - `zcta_matches` (int): Number of ZCTA matches.
