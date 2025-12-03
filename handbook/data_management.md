# Example of NIH Data Management and Sharing Plan leveraging the Climate-Health CAFE Dataverse Collection

## Data Type

This project utilizes diverse data sources, including health data (e.g., Medicare claims data from the Center of Medicare and Medicaid Services (CMS)), weather and climate data (e.g., meteorological data from gridMET and PRISM), satellite data (e.g., NASA, ESA), environmental exposure data (EPA monitor data), and sociodemographic data (e.g., area-level demographics from the Census and American Community Survey). Data volumes are expected to range from hundreds of gigabytes to tens of terabytes. All research data will be deposited into the Harvard Dataverse, specifically the Climate CAFE Harvard Dataverse collection, to facilitate data preservation and sharing.

Examples of research data sets included in this study are:
- Global and national air pollution exposure data (e.g., PM2.5, NO2, O3, and PM2.5 element concentrations).
- Synthetic health data, including data shared by CMS.
- Claims, cohort, and other human subject health data (details on sharing and access in the "Access, Distribution, or Reuse Considerations" section).

Raw data will undergo cleaning, interpolation, and harmonization. Various data file types and formats will be used, such as tabular (.csv), fst, network Common Data Form (netCDF), txt, and shapefiles.

### Human Subjects

This project includes human subject data collected as secondary data from X (RESEARCHER TO ADD DETAILS)

All final data products will be shared and preserved in an analysis-ready format, allowing for future studies. Metadata, documentation, and standard operating procedures (SOP) for data processing will be shared with each dataset to facilitate interpretation. Harvard Dataverse supports widely used metadata schemas, ensuring compliance with the latest research dissemination standards, including FAIR principles.

## Related Tools, Software, and/or Code

All data will be made available in open file formats such as csv, fst, netCDF, txt, and shapefiles. Due to the large data volume, supercomputing infrastructure like HPC or cloud computing may be necessary for data access and manipulation. The study team will employ free and open-source software (R and Python) for data processing, linkage, and analysis. Additionally, scientific code used in data production will be open-source and publicly shared on software registries (CRAN and PyPI).

## Standards

Data products will adhere to tabular or multidimensional file formats, organized according to predefined data models for structured data. Spatial variables, temporal information, and numerical codes will follow standard formats to ensure machine- and human-readability. GitHub, specifically the Climate-CAFE GitHub organization, will maintain contemporaneous records of data processing details, processing pipelines, and documentation, making them publicly accessible alongside the data on Harvard Dataverse.

## Data Preservation, Access, and Associated Timelines

All data products will be documented and disseminated through the Harvard Dataverse research repository in a dedicated data collection created for this grant. Harvard Dataverse, an NIH-supported repository, ensures data preservation and long-term access. It stores data on Amazon Web Services with backup copies at Amazon Glacier and FAS Research Computing. The repository follows FAIR principles, supports standard metadata schemas (DDI, Dublin Core, schema.org), and provides metadata, persistent identifiers (DOIs), and long-term access. All data products, whether sensitive or not, will be registered and identifiable with a persistent identifier (DOI). Data will be released as open data to the general public as soon as possible.

## Access, Distribution, or Reuse Considerations

Highly sensitive human subjects data cannot be shared due to contractual obligations and IRB requirements. To mitigate this, synthetic health data files will be used when possible, and code for processing these data will be publicly available on GitHub. Sensitive data will only be shared if permitted by the DUA and IRB.

## Oversight of Data Management and Sharing

The following individuals are responsible for overseeing data management, processing, and dissemination activities, as well as updating and revising the Data Management and Sharing Plan when necessary:

- Name of individual (RESEARCHER TO ADD DETAILS)

## Planned Research Outputs

Planned research outputs include:

1. Research data sets deposited into the Harvard Dataverse, publicly available with metadata and documentation, accessible through the Harvard Dataverse Climate CAFE collection.
2. Software workflow tools deposited as free and open-source resources on GitHub within the Climate CAFE collection, ensuring easy accessibility and usability.
