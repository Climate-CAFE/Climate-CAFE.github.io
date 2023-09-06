## Catalog

The following data is available at: **`/n/dominici_nsaph_l3/Lab/projects/analytic/`**

### MedPar (Admissions)

`````{dropdown} **admissions_by_year**

```{list-table}
:header-rows: 0

* - data_source
  - MedPar
* - fasse_location
  - `admissions_by_year`
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/gen_admission/ 1999_2016/targeted_conditions/cache_data/admissions_by_year/`
* - date_created
  - Feb 20 2020
* - size
  - 22 GB
* - files
  - 
```
```
   ├── admissions_1999.fst
   ├── admissions_2000.fst
   ├── ...
   └── admissions_2016.fst
```
````{dropdown} header
```
QID                      : chr  
AGE                      : int  
SEX                      : int  
RACE                     : int  
SSA_STATE_CD             : int  
SSA_CNTY_CD              : int  
PROV_NUM                 : int  
ADM_SOURCE               : chr  
ADM_TYPE                 : int  
ADATE                    : chr  
DDATE                    : chr  
BENE_DOD                 : chr  
DODFLAG                  : chr  
ICU_DAY                  : int  
CCI_DAY                  : int  
ICU                      : int  
CCI                      : int  
DIAG1                    : chr  
DIAG2                    : chr  
DIAG3                    : chr  
DIAG4                    : chr  
DIAG5                    : chr  
DIAG6                    : chr  
DIAG7                    : chr  
DIAG8                    : chr  
DIAG9                    : chr  
DIAG10                   : logi 
diag11                   : logi 
diag12                   : logi 
diag13                   : logi 
diag14                   : logi 
diag15                   : logi 
diag16                   : logi 
diag17                   : logi 
diag18                   : logi 
diag19                   : logi 
diag20                   : logi 
diag21                   : logi 
diag22                   : logi 
diag23                   : logi 
diag24                   : logi 
diag25                   : logi 
YEAR                     : int  
LOS                      : int  
Parkinson_pdx            : int  
Parkinson_pdx2dx_10      : int  
Parkinson_pdx2dx_25      : int  
Alzheimer_pdx            : int  
Alzheimer_pdx2dx_10      : int  
Alzheimer_pdx2dx_25      : int  
Dementia_pdx             : int  
Dementia_pdx2dx_10       : int  
Dementia_pdx2dx_25       : int  
CHF_pdx                  : int  
CHF_pdx2dx_10            : int  
CHF_pdx2dx_25            : int  
AMI_pdx                  : int  
AMI_pdx2dx_10            : int  
AMI_pdx2dx_25            : int  
COPD_pdx                 : int  
COPD_pdx2dx_10           : int  
COPD_pdx2dx_25           : int  
DM_pdx                   : int  
DM_pdx2dx_10             : int  
DM_pdx2dx_25             : int  
Stroke_pdx               : int  
Stroke_pdx2dx_10         : int  
Stroke_pdx2dx_25         : int  
CVD_pdx                  : int  
CVD_pdx2dx_10            : int  
CVD_pdx2dx_25            : int  
CSD_pdx                  : int  
CSD_pdx2dx_10            : int  
CSD_pdx2dx_25            : int  
Ischemic_stroke_pdx      : int  
Ischemic_stroke_pdx2dx_10: int  
Ischemic_stroke_pdx2dx_25: int  
Hemo_Stroke_pdx          : int  
Hemo_Stroke_pdx2dx_10    : int  
Hemo_Stroke_pdx2dx_25    : int  
zipcode_R                : int  
Race_gp                  : chr  
Sex_gp                   : chr  
age_gp                   : chr  
Dual                     : int  
```
````
`````

### MBSF (Denominator)
`````{dropdown}  **denom**

```{list-table}
:header-rows: 0

* - data_source
  - MBSF
* - fasse_location
  - `denom`
* - size
  - 7.4 GB
* - files
  - 
```
```
   ├── qid_data_2009.fst
   ├── qid_data_2010.fst
   ├── ...
   ├── qid_data_2016.fst
   ├── qid_entry_exit.fst
   └── year_zip_confounders.fst
```
````{dropdown} header (qid_data_yyyy)
```
qid   : chr  
year  : int  
zip   : int  
sex   : int  
age   : int  
dual  : chr  
dead  : logi 
hmo_mo: chr  
fips  : int  
race  : chr  
sexM  : num  
```
````
````{dropdown} header (year_zip_confounders)
```
zip               : num  
year              : int  
mean_bmi          : num  
smoke_rate        : num  
hispanic          : num  
pct_blk           : num  
medhouseholdincome: num  
medianhousevalue  : num  
poverty           : num  
education         : num  
popdensity        : num  
pct_owner_occ     : num  
summer_tmmx       : num  
winter_tmmx       : num  
summer_rmax       : num  
winter_rmax       : num  
city              : chr  
statecode         : chr  
latitude          : num  
longitude         : num  

min_year: 2000
max_year: 2016
```
````
`````

### Annual Exposure per Medicare Beneficiary
`````{dropdown} **qid_yr_exposures**

```{list-table}
:header-rows: 0

* - rce_location
  - `~/shared_space/ci3_analysis/dmork/Data/DLM_ADRD`
* - fasse_location
  - `qid_yr_exposures`
* - dataset_author
  - Daniel Mork
* - date_created
  - April 2022
* - size
  - 139 GB
* - description
  - Annual exposure measurements (columns, 2000-2016) for each Medicare benficiary (rows) tied to their zip code of residence in a given year. Exposures (xxx in file name) include: no2, ozone, pm2.5, pm2.5components, pr (precipitation), rmax (max humidity), tmmx (max temperature), zip (zip code of residence).
* - files
  - 
```

```
    ├── qid_yr_no2.fst
    ├── qid_yr_ozone.fst
    ├── qid_yr_pm25comp_br.fst
    ├── qid_yr_pm25comp_ca.fst
    ├── qid_yr_pm25comp_cu.fst
    ├── qid_yr_pm25comp_ec.fst
    ├── qid_yr_pm25comp_fe.fst
    ├── qid_yr_pm25comp_k.fst
    ├── qid_yr_pm25comp_nh4.fst
    ├── qid_yr_pm25comp_ni.fst
    ├── qid_yr_pm25comp_no3.fst
    ├── qid_yr_pm25comp_oc.fst
    ├── qid_yr_pm25comp_pb.fst
    ├── qid_yr_pm25comp_si.fst
    ├── qid_yr_pm25comp_so4.fst
    ├── qid_yr_pm25comp_v.fst
    ├── qid_yr_pm25comp_z.fst
    ├── qid_yr_pm25.fst
    ├── qid_yr_pr.fst
    ├── qid_yr_rmax.fst
    ├── qid_yr_tmmx.fst
    └── qid_yr_zip.fst
```

