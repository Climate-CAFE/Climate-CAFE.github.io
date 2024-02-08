# Contributing to the Climate-Health CAFÉ Dataverse Collection

This tutorial provides step-by-step instructions on how to upload data to [Dataverse](https://dataverse.harvard.edu/) and select the "Climate Change and Health Research Coordinating Center (CAFE) Collection" organization as the Host Dataverse. Dataverse is a robust platform for sharing, archiving, and collaborating on research data.

To ensure the reproducibility of your data, it's essential to include a link to your GitHub repository in the dataset's description. This link should lead to the pipeline that outlines the process for creating the data. 

![](./imgs/dataverse.png)

## Prerequisites

Before you begin, ensure you have the necessary data files, github links, and information ready for upload.

## Steps

1. **Log In or Create an Account**

   - If you haven't already, visit [Dataverse](https://dataverse.harvard.edu/) and either log in to your existing account or create a new one.

2. **Select "Add Data" in Top Right Corner**

   - From your Dataverse dashboard, click on "Add Data" on the top right side.
   - Under "Host Dataverse," find and select "**Climate Change and Health Research Coordinating Center (CAFE) Collection**" as the organization where you want to upload your data.

3. **Fill in Dataset Information**
Please follow the prompts provided in the Metadata checklist to provide the descriptors required to make your dataset available through Dataverse. Some context-specific instructions have been added to the upload form, and you can additionally find field-specific explanations for each field by hovering your cursor over the question-mark icon next to the entry.
For additional clarity, we have highlighted directions for a few key fields that may be unfamiliar to users:
   -   **Keywords and Controlled Vocabulary**: Add keywords to aid in discoverability. Controlled vocabulary is used to ensure keywords are consistent across different data contributors. NIEHS has established a glossary of keywords that CAFE data contributors are expected to use. Select keywords relevant to your data from the [Climate Change and Human Health Glossary](https://tools.niehs.nih.gov/cchhglossary/). The Controlled Vocabulary Name can be left blank in the metadata, but the glossary link should be included in the URL section. This URL should appear as a default. If you would like to include keywords from another glossary, follow the same procedure using the + button to add new keywords and including the relevant URL for each.
   -   **Geospatial Metadata**. Provide information about the area(s) that your data covers as directed by the checklist prompts.
   -   **Computational Workflow**: Open source processing is a priority for reproducibility. Refer to the [Code Sharing Walkthrough page](https://climate-cafe.github.io/code_sharing_workflow.html) for details on the expectations for processing pipelines. Include a link to your processing pipeline (ie:GitHub) if applicable.
   -   **Metadata About Data Sources**: Include all available information about any raw data source from which the dataset was derived (Select *Yes* from the Derived from Another Dataset option before completing this section).
   -   **Metadata About Geospatial Files**: These details are relevant strictly for spatial file formats. 

4. **Upload Data Files**

   - The last component of the dataset submission involves uploading your data and code (if not using online computational workflow). You can select or upload files, specify their naming, and specify a folder infrastructure if needed. 
   - Click the "Select Files to Add" button to choose files from your local device or drag and drop files into the upload widget. In addition to the metadata specified in this form, a .csv data dictionary describing all variables should be uploaded as a file with your submission.

   - **Note:** Dataverse supports a wide range of file types. Ensure your files are within the specified size limits, and tabular files have their own limitations for ingestion.

6. **Finalize and Edit Metadata**

   - Select *Save Dataset* when all fields are filled and you have added the files you would like to submit. After you have saved your dataset, you can edit the metadata to add additional information by selecting *Edit Dataset*
     
7. **Submit**

   - Once you're satisfied with the dataset and metadata, click the "*Submit for Review*" button.

Congratulations! You've successfully uploaded your data to Dataverse under the "**Climate Change and Health Research Coordinating Center (CAFE) Collection**" organization. Your dataset is now being reviewed for collaboration, sharing, and archiving within the Dataverse platform.
