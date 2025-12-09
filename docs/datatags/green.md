---
title: "Green"
layout: default
nav_order: 2
parent: Datatags
---

# Green data tag: non-confidential and low sensitivity data with some access control

If a dataset can be shared with minor access restrictions, the dataset can be tagged with a green data tag.
**Anyone with a FAIRVault account**, [institutional or via ORCID](../guides/getting-started.md#access), browsing to the FAIRVault repository will be able to access the dataset files.

## Example FAIRVault dataset
A researcher in the field of psychology has executed a large online survey on the use of social media by adults and how it is interwoven in their personal- and professional life. The survey consists of likert scales on statements (“to what level do you agree that….”), it inquires what social media platforms respondents are using and how much time to spend on each platform, and the collection of socio-demographic details (age, gender, professional situation, household composition). Consent is used as a legal ground, and respondents indicated that they agree to sharing the data. Every entry in the dataset has been pseudonymised to such a level that there are at least 4 entries for identical socio-demographical information (i.e. it is impossible to single-out responses based on socio-demographical data). 

## How to classify?

a) Fill out the the metadata fields relating to the FAIRVault decision tree. This comprises of questions related to the confidentiality of the data.  
b) Make sure to fill out the [Decision Tree questionnaire](https://ugent.qualtrics.com/jfe/form/SV_0od3zuglm2D01P8) and include the response summary - which you will receive by email - as a file in your dataset deposit.

- Provide information for the most sensitive data contained in the dataset, for each type of sensitivity. *E.g.: if one file contains personal data and another is important for commercial valorization, both questions should be answered positively.*

If there are minor sensitivity or confidentiality risks, the dataset will get a **green** data tag.
- When submitting the dataset for review, the data curators will review the data tag classification.

More information: [the FAIRVault Decision Tree for sensitivity of research data](decision-forest.md)

## Checklist when depositing
 - [ ] Provide all mandatory and recommended metadata - [link to metadata guidance](../guides/Metadata_overview_v02.pdf)
 - [ ] Upload the dataset files AND **implement restriction on the dataset files**. Do not allow access requests. See [instructions below](##Implementing-access-restriction-to-data-files-for-datasets-with-a-Green-data-tag).
 - [ ] Upload the response summary from the Decision Tree questionnaire (see above), do not restrict this file or other documentation files if not strictly necessary.
 - [ ] Add the green dataset guestbook for non confidential datasets.
 - [ ] Edit the Terms: select the FAIRVault v1.0 data licence from the dropdown.
 - [ ] Submit the dataset for review.

## Actions for the data curator
- [ ] Review metadata
- [ ] Review the decision tree responses
- [ ] Review terms
- [ ] Indicate the correct data tag, and if necessary the correct legitimate opt out reason for open sharing
- [ ] In case of a confirmed green data tag: Grant file permissions to all authenticated users

## Implementing access restriction to data files for datasets with a Green data tag
- After uploading the files, select the dataset files which should be restricted and click 'Edit' on the right hand side
- In the small drop-down, click 'Restrict'
![Edit files to restrict access](../guides/images/FV_restrict_files_1.png)

- Unselect the box that allows access requests. Access will be granted to all authenticated users by the data curator when reviewing your dataset for publication.
- Add a clarification that data is available to all authenticated users of FAIRVault
![Do not allow access requests, since all authenticated users will have access](../guides/images/FV_restrict_files_disable_request.png)