````{dropdown} header (qid_yr_xxx.fst):
```
qid : chr  
2000: num  
2001: num  
2002: num  
2003: num  
2004: num  
2005: num  
2006: num  
2007: num  
2008: num  
2009: num  
2010: num  
2011: num  
2012: num  
2013: num  
2014: num  
2015: num  
2016: num
```
````
`````

### MBSF (Enrollment file, denominator) 
`````{dropdown} **denom_by_year**

```{list-table}
:header-rows: 0

* - data_source
  - MBSF, census (interpolated), BRFSS (interpolated), PM2.5 exposure, seasonal temperature
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/mortality/ 1999_2016/wu/cache_data/merged_by_year_v2`
* - fasse_location
  - `denom_by_year`
* - git_repository 
  - [github.com/NSAPH/National-Causal-Analysis](https://github.com/NSAPH/National-Causal-Analysis/tree/master/MergedData)
* - dataset_author
  - Ben Sabath, Xiao Wu
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 1999-2016
* - processing_description
  - Recommended for use. Available in both `.fst` and `.csv` formats on FASSE.
* - date_created
  - Apr 2021
* - size
  - 7.4 GB
* - files
  - 
```

```
   ├── confounder_exposure_merged_nodups_health_1999.fst
   ├── ...
   └── confounder_exposure_merged_nodups_health_2016.fst
```
````{dropdown} header
```
zip                         : int  
year                        : int  
qid                         : chr  
dodflag                     : chr  
bene_dod                    : chr  
sex                         : int  
race                        : int  
age                         : int  
hmo_mo                      : chr  
hmoind                      : chr  
statecode                   : chr  
latitude                    : num  
longitude                   : num  
dual                        : chr  
death                       : int  
dead                        : logi 
entry_age                   : int  
entry_year                  : int  
entry_age_break             : int  
followup_year               : num  
followup_year_plus_one      : num  
pm25_ensemble               : num  
pm25_no_interp              : num  
pm25_nn                     : num  
ozone                       : num  
ozone_no_interp             : num  
zcta                        : int  
poverty                     : num  
popdensity                  : num  
medianhousevalue            : num  
pct_blk                     : num  
medhouseholdincome          : num  
pct_owner_occ               : num  
hispanic                    : num  
education                   : num  
population                  : num  
zcta_no_interp              : int  
poverty_no_interp           : num  
popdensity_no_interp        : num  
medianhousevalue_no_interp  : num  
pct_blk_no_interp           : num  
medhouseholdincome_no_interp: num  
pct_owner_occ_no_interp     : num  
hispanic_no_interp          : num  
education_no_interp         : num  
population_no_interp        : int  
smoke_rate                  : num  
mean_bmi                    : num  
smoke_rate_no_interp        : num  
mean_bmi_no_interp          : num  
amb_visit_pct               : num  
a1c_exm_pct                 : num  
amb_visit_pct_no_interp     : num  
a1c_exm_pct_no_interp       : num  
tmmx                        : num  
rmax                        : num  
pr                          : num  
cluster_cat                 : chr  
fips_no_interp              : int  
fips                        : int  
summer_tmmx                 : num  
summer_rmax                 : num  
winter_tmmx                 : num  
winter_rmax                 : num  
```
````
`````

### AD/ADRD Hospitalization
`````{dropdown} **hospitalization**

```{list-table}
:header-rows: 0

* - data_source
  - MedPar derived
* - rce_location
  - `~/shared_space/ci3_analysis/dmork/Data/DLM_ADRD`
* - fasse_location
  - `hospitalization`
* - dataset_author
  - Daniel Mork
* - description
  - The first recorded hospitalization for each individual broken down by primary/secondary/any billing code (ICD).
* - size
  - 1.2 GB
* - files
  - 
```
```
   ├── First_hosp_AD_any.fst
   ├── First_hosp_AD_primary.fst
   ├── First_hosp_ADRD_any.fst
   ├── First_hosp_ADRD_primary.fst
   ├── First_hosp_ADRD_secondary.fst
   └── First_hosp_AD_secondary.fst
```
````{dropdown} header
```
QID  : Factor 
ADATE: Date
year : num  
```
````
`````

### Medicare Entry Age
`````{dropdown} **medicare_entry_age**

```{list-table}
:header-rows: 0

* - data_source
  - MBSF derived
* - rce_location
  - `/nfs/nsaph_ci3/scratch/jan2021_whanhee_cache/entry_age/`
* - fasse_location
  - `medicare_entry_age`
* - size
  - 2.3 GB
* - date_created
  - Jan 26, 2021
* - dataset_author
  - Ben Sabath, Whenhee Lee
* - spatial_resolution
  - zipcode
* - git_repository
  - [NSAPH/data_requests](https://github.com/NSAPH/data_requests/blob/master/request_projects/jan2021_whanhee_fisrt_hosps/code/1_create_indivdual_vars.R)
* - files
  -
```
```
   └── medicare_entry_age.csv
```
`````

### Years in Medicare 
`````{dropdown} **years_in_medicare**
```{list-table}
:header-rows: 0

* - data_source
  - MBSF derived
* - rce_location
  - `/nfs/nsaph_ci3/scratch/jan2021_whanhee_cache/follow_up/`
* - fasse_location
  - `years_in_medicare`
* - description
  - Number of years a beneficiary has been in Medicare (or in other words, the number of years since one has entered Medicare). Allows for grouping on how long beneficiaries have been in Medicare.
* - size
  - 8.8 GB
* - date_created
  - Jan 26, 2021
* - temporal_coverage
  - 1999-2016
* - dataset_author
  - Ben Sabath, Whanhee Lee
* - spatial_resolution
  - zipcode
* - git_repository
  - [NSAPH/data_requests](https://github.com/NSAPH/data_requests/blob/master/request_projects/jan2021_whanhee_fisrt_hosps/code/1_create_indivdual_vars.R)
* - files
  -
```
```
   ├── follow_up_year_2000.fst
   ├── ...
   └── follow_up_year_2016.fst
```
`````

### Temperature Humidity Precipitation 
`````{dropdown} **temperature_seasonal_zipcode**
```{list-table}
:header-rows: 0
* - rce_location
  - `/nfs/nsaph_ci3/ci3_confounders/data_for_analysis/earth_engine/ temperature/temperature_seasonal_zipcode_combined.csv`
* - fasse_location
  - `temperature_seasonal_zipcode`
* - dataset_author
  - Xiao Wu, Ben Sabath
* - date_created
  - Jul 23,  2020
* - data_source
   - Google Earth Engine provides a single interface for interacting with a number of geospatial data sources. The sources used and links to their documentation are: [GRIDMET](https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_GRIDMET), [NLDAS](https://developers.google.com/earth-engine/datasets/catalog/NASA_NLDAS_FORA0125_H002), [MODIS MOD10A1.006](https://developers.google.com/earth-engine/datasets/catalog/MODIS_006_MOD10A1), [GLDAS](https://developers.google.com/earth-engine/datasets/catalog/NASA_GLDAS_V021_NOAH_G025_T3H), [NOAA CDR PATMOSX](https://developers.google.com/earth-engine/datasets/catalog/NOAA_CDR_PATMOSX_V53), [NOAA NCEP Climate Forecast System V2](https://developers.google.com/earth-engine/datasets/catalog/NOAA_CFSV2_FOR6H)
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 1999-2019
* - temporal_resolution
  - annually
* - description
  - This dataset contains information on temperature, relative humidity, and total precipitation data. The data is available as raster files on Google earth engine. The temporal and spatial resolutions varied by data source, but all were available at a daily resolution or more frequently. Where the time resolution of the rasters is more than daily, daily averages for each raster were calculated. Next, using Google earth engine's spatial averaging algorithms and a set of polygons representing the areas of interest, the daily value for each polygon was calculated. The polygons used were the ones described in the preceding section. The results of this calculation were then downloaded as a csv file to the RCE. At this point, there is one file for each year. Following this, annual averages are calculated for each location, and these are combined in to a single file. The daily values are also combined in to a single file. For the `combined_zips` files (which combine the zip code polygon based measures with the the point based estimates to address zip codes without area) there is an additional step. Values for zip codes not in the polygon based measure are taken from the point based measures to address the ~7000 zip codes without area that are missing from the polygon shape file.
* - git_repository 
  - [NSAPH/data_documentation](https://github.com/NSAPH/data_documentation/blob/master/earth_engine_docs/earth_engine_data.Rmd)
* - meterological
  - Temperature (K) - variable name: tmmx (Source: GRIDMET); Relative Humidity - variable name: rmax (Source: GRIDMET)
* - size
  - 65 MB
* - header 
  - `ZIP,year,summer_tmmx,summer_rmax,winter_tmmx,winter_rmax`
* - files
  -
```
```
   └── temperature_seasonal_zipcode_combined.csv
```
`````

### Pollution-Census-Temperature covariates
`````{dropdown} **merged_covariates_pm_census_temp**
```{list-table}
:header-rows: 0
* - data_source
  - US Census/ACS, Business Analyst Data Set, BRFSS
* - rce_location
  - `/nfs/nsaph_ci3/ci3_health_data/medicare/ mortality/1999_2016/wu/output_data /merged_covariates.csv`
* - fasse_location
  - `merged_covariates_pm_census_temp`
* - dataset_author
  - Xiao Wu, Ben Sabath
* - date_created
  - May 29, 2019
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - publication 
  - https://www.science.org/doi/10.1126/sciadv.aba5692
* - git_repository 
  - [nejm_confounder_summary/nejm_confounder](https://github.com/NSAPH/data_documentation/blob/master/nejm_confounder_summary/nejm_confounders.csv) and [rce_data_list/confounder_data](https://github.com/NSAPH/data_documentation/blob/master/rce_data_list/confounder_data.csv)
* - size
  - 296 MB
* - header 
  - `zip, year, pm25_ensemble, pm25_no_interp, pm25_nn, ozone, ozone_no_interp, zcta, poverty, popdensity, medianhousevalue, pct_blk, medhouseholdincome, pct_owner_occ, hispanic, education, population, zcta_no_interp, poverty_no_interp, popdensity_no_interp, medianhousevalue_no_interp, pct_blk_no_interp, medhouseholdincome_no_interp, pct_owner_occ_no_interp, hispanic_no_interp, education_no_interp, population_no_interp, smoke_rate, mean_bmi, smoke_rate_no_interp, mean_bmi_no_interp, amb_visit_pct, a1c_exm_pct, amb_visit_pct_no_interp, a1c_exm_pct_no_interp, tmmx, rmax, pr, cluster_cat, fips, fips_no_interp`
* - files
  - 
```
```
   └── merged_covariates.csv
```
`````

### Population-Weighted Daily County-Level Heat Metrics
`````{dropdown} **county_heat_metrics**
```{list-table}
:header-rows: 0
* - data_source
  - ERA5-Land gridded data
* - fasse_location
  - `heatvars_county_2000-2020`
* - dataset_author
  - Keith Spangler
* - date_created
  - June 17, 2022
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - county
* - temporal_coverage
  - 2000-2020
* - temporal_resolution
  - daily
* - publication 
  - https://pubmed.ncbi.nlm.nih.gov/35715416/
* - size
  - 1.03 GB
* - header 
  - `"StCoFIPS", "Date", "Tmin_C", "Tmax_C", "Tmean_C", "TDmin_C", "TDmax_C", "TDmean_C", "NETmin_C", "NETmax_C", "NETmean_C", "HImin_C", "HImax_C", "HImean_C", "HXmin_C", "HXmax_C", "HXmean_C", "WBGTmin_C", "WBGTmax_C", "WBGTmean_C", "UTCImin_C", "UTCImax_C", "UTCImean_C", "Flag_T", "Flag_TD", "Flag_NET", "Flag_HI", "Flag_HX", "Flag_WBGT", "Flag_UTCI"`
* - files
  - 
```
```
   └── Heatvars_County_2000-2020_v1.2.Rds
```
`````

### Medicaid - Respiratory Hospitalizations in Children
`````{dropdown} **medicaid_children_99-12**
```{list-table}
:header-rows: 0
* - data_source
  - Medicaid
* - rce_location
  - `/nfs/nsaph_ci3/ci3_health_data/medicaid/respiratory /1999_2012/youth_resp_hosps_jlee/data`
* - fasse_location
  - `medicaid_children_99-12`
* - dataset_author
  - Jenny Lee
* - date_created
  - 2021
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 1999-2012
* - temporal_resolution
  - annually
* - description
  - The data prepared for this project consists of the Medicaid Fee For Service population, with unrestricted Medicaid benefits, under the age of 20 from 1999-2012. This data also includes all hospitalizations for that population, with indicators included regarding whether or not they were associated with a set of respiratory hospitalizations. See the schema for the hospitalization data below for details on specific indicators.
* - git_repository 
  - [NSAPH/data_requests](https://github.com/NSAPH/data_requests/tree/master/request_projects/feb2021_jenny_medicaid_resp)
* - exposures
  - Xiao Wu's CausalGPS PM2.5 data 
* - size
  - 14 GB
* - files
  -
``` 
```
├── denom
│   ├── denom_under_20_1999.fst
│   ├── ...
│   └── denom_under_20_2012.fst
└── hosps
    ├── under_20_admissions_1999.fst
    ├── ...
    └── under_20_admissions_2012.fst
```
`````

### Exposure-census-BRFFS confounders
`````{dropdown} **confounders** 
```{list-table} 
:header-rows: 0
* - data_source
  - US Census, BRFSS
* - rce_location
  - `/nfs/nsaph_ci3/scratch/jan2021_whanhee_cache/cache_dir/ merged_exposure_confounders/`
* - fasse_location
  - `confounders`
* - dataset_author
  - Ben Sabath, Whanhee Lee
* - date_created
  - Apr 23, 2021
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - zipcode, zcta
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - git_repository
  - [data_requests](https://github.com/NSAPH/data_requests/blob/master/request_projects/jan2021_whanhee_fisrt_hosps/code/6_join_exposure_to_confounders.R)
* - size
  - 247 MB
* - header 
  - `ZIP, year, zcta, poverty, popdensity, medianhousevalue, pct_blk, medhouseholdincome, pct_owner_occ, hispanic, education, population, pct_asian, pct_native, pct_white, smoke_rate, mean_bmi, pm25.current_year, ozone.current_year, no2.current_year, ozone_summer.current_year, pm25.one_year_lag, ozone.one_year_lag, no2.one_year_lag, ozone_summer.one_year_lag`
* - files
  - 
```
```
   ├── merged_confounders_2000.csv
   ├── ...
   └── merged_confounders_2016.csv
```
`````

### ADRD Hospitalization Records
`````{dropdown} **adrd_hospitalization**
```{list-table}
:header-rows: 0
* - dataset_author
  - Shuxin Dong
* - date_created
  - Jan 27, 2022
* - data_source
  - MedPar (admissions)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode (unaggregated)
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - daily (with admission date)
* - description
  - extract the ADRD hospitalizations based on the Chronic Condition Warehouse
* - rce_location
  - `~/shared_space/ci3_analysis/ data_ADRDhospitalization/ ADRDhospitalization_CCWlist/`
* - fasse_location
  - `adrd_hospitalization`
* - size
  - 1.9 GB
* - git_repository
  - https://github.com/ShuxinD/ADRDdata
* - other
  - The Chronic Condition Warehouse list for ADRD: https://www2.ccwdata.org/web/guest/condition-categories
* - files
  -
```
```
   ├── ADRD_2000.fst
   ├── ...
   └── ADRD_2016.fst
```
````{dropdown} header
```
QID           : chr 
ADATE         : Date
DDATE         : Date
zipcode_R     : int 
DIAG1         : chr 
DIAG2         : chr 
DIAG3         : chr 
DIAG4         : chr 
DIAG5         : chr 
DIAG6         : chr 
DIAG7         : chr 
DIAG8         : chr 
DIAG9         : chr 
DIAG10        : chr 
AGE           : int 
Sex_gp        : chr 
Race_gp       : chr 
SSA_STATE_CD  : int 
SSA_CNTY_CD   : int 
PROV_NUM      : int 
ADM_SOURCE    : chr 
ADM_TYPE      : int 
Dual          : int 
year          : num 
AD_primary    : logi
AD_any        : logi
AD_secondary  : logi
ADRD_primary  : logi
ADRD_any      : logi
ADRD_secondary: logi
```
````
`````

### Medpar File 2000-2016 Clean 
`````{dropdown} **medpar_hospital_clean_0619**
```{list-table}
:header-rows: 0
* - dataset_author
  - Mahdieh Danesh Yazdi
* - date_created
  - May 2019
* - data_source
  - MedPar (admissions)
* - spatial_coverage
  - US
* - size
  - 1.8 GB
* - spatial_resolution
  - zipcode, city
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - admissions date
* - processing_description
  - The data was limited to the years 2000-2016 (1999 was dropped). Demographic data was removed (use demographic data from denominator file). Duplicated admission records were removed. For multiple admissions on the same day, the longer length of stay was kept and those without missing diagnositic codes. Subset data to keep only first two diagnostic codes. A diabetes varible was created (would review ICD codes used clinically prior to use). 
* - rce_location
  - `~/shared_space/ci3_mdaneshyazdi/Medpar_Data/ data/medpar_hospital_clean_0619.rds`
* - fasse_location
  - `medpar_hospital_clean_0619`
* - files
  -
```
```
   └── medpar_hospital_clean_0619.rds
```
`````

### Denominator File 2000-2016 Clean 
`````{dropdown} **denominator_clean_0619**
```{list-table}
:header-rows: 0
* - dataset_author
  - Mahdieh Danesh Yazdi
* - date_created
  - May 2019
* - data_source
  - MBSF (denominator)
* - spatial_coverage
  - US
* - size
  - 3.8 GB
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - processing_description
  - The data was limited to the years 2000-2016 (1999 was dropped). Rows with empty or missing QID values were dropped. Those whose sex changed through follow up were dropped. Those whose race changed through follow up were assigned "Other/Unknown" category. Those who had multiple dates of death in different years were dropped. For those with multiple dates of death in the same year, earlier date of death was assigned. If duplicate rows existed, one with date of death and one without, the row with non-missing date of death was kept. Multiple QID-year rows with differing values of other variables were removed. Observations with invalid zip codes were removed. Warning: There may be excess deaths on the last day of the month due to CMS processing. Sometimes when the exact date of death is unknown, it is assigned to the last day of the month.
* - rce_location
  - `~/shared_space/ci3_mdaneshyazdi/Denominator_Data/ data/denominator_clean_0619.rds`
* - fasse_location
  - `denominator_clean_0619`
* - files
  -
```
```
   └── denominator_clean_0619.rds
```
`````

### Denominator Clean Merged with Exposure and Covariate Data 
`````{dropdown} **merged_denominator_clean_0619_exp_conf**
```{list-table}
:header-rows: 0
* - dataset_author
  - Mahdieh Danesh Yazdi
* - date_created
  - February 2020
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - size
  - 30 GB (`fst`) and 4.4 GB (`rds`)
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  -  annually
* - description
  - The clean denominator file merged with annual PM2.5, NO2, O3 levels from 1-km exposure models generated by Qian Di and Weeberb Requia aggregatetd to zip code level by Yaguang Wei. Also merged with covariate data from the Census, ACS, BRFSS, and Dartmouth Health Atlas created by Ben Sabath. Missing values were filled in using interpolated/extrapolated values from Liuhua Shi. (Negative values were set to 0 and values greater than 100% were set to 100%). Other missing values were dropped. The exposure values and covariate data may need to updated depending on study being done.  
* - rce_location
  - `~/shared_space/ci3_mdaneshyazdi/ Merged_Data/data/denominator.rds` and `~/shared_space/ci3_mdaneshyazdi/ Merged Data/denominator.fst`
* - fasse_location
  - `merged_denominator_clean_0619_exp_conf`
* - files
  -
```
```
   ├── denominator.rds
   └── denominator.fst
```
`````

### Hospital Admissions Merged with Denominator, Exposure, and Covariates
`````{dropdown} **national_exp_0621**
```{list-table}
:header-rows: 0
* - dataset_author
  - Mahdieh Danesh Yazdi
* - date_created
  - Jun 2021
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - The clean denominator file merged with the clean hospital admissions data, limited to FFS patients, and then merged with annual PM2.5, NO2, O3 levels and Warm-season O3 levels from 1-km exposure models generated by Qian Di and Weeberb Requia aggregatetd to zip code level by Yaguang Wei. Also merged with covariate data from the Census, ACS, BRFSS, and Dartmouth Health Atlas created by Ben Sabath. Missing values were filled in using interpolated/extrapolated values from Liuhua Shi. (Negative values were set to 0 and values greater than 100% were set to 100%). Other missing values were dropped. The exposure values and covariate data may need to updated depending on study being done. Individuals may have multiple admissions per year. 
* - size
  - 32 GB
* - rce_location
  - `~/shared_space/ci3_mdaneshyazdi/ Merged_Data/data/national_exp_0621.fst`
* - fasse_location
  - `national_exp_0621`
* - files
  -
```
```
   └── national_exp_0621.fst
```
`````


### Aggregated 2010-2016 Medicare Mortality Data with PM2.5 Exposure and ZIP code level variables
`````{dropdown} **aggregate_medicare_data_2010to2016**
```{list-table}
:header-rows: 0
* - description
  - This data contain (annually aggregated) exposure to PM2.5 data, demographic data from census and mortality data + individual level characteristics for the entire Medicare population in 1999-2016. See [Xiao’s paper](https://www.science.org/doi/10.1126/sciadv.aba5692) for processing description. 
* - dataset_author
  - Xiao Wu, Ben Sabath
* - date_created
  - 2020
* - data_source
  - Medicaid, Exposure Data, Census Data
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2010-2016
* - temporal_resolution
  - Annually
* - publication
  - https://www.science.org/doi/10.1126/sciadv.aba5692
* - rce_location
  - `~shared_space/ci3_analysis/causal_rule_ensemble /aggregate_medicare_data_2010to2016.fst`
* - fasse_location
  - `aggregate_medicare_data_2010to2016`
* - git_repository
  - https://github.com/wxwx1993/National_Causal
* - files
  -
```
```
   └── aggregate_medicare_data_2010to2016.fst
```
`````

### Nationwide Medicare Strata

`````{dropdown} **erc_strata**
```{list-table}
:header-rows: 0
* - dataset_author
  - Kevin Josey
* - date_created
  - Aug 5 2022
* - data_source
  - Medicare File from Xiao et al.'s Science Advances paper (see `denom_by_year`)
* - spatial_coverage
  - contiguous US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annual
* - description
  - Data were divided and aggregated into custom strata, then subsetted depending on several individual factors. I further merged these data tables with neighborhood level covariates.
* - rce_location
  - `~/shared_space/ci3_analysis/josey_erc_strata/Data`
* - fasse_location
  - `erc_strata`
* - git_repository
  - https://github.com/kevjosey/erc-strata
* - size
  - 6.9 GB
* - files
  -
```
```
├── aggregate_data_qd.RData
├── aggregate_data_rm.RData
├── national_merged2016_qd.RData
├── national_merged2016_rm.RData
├── qd
│   ├── 0_all_qd.RData
│   ├── 0_asian_qd.RData
│   ├── 0_black_qd.RData
│   ├── 0_hispanic_qd.RData
│   ├── 0_white_qd.RData
│   ├── 1_all_qd.RData
│   ├── 1_asian_qd.RData
│   ├── 1_black_qd.RData
│   ├── 1_hispanic_qd.RData
│   ├── 1_white_qd.RData
│   ├── 2_all_qd.RData
│   ├── 2_asian_qd.RData
│   ├── 2_black_qd.RData
│   ├── 2_hispanic_qd.RData
│   └── 2_white_qd.RData
└── rm
    ├── 0_all_rm.RData
    ├── 0_asian_rm.RData
    ├── 0_black_rm.RData
    ├── 0_hispanic_rm.RData
    ├── 0_white_rm.RData
    ├── 1_all_rm.RData
    ├── 1_asian_rm.RData
    ├── 1_black_rm.RData
    ├── 1_hispanic_rm.RData
    ├── 1_white_rm.RData
    ├── 2_all_rm.RData
    ├── 2_asian_rm.RData
    ├── 2_black_rm.RData
    ├── 2_hispanic_rm.RData
    └── 2_white_rm.RData
```
`````

### CVD Medicaid 

`````{dropdown} **cvd_medicaid**
```{list-table}
:header-rows: 0
* - dataset_author 
  - Ben Sabath  
* - date_created
  - January 28, 2020
* - data_source
  - Medicaid 
* - spatial_coverage
  - US (continental) 
* - spatial_resolution
  - zipcode 
* - temporal_coverage
  - 2002-2012
* - temporal_resolution
  - daily
* - size
  - 86 GB
* - git_repository
  - [dec2019_medicaid_platform_cvd](https://github.com/NSAPH/data_requests/tree/master/request_projects/dec2019_medicaid_platform_cvd)
* - rce_location
  - `~/shared_space/ci3_health_data /medicaid/cvd/2010_2011/desouza-2`
* - fasse_location
  - `cvd_medicaid`
* - publication
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7896354/
* - files
  -
```
```
├── [2.3G]  cvd.csv
├── [2.1G]  cvd.sas7bdat
├── [6.3K]  CVD-specific data dictionary-07-12-2018.docx
├── [6.8K]  data_dictionary.md
├── [ 70G]  merged_cvd_data.csv
├── [ 18K]  merge.out
│   ├── [5.7K]  log.txt
│   ├── [  77]  r_error.0
│   └── [ 12K]  r_out.0
├── [1.7K]  merge.R
├── [ 906]  readme
└── [ 899]  r.submit
```
`````


### Aggregated CVD cohort Medicare

`````{dropdown} **aggregated_cvd_cohort_medicare**
```{list-table}
:header-rows: 0
* - dataset_author
  - Jochem Klompmaker
* - date_created
  - April 2022
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - Denominator file linked with hospitalization data and merged with confounders and exposures (NO2, PM2.5, ozone, temperature, humidity). Person records were aggregated by zip code, year and individual demographics
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/gen_admission /1999_2016/Klompmaker/merged_data/cvd2/`
* - fasse_location
  - `aggregated_cvd_cohort_medicare`
* - size
  - 38 GB
* - files
  -
```
```
├── [4.2G]  aggregate_CVD_65yrs.fst
├── [3.8G]  aggregate_CVD_75yrs.fst
├── [3.1G]  aggregate_CVD_85yrs.fst
├── [6.5G]  aggregate_CVD.fst
├── [4.8G]  aggregate_death_CVD.fst
├── [4.6G]  aggregate__excl_1yrhosp_CVD.fst
├── [4.3G]  aggregate_excl_1yrhosp_RES.fst
├── [1.2M]  cc_zipyear_all.fst
├── [1.2M]  cc_zipyear_confounder.fst
├── [941K]  cc_zipyear_cvd.fst
├── [347M]  CVD_count.fst
├── [354M]  CVD_death_count.fst
├── [439M]  time_count.fst
└── [439M]  time_death_count.fst
```
`````

### Aggregated CHD cohort Medicare

`````{dropdown} **aggregated_chd_cohort_medicare**
```{list-table}
:header-rows: 0
* - dataset_author
  - Jochem Klompmaker
* - date_created
  - April 2022
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - Denominator file linked with hospitalization data and merged with confounders and exposures (NO2, PM2.5, ozone, temperature, humidity). Person records were aggregated by zip code, year and individual demographics
* - rce_location
  - `~/shared_space/ci3_health_data/medicare /gen_admission /1999_2016/Klompmaker/merged_data/chd2/`
* - fasse_location
  - `aggregated_chd_cohort_medicare`
* - size
  - 35 GB
* - files
  -
```
```
├── [4.1G]  aggregate_CHD_65yrs.fst
├── [3.8G]  aggregate_CHD_75yrs.fst
├── [3.2G]  aggregate_CHD_85yrs.fst
├── [ 14G]  aggregate_CHD.fst
├── [4.3G]  aggregate_excl_1yrhosp_CHD.fst
├── [1.2M]  cc_zipyear_chd.fst
├── [ 92M]  CHD_count.fst
└── [116M]  time_count.fst
```
`````

### Aggregated CBV cohort Medicare

`````{dropdown} **aggregated_cbv_cohort_medicare**
```{list-table}
:header-rows: 0
* - dataset_author
  - Jochem Klompmaker
* - date_created
  - April 2022
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - Denominator file linked with hospitalization data and merged with confounders and exposures (NO2, PM2.5, ozone, temperature, humidity). Person records were aggregated by zip code, year and individual demographics
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/gen_admission /1999_2016/Klompmaker/merged_data/cbv2/`
* - fasse_location
  - `aggregated_cbv_cohort_medicare`
* - size
  - 35 GB
* - files
  -
```
```
├── [4.1G]  aggregate_CBV_65yrs.fst
├── [3.8G]  aggregate_CBV_75yrs.fst
├── [3.2G]  aggregate_CBV_85yrs.fst
├── [ 14G]  aggregate_CBV.fst
├── [4.4G]  aggregate__excl_1yrhosp_CBV.fst
├── [ 93M]  CBV_count.fst
├── [1.2M]  cc_zipyear_cbv.fst
└── [117M]  time_count.fst
```
`````


### Aggregated ADRD cohort Medicare

`````{dropdown} **aggregated_adrd_cohort_medicare**
```{list-table}
:header-rows: 0
* - dataset_author
  - Jochem Klompmaker
* - date_created
  - February 2022
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - Denominator file linked with hospitalization data and merged with confounders and exposures (NDVI, blue space, park cover, NO2, PM2.5, ozone, temperature, humidity). Person records were aggregated by zip code, year and individual demographics
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/gen_admission /1999_2016/Klompmaker/merged_data/alz2/`
* - fasse_location
  - `aggregated_adrd_cohort_medicare`
* - size
  - 28 GB
* - files
  -
```
```
├── [3.6G]  aggregate_ALZ_65yrs.fst
├── [3.4G]  aggregate_ALZ_75yrs.fst
├── [2.8G]  aggregate_ALZ_85yrs.fst
├── [4.5G]  aggregate_ALZ.fst
├── [4.4G]  aggregate_death_ALZ.fst
├── [3.8G]  aggregate_excl_1yrhosp_ALZ.fst
├── [358M]  ALZ_count.fst
├── [387M]  ALZ_death_count.fst
├── [471M]  time_count.fst
└── [472M]  time_death_count.fst
```
`````

### Aggregated PD cohort Medicare


`````{dropdown} **aggregated_pd_cohort_medicare**
```{list-table}
:header-rows: 0
* - dataset_author
  - Jochem Klompmaker
* - date_created
  - February 2022
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - description
  - Denominator file linked with hospitalization data and merged with confounders and exposures (NDVI, blue space, park cover, NO2, PM2.5, ozone, temperature, humidity). Person records were aggregated by zip code, year and individual demographics.
* - rce_location
  - `~/shared_space/ci3_health_data/medicare /gen_admission/1999_2016 /Klompmaker/merged_data/par2/`
* - fasse_location
  - `aggregated_pd_cohort_medicare`
* - size
  - 29 GB
* - files
  -
```
```
├── [4.4G]  aggregate_death_PAR.fst
├── [4.4G]  aggregate_excl_1yrhosp_PAR.fst
├── [3.7G]  aggregate_PAR_65yrs.fst
├── [3.4G]  aggregate_PAR_75yrs.fst
├── [2.9G]  aggregate_PAR_85yrs.fst
├── [4.6G]  aggregate_PAR.fst
├── [ 94M]  PAR_count.fst
├── [405M]  PAR_death_count.fst
├── [222M]  time_count.fst
└── [486M]  time_death_count.fst
```
`````

### Daily County Level Heatwave Associated Hospitalizations

`````{dropdown} **daily_county_level_heatwave_assosciated_hospitalizations**
```{list-table}
:header-rows: 0
* - dataset_author
  - Ben Sabath
* - date_created
  - July 10, 2020
* - size
  - 7.7 GB
* - data_source
  - MedPar (admissions), MBSF (denominator), Medicaid MAX
* - spatial_coverage
  - US
* - spatial_resolution
  - county
* - temporal_coverage
  - 2006-2016, 1999-2016
* - temporal_resolution
  - daily
* - description
  - FIPS code, race, sex, age, and dual eligibility were determined for each case based on the information in the patient summary file for that individual in the year of their admission. The denominator for each observation is calculated monthly and contains all individuals who are eligible for Fee for Service (FFS) hospitalization coverage and have not died prior to that month. The CCS codes included were 2, 50, 55, 114, 157, 159, and 244. ICD processing done using the ICD package(Wasey 2018). The author of this package asks that it be cited in papers using data that was created using the package.
* - rce_location
  - `~/shared_space/ci3_health_data/medicare/heat_related`
* - fasse_location
  - `daily_county_level_heatwave_assosciated_hospitalizations`
* - publication
  - https://arxiv.org/abs/2102.10478
* - git_repository
  - [https://github.com/wxwx1993/TS_Stochastic](https://github.com/wxwx1993/TS_Stochastic)
* - files
  -
```
```
├── 1999_2016
│   └── county_ccs_hosps
│       ├── cache_dir
│       │   ├── daily_counts
│       │   │   ├── daily_counts_by_ccs_1999.fst
│       │   │   ├── ...
│       │   │   └── daily_counts_by_ccs_2016.fst
│       │   └── denom
│       │       ├── ffs_patient_summary_by_county_1999.fst
│       │       ├── ...
│       │       └── ffs_patient_summary_by_county_2016.fst
│       ├── data
│       │   ├── daily_ccs_heatwave_counts_by_fips_1999.fst
│       │   ├── ...
│       │   └── daily_ccs_heatwave_counts_by_fips_2016.fst
│       └── data_daily_hosp_mort
│           ├── daily_only_ccs_heatwave_hosp_mort_counts_by_fips_1999.fst
│           ├── ...
│           └── daily_only_ccs_heatwave_hosp_mort_counts_by_fips_2016.fst
└── 2006_2016
    └── county_ccs_hosps
        ├── cache_dir
        │   ├── daily_counts
        │   │   ├── daily_counts_by_ccs_2006.fst
        │   │   ├── ...
        │   │   └── daily_counts_by_ccs_2016.fst
        │   └── denom
        │       ├── ffs_patient_summary_by_county_2006.fst
        │       ├── ...
        │       └── ffs_patient_summary_by_county_2016.fst
        ├── data
        │   ├── daily_ccs_heatwave_counts_by_fips_2006.fst
        │   ├── ...
        │   ├── daily_ccs_heatwave_counts_by_fips_2016.fst
        │   ├── Daily_Heat_CCS_2006-2016_with_Temperature_by_WFO.Rda
        │   ├── Daily_Heat_CCS_2006-2016_with_Temperature_by_WFO_v0.Rda
        │   ├── Daily_Heat_CCS_2006-2016_with_Temperature_ERA5Land.Rda
        │   ├── Daily_Heat_CCS_2006-2016_with_Temperature.Rda
        │   └── Daily_Heat_CCS_2006-2016_with_Temperature_v0.Rda
        ├── readme.md
        └── schema.yml
```
`````


### Hospitalizations for kidney disease and comorbidities

`````{dropdown} **medicare_for_kidney_diseases**
```{list-table}
:header-rows: 0
* - dataset_author
  - Ana Trisovic
* - date_created
  - July 10, 2022
* - data_source
  - MedPar (admissions), MBSF (denominator), confounders
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - annually
* - git_repository
  - [mbsf-medpar-aki-first-hospitalization](https://github.com/NSAPH-Data-Processing/mbsf-medpar-aki-first-hospitalization)
* - description
  - Special modifications for the kidney diseases for numerators and denominators (people at risk) for the analysis by Whanhee Lee. 
* - rce_location
  - `~/shared_space/ci3_analysis/whanhee_revisions`
* - fasse_location
  - `medicare_for_kidney_diseases`
* - size
  - 31 GB
* - header
  - `year, sex, race, zip, dual, follow_up, entry_age_group, aki_primary_secondary_first_hosp, aki_primary_secondary_first_hosp_denom, ckdhosp_prior_aki, ckdhosp_prior_aki_denom, diabeteshosp_prior_aki, diabeteshosp_prior_aki_denom, diabetes_primary_aki_secondary_first_hosp, diabetes_primary_aki_secondary_first_hosp_denom, csd_primary_aki_secondary_first_hosp, csd_primary_aki_secondary_first_hosp_denom, ihd_primary_aki_secondary_first_hosp, ihd_primary_aki_secondary_first_hosp_denom, pneumonia_primary_aki_secondary_first_hosp, pneumonia_primary_aki_secondary_first_hosp_denom, hf_primary_aki_secondary_first_hosp, hf_primary_aki_secondary_first_hosp_denom, ami_primary_aki_secondary_first_hosp, ami_primary_aki_secondary_first_hosp_denom, cerd_primary_aki_secondary_first_hosp, cerd_primary_aki_secondary_first_hosp_denom, uti_primary_aki_secondary_first_hosp, uti_primary_aki_secondary_first_hosp_denom, zcta, poverty, popdensity, medianhousevalue, pct_blk, medhouseholdincome, pct_owner_occ, hispanic, education, population, pct_asian, pct_native, pct_white, smoke_rate, mean_bmi, pm25.current_year, ozone.current_year, no2.current_year, ozone_summer.current_year, pm25.one_year_lag, ozone.one_year_lag, no2.one_year_lag, ozone_summer.one_year_lag`
* - files
  -
```
```
└── [ 27G]  final.csv
```
`````

### IHD medicare hospitalizations (2005)

`````{dropdown} **ihd_medicare_hosp_2005**
```{list-table}
:header-rows: 0
* - dataset_name
  - IHD medicare hospitalizations (2005)
* - dataset_author
  - Cory Zigler
* - date_created
  - Oct 4 2018
* - data_source
  - MedPar (admissions)
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2005
* - temporal_resolution
  - annually
* - size
  - 234 MB
* - rce_location
  - `~/shared_space/ci3_analysis/ zigler_lab/projects/ BipartiteInterference_GPS/ BipartiteInterference_GPS/ Data`
* - fasse_location
  - `ihd_medicare_hosp_2005`
* - files
  -
```
```
├── [4.8K]  00Tree.html
├── [348K]  AnnualFacilityData.Rda
├── [773K]  AnnualUnitData.Rda
├── [ 12K]  Create Analysis Data.R
├── [6.4K]  Create HyADS Adjacency Matrix.R
├── [9.3K]  Create Power Plant Data.R
├── [5.8K]  Create Zip Code Data.R
├── [ 10M]  data_nomed.Rda
├── [ 31K]  facilities_for_analysis.Rda
├── [ 53M]  HyADSmat.Rda
├── [108M]  HyADSmat_replaced20191212.Rda
├── [3.1M]  MonthlyFacilityData.Rda
├── [9.7M]  MonthlyUnitData.Rda
├── [ 11M]  out.zip_pp.rda
├── [ 114]  Readme
├── [5.6M]  ZipcodeData.Rda
└── [ 89K]  zips_included.rda
```
`````

### Daily Florida Hospitalization Counts by Zip

`````{dropdown} **daily-florida-hosp-counts-zip**
```{list-table}
:header-rows: 0
* - dataset_author
  - Ben Sabath, Kate Burrows
* - date_created
  - February 07 2020
* - data_source
  - MedPar (admissions), MBSF (denominator)
* - spatial_coverage
  - Florida
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 1999-2016
* - temporal_resolution
  - daily
* - processing_description
  - Denominator file linked with hospitalization data. This is the raw unprocessed data.
* - size
  - 2.1 GB
* - rce_location
  - `~/shared_space/ci3_health_data /medicare/gen_admission /1999_2016/burrows/cache_data`
* - fasse_location
  - `daily-florida-hosp-counts-zip`
* - files
  -
```
```
├── [308K]  Burrows_DataRequest_September2019.pdf
├── [ 19M]  death_count
│   ├── [1.0M]  death_count_1999.fst
│   ├── [1.0M]  ...
│   └── [1.2M]  death_count_2016.fst
├── [104M]  hosp_count
│   ├── [5.5M]  hosp_count_1999.fst
│   ├── [5.6M]  ...
│   └── [5.2M]  hosp_count_2016.fst
├── [1.6G]  merged_data
│   ├── [ 86M]  daily_zips_1999.fst
│   ├── [106M]  ...
│   └── [106M]  daily_zips_2016.fst
└── [7.2M]  zip_denom
    ├── [382K]  zip_denom_1999.fst
    ├── [440K]  ...
    └── [450K]  zip_denom_2016.fst
```
`````

### Coal PM2.5 Source Impacts

`````{dropdown} **coal_exposure_pm25**
```{list-table}
:header-rows: 0
* - dataset_author
  - Lucas Henneman
* - date_created
  - Sep 14, 2022
* - data_source
  - HyADS exposure modeling
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 1999-2020
* - temporal_resolution
  - annually
* - rce_location
  - `/nfs/home/H/henneman /shared_space/ci3_nsaph/ LucasH/disperseR/ main/output/ zips_model.lm.cv_single_poly`
* - fasse_location
  - `coal_exposure_pm25`
* - GitHub repository/directory on how the data was processed
  - https://github.com/lhenneman/coal_unit_PM25
* - exposures
  - This was created with the HyADS model using emissions from EPA's CAMD database.
* - meterological
  - NOAA/NCAR reanalysis data.
* - size
  - 6.3 GB
* - files
  -
```
```
├── [300M]  zips_pm25_byunit_1999.fst
├── [291M]  ...
├── [134M]  zips_pm25_byunit_2020.fst
├── [599K]  zips_pm25_total_1999.fst
├── [599K]  ...
└── [599K]  zips_pm25_total_2020.fst
```
`````

### Aggregated 2000-2016 Medicare Mortality Data with PM2.5 Exposure by ZIP code

`````{dropdown} **aggregated_2000-2016_medicare_mortality_pm25_zip**
```{list-table}
:header-rows: 0
* - dataset_author
  - Xiao Wu, Ben Sabath
* - date_created
  - 2020
* - data_source
  - Medicaid, Exposure Data, Census Data
* - spatial_coverage
  - US
* - spatial_resolution
  - zipcode
* - temporal_coverage
  - 2000-2016
* - temporal_resolution
  - Annually
* - processing_description
  - See [Xiao’s paper](https://www.science.org/doi/10.1126/sciadv.aba5692) for processing description.
* - rce_location
  - `~/shared_space/ci3_mic6949/ input_data/aggregate_data.RDS`
* - fasse_location
  - `aggregated_2000-2016_medicare_mortality_pm25_zip`
* - publication
  - [Xiao’s paper](https://www.science.org/doi/10.1126/sciadv.aba5692)
* - git_repository
  - [National_Causal](https://github.com/wxwx1993/National_Causal)
* - size
  - 166 MB
* - files
  -
```
```
└── [166M]  aggregate_data.RDS
```
`````
