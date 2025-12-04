---
title: "Orange"
layout: default
nav_order: 3
parent: Datatags
---

# Orange data tag: confidential and moderate sensitivity data with access control

If a dataset can only be shared under restricted access conditions, but does not contain highly sensitive data, the dataset can be tagged with an orange data tag.  
All authenticated users of FAIRVault can submit a Data Access request. This access request will be evaluated. If necessary (e.g. for personal data), a Data Use or Data Transfer Agreement will be drafted and signed by both parties before access can be granted.

## Example FAIRVault dataset
A researcher in the field of Linguistics studies the evolution of regional dialects. The researcher conducts interviews and conversations with native speakers of all generations and audio-records those. Additionally, contact details and a wide variety of socio-demographics are collected (data- and place of birth, gender, location history, education level,….). The researcher has consent of all the participants to process this data. The researcher uploads the raw dataset to the FAIRVault.

## How to classify?

a) Fill out the the metadata fields relating to the FAIRVault decision tree. This comprises of questions related to the confidentiality of the data.  
b) Make sure to fill out the [Decision Tree questionnaire](https://ugent.qualtrics.com/jfe/form/SV_0od3zuglm2D01P8) and include the response summary - which you will receive by email - as a file in your dataset deposit.

- Provide information for the most sensitive data contained in the dataset, for each type of sensitivity. *E.g.: if one file contains personal data and another is important for commercial valorization, both questions should be answered positively.*

If there are sensitivity or confidentiality risks, the dataset may get an **orange** data tag.
- When submitting the dataset for review, the data curators will review the data tag classification.

More information: [the FAIRVault Decision Forest for sensitivity of research data](decision-forest.md)

## Checklist when depositing
 - [ ] Provide all mandatory and recommended metadata [todo: insert link to metadata guidance]
- [ ] Upload the dataset files AND **implement restriction on the dataset files**. Allow access requests. See [instructions below](##Implementing-access-restriction-to-data-files-for-datasets-with-an-Orange-data-tag).
 - [ ] Upload the response summary from the Decision Tree questionnaire (see above), do not restrict this file or other documentation files if not strictly necessary
 - [ ] Add the orange dataset guestbook for confidential datasets
 - [ ] Edit the Terms: select 'Custom Dataset Terms' in the license dropdown and provide a brief summary of the Terms of Use. The curator will review and further complete the terms during the review process.
 - [ ] Submit the dataset for review

## Actions for the data curator
- [ ] Review metadata
- [ ] Review the decision tree responses
- [ ] Review terms, add the necessary information
- [ ] Indicate the correct data tag, and if necessary the correct legitimate opt out reason for open sharing

## Implementing access restriction to data files for datasets with an Orange data tag
- After uploading the files, select the dataset files which should be restricted and click 'Edit' on the right hand side
- In the small drop-down, click 'Restrict'
![Edit files to restrict access](../guides/images/FV_restrict_files_1.png)

- Allows access requests. 
- Add a clarification under which conditions access could be granted.
