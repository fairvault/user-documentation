---
title: "Red"
layout: default
nav_order: 3
parent: Datatags
---

# Red data tag: legally risky or highly sensitive data with strict curatorial control

A dataset must be classified with a red data tag when it contains data that poses substantial legal, or public risk if released without unconditional safeguards.  
Files are deposited normally in FAIRVault, but *remain strictly restricted at all times — there are no dataset access-request mechanisms for users to apply through the interface.

Access to datasets classified under the red data tag is always evaluated case-by-case by data curators and curators alone.  
To initiate this process, researchers must directly contact the FAIRVault curators. The FAIRVault curators may then draft specific Data Use or Data Transfer Agreements where required.

## Example FAIRVault dataset
A Digital Humanities researcher archives a set of personal testimonies containing legally risky material, such as statements involving medical malpractice disputes or confessions describing criminal behavior, including severe public-risk cases like child abuse.  
While these files are deposited in FAIRVault for preservation and research integrity, access is explicitly mediated by curators of that specific institution, in concert with their legal teams, and only granted where a bona fide lawful and justified need exists.

## How to classify?

a) Fill out the the metadata fields relating to the FAIRVault decision tree. This comprises of questions related to the confidentiality of the data.  
b) Make sure to fill out the [Decision Tree questionnaire](https://ugent.qualtrics.com/jfe/form/SV_0od3zuglm2D01P8) and include the response summary - which you will receive by email - as an unrestricted file in your dataset deposit.

- Provide information for the most sensitive data contained in the dataset, for each type of sensitivity. *E.g.: if one file contains personal data and another is important for commercial valorization, both questions should be answered positively.*

If there are high sensitivity or confidentiality risks, the dataset may get a **red** data tag.
- When submitting the dataset for review, the data curators will review the data tag classification.

More information: [FAIRVault Decision Tree for sensitivity of research data.](https://fairvault.github.io/user-documentation/docs/datatags/decision-forest/)

## Checklist when depositing
 - [ ] Deposit dataset files in FAIRVault
 - [ ] Ensure **all files are restricted**, with no access-request feature enabled
 - [ ] Provide complete metadata guidance fields - [link to metadata guidance](../guides/Metadata_overview_v02.pdf)
 - [ ] Upload the response summary from the decision tree as documentation (unrestricted unless exceptionally necessary)
 - [ ] Select 'Custom Dataset Terms' in the license dropdown and provide a concise Terms of Use summary for curator review
 - [ ] Submit dataset for curator review

## Actions for the data curator
- [ ] Review metadata
- [ ] Review the decision tree responses
- [ ] Review file restriction settings
- [ ] Review terms, add the necessary information
- [ ] Indicate the correct data tag, and if necessary the correct legitimate opt out reason for open sharing

## Implementing access restriction to data files for datasets with a Red data tag
- After uploading the files, select the dataset files which should be restricted and click 'Edit' on the right hand side
- In the small drop-down, click 'Restrict'

![Edit files to restrict access](../guides/images/FV_restrict_files_1.png)

- Uncheck the box that says "allow access requests"
