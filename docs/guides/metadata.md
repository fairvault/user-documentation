---
title: "Metadata overview"
layout: default
nav_order: 2
parent: Guide
permalink: /metadata/
---

# Overview of the full metadata model
[Citation metadata](#citation-metadata)
[Access conditions](#access-conditions)
[Decision Tree](#fairvault-decision-tree)

## Citation metadata

| Metadata field | Description | Tips |
|----|----|----|
| Title | Enter the main title of your dataset.| If your dataset is linked to a publication, you may click *“Replication data for”* below the title field and add the title of your publication. |
| Subtitle | A secondary title that amplifies or states certain limitations on the main title. |  |
| Alternative title | A title that is commonly used to refer to the dataset or an abbreviation of the title. This field can also be used to add a title in another language. | By clicking “+”, you can add multiple titles. |
| Alternative URL | URL outside of FAIRVault where the data of the dataset can also be viewed or accessed, such as a project or personal webpage. | An example can be GitHub/GitLab. |
| Other identifier *(consists of 2 subfields)* | Another unique identifier for the dataset, such as another repository’s identifier. | e.g. accession number in a sequence database <br> By clicking “+”, you can add multiple identifiers. |
| - Agency | The name of the producer or other repository that generated the other identifier. |  |
| - Identifier | Another identifier that uniquely identifies the dataset. |  |
| Author *(consists of 4 subfields)* | The person(s) or organization(s) responsible for creating the data of the dataset. Note that the author names are added to the bibliographic citation in order of entry. | The name and affiliation associated with the account creating the dataset draft will be automatically included as the first Author of the dataset. <br> By clicking “+”, you can add co-authors. |
| - Name | The author’s last name, first name or the name of an organization responsible for creating this dataset. | Use the search function to find (co-) authors with an ORCID. In case they are missing an ORCID, you can add them manually (last name, first name). |
| - Affiliation | The organization with which the author is affiliated. | Use the search function to find the organization with a ROR-id. In case the ROR-id is missing, you can add the affiliation manually. <br> Currently, it is not possible to add multiple affiliations for the same author. |
| - Identifier type | The type of identifier that uniquely identifies the author (e.g., ORCID, ISNI) | This field only appears if you do not use the automated ORCID method listed above. |
| - Identifier | Uniquely identifies the author when paired with an Identifier Type. | This field only appears if you do not use the automated ORCID method listed above. |
| Point of contact *(consists of 3 subfields)* | The person(s) or organization(s) that can be contacted by data users when questions arise. Note that we advise to add (a) person(s) with a more permanent function (e.g. promotor). | By clicking “+”, you can add multiple points of contact. |
| - Name | The contact’s last name, first name or the name of an organization. | The name of the dataset creator in FAIRVault will automatically be added, but this can be changed manually. Best practice is to add the name of a senior scientist (e.g. the promotor). |
| - Affiliation | The organization with which the point of contact is affiliated. | The affiliation of the dataset creator in FAIRVault will automatically be added, but this can be changed manually. Best practice is to add the affiliation of a senior scientist (e.g. the promotor). |
| - E-mail | The email address of the point of contact. This email address will NOT be displayed publicly. A message to the point of contact can only be sent via the “contact owner” button once the dataset is published. | The email address of the dataset creator in FAIRVault will automatically be added, but this can be changed manually. Best practice is to add the email address of a senior scientist (e.g. the promotor). |
| Description *(consists of 2 subfields)* | A short description that summarizes the dataset itself. You can mention what the data include, how they were obtained and what they can be used for. Avoid copying the abstract of your publication. | By clicking “+”, you can add more descriptions. |
| - Text | A summary describing the purpose, nature, and scope of the dataset. | Avoid using special characters and html tags. |
| - Date | The date when the description was added to the dataset. If the dataset contains more than one description, e.g. the data producer supplied one description and the data repository supplied another, this date is used to distinguish between the descriptions. | Add the date following the ISO 8601 standard, i.e. YYYY-MM-DD. |
| Subject | The area of study relevant to the dataset. | Use the drop-down list to choose the subject(s) that best fit(s) your dataset. You can choose multiple. In case none of the subjects fit, choose “other”. |
| Keyword *(consists of 4 subfields)* |  Key terms describing important aspects of the dataset. These keywords will improve the findability of your dataset. | Each keyword needs to be entered separately by clicking “+”. |
| - Term | Key terms describing important aspects of the dataset. | Preferably choose keywords from a controlled vocabulary. For example, the term “Plasmodium vivax”. |
| - Term URI | A URI (Uniform Resource Identifier) that points to the web presence of the keyword term. | For example, for the term “Plasmodium vivax”, you could provide a link to the specific term in the term URI field (https://www.ncbi.nlm.nih.gov/mesh/68010966) |
| - Controlled Vocabulary Name | The controlled vocabulary used for the keyword term, such as LCSH, MeSH or others. | For example, the name “MeSH” in the Controlled Vocabulary Name field |
| - Controlled Vocabulary URL | The URL where one can access information about the term's controlled vocabulary. | For example, a link to the MeSH homepage  (https://www.nlm.nih.gov/mesh/). |
| Topic Classification *(consists of 3 subfields)* | Indicates a broad, important topic or subject that the dataset covers. | By clicking “+”, you can add topic classifications. |
| - Term | Indicates a broad, important topic or subject that the dataset covers. |  |
| - Controlled Vocabulary Name | The controlled vocabulary used for the keyword term, such as LCSH, MeSH or others. |  |
| - Controlled Vocabulary URL | The URL where one can access information about the term's controlled vocabulary. |  |
| Related publication *(consists of 5 subfields)* | Publications that use the data of this dataset. | By clicking “+”, you can add multiple related publications. |
| - Relation type | The nature of the relationship between this dataset and the related publication. | Most frequently, for a dataset supporting a research article or publication, use the “Is Supplement To” relation type. |
| - Citation | The full bibliographic citation for the related publication. | In case your publication is submitted to the journal but not yet accepted, add “submitted for review”. |
| - Identifier type | The type of identifier that uniquely identifies a related publication (e.g. DOI = Digital Object Identifier). | Choose from the drop-down list. |
| - Identifier | The identifier of a related publication. |  |
| - URL | Link to the website where the publication is available (e.g. journal article page). |  |
| Notes | Additional important information about the dataset. |  |
| Language | The language that the dataset's files are written in. | Choose from the drop-down list. |
| Producer *(consists of 5 subfields)* | Person(s) or organization(s) managing the finances or other administrative processes involved in the creation of the dataset. | Think of producers as in the movie industry. <br> By clicking “+”, you can add multiple producers. |
| - Name | The producer’s last name, first name or the name of an organization. |  |
| - Affiliation | The organization with which the producer is affiliated. |  |
| - Abbreviated Name | The producer's abbreviated name. |  |
| - URL | The URL of the producer's website. |  |
| - Logo URL | The URL of the producer's logo. |  |
| Production Date | The date when the data were produced (not distributed, published, or archived). | Add the date following the ISO 8601 standard, i.e. YYYY-MM-DD. |
| Production Location | The location where the data and any related materials were produced or collected. | By clicking “+”, you can add multiple locations. |
| Contributor *(consists of 2 subfields)* | The person(s) or organization(s) responsible for collecting, managing, or otherwise contributing to the development of the dataset. | Note that contributors do not appear in the bibliographic citation. <br> By clicking “+”, you can add multiple contributors. | 
| - Type | Indicates the type of contribution made to the dataset. | Choose from the drop-down list. |
| - Name | The contributor’s last name, first name or the name of an organization. |  |
| Funding Information *(consists of 2 subfields)* | Information about the dataset's financial support. | By clicking “+”, you can add multiple funders. |
| - Agency | The agency that provided financial support for the dataset. | Use the search function to find the funding agency with a ROR-id. In case the ROR-id is missing, you can add the funding agency manually. |
| - Identifier | The grant identifier or contract identifier of the agency that provided financial support for the dataset. |  |
| Distributor *(consists of 5 subfields)* |  Person(s) or organization(s) designated to generate copies of the dataset, including any editions or revisions. |  |
| - Name | The distributor’s last name, first name or the name of an organization. |  |
| - Affiliation | The organization with which the point of contact is affiliated. |  |
| - Abbreviated name | The distributor's abbreviated name. |  |
| - URL | The URL of the distributor's webpage. |  |
| - Logo URL | The URL of the distributor's logo image, used to show the image on the dataset's page. |  |
| Distribution Date | The date when the dataset was made available for distribution/presentation. | Add the date following the ISO 8601 standard, i.e. YYYY-MM-DD. |
| Depositor | Person(s) or organization(s) that deposited the dataset in the repository. | The name of the dataset creator in FAIRVault will automatically be added. We recommend not to manually change this field. | 
| Deposit Date | The date when the dataset was deposited into the repository. | The deposit date field is prefilled in the metadata form when clicking to add a new dataset. The date on which you click to add a new dataset is taken as the prefilled deposit date. Add the date following the ISO 8601 standard, i.e. YYYY-MM-DD. |
| Time Period *(consists of 2 subfields)* | The time period that the data refer to. Also known as span. This is the time period covered by the data, not the dates of coding, collecting data, or making documents machine-readable. | By clicking “+”, you can add multiple time periods. |
| - Start Date | The start date of the time period that the data refer to. |  |
| - End Date | The end date of the time period that the data refer to. |  |
| Date of Collection *(consists of 2 subfields)* | The time period when the data were collected or generated. |  |
| - Start Date | The date when the data collection started. |  |
| - End Date | The date when the data collection ended. |  |
| Data Type | The type of data included in the files. | By clicking “+”, you can add multiple data types. <br> Choose your data type from the drop down menu (compiled data, simulation data, experimental data, aggregated data, survey data, observational data, recorded data, measurement and test data, clinical trial data, genomic data, laboratory notebook, encoded data or geospatial data). | 
| Series *(consists of 2 subfields)* | Information about the dataset series to which the dataset belong. | By clicking “+”, you can add multiple series. |
| - Name | The name of the dataset series. |  |
| - Information | This can include a history of the series and/or a summary of features that apply to the series. |  |
| Software *(consists of 2 subfields)* | Information about the software used to generate the dataset. | By clicking “+”, you can add multiple software. |
| - Name | The name of software used to generate the dataset. |  |
| - Version | The version of the software used to generate the dataset. |  |
| Related Material | Information, such as a persistent ID or citation, about the material related to the Dataset, such as appendices or sampling information available outside of the dataset. | By clicking “+”, you can add multiple related materials. | 
| Related Dataset | Information, such as a persistent ID or citation, about a related dataset, such as previous research on the dataset's subject. | By clicking “+”, you can add multiple related datasets. |
| Other Reference | Information, such as a persistent ID or citation, about another type of resource that provides background or supporting material to the dataset. | By clicking “+”, you can add multiple references. |
| Data Source | Information, such as a persistent ID or citation, about sources of the dataset (e.g. a book, article, serial, or machine-readable data file). | By clicking “+”, you can add multiple data sources. | 
| Origin of Historical Sources | For historical sources, the origin and any rules followed in establishing them as sources. |  |
| Characteristics of Sources | Characteristics not already noted elsewhere. |  |
| Documentation and Access to Sources | Methods or procedures for accessing data sources and/or any special permissions needed for access. |  |

## Access conditions

| Metadata field | Description | Tips |
|----|----|----|

## FAIRVault Decision Tree

For the implications of the Decision Tree fields, see [guidelines for restricting access to confidential or sensitive datasets](../datatags/index.md)

| Metadata field | Description | Drop-down options | Tips |
|----|----|----|----|
| Ethical concerns? | Are there ethical concerns regarding disclosure of the data? | <ul><li>Ethical concerns apply </li><li>No ethical concerns</li></ul> | Choose ‘Ethical concerns apply’ if disclosing the data could raise ethical concerns. E.g., if it risks harming individuals or groups, involves sensitive personal or cultural information, includes data from vulnerable populations, lacks proper informed consent for sharing, or could be misused in ways that cause discrimination, stigmatization, or other negative consequences. Ethical concerns also apply if disclosure would violate legal, institutional, or community agreements.|
| Underlying 3rd party confidentiality? | Is the dataset subject to confidentiality obligations towards third parties? | Choose from the drop-down list. (3rd party confidentiality applies, No 3rd party confidentiality) | Choose ‘3rd party confidentiality applies’ if the dataset contains information that is subject to confidentiality agreements with third parties. E.g., data provided by external organizations, companies, or collaborators under a contract containing a confidentiality clause or a non-disclosure agreement (NDA). |
| Valorisation potential? | Is there a valorisation potential related to the data? | Choose from the drop-down list. (Valorisation potential applies, No valorisation potential) | Choose 'Valorisation potential applies’ if the data has potential commercial value. E.g., if it could be used for developing products, services, patents, or innovations, or if it holds relevance for industry partners, startups, or other external stakeholders. |
| Dual/military use? | Can the data be misused or is there any dual or military use potential? | Choose from the drop-down list. (Dual/military use potential, No dual/military use) | Choose ‘Yes’ if the dataset (research results or techniques) may lend themselves to military purposes or if they could be applied for both civil and military purposes, even if not intended for military use. |
| Research security or misuse? | | 

