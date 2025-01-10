
# Hakai Data Catalogue Review Process

As it currently stands there is no internal, formalized review process for the metadata records that are created for the Hakai Catalogue through the metadata intake form. Submissions of metadata records are currently tracked through e.g. GitHub issues, but only for ERDDAP datasets. Below are some recommendations that can be made to improve the efficiency of reviewing and publishing records, and ensuring consistency of metadata quality.

Edits to the issue template should be made here: https://github.com/HakaiInstitute/hakai-metadata-entry-form/blob/main/firebase-functions/functions/dataset-name.md

--------

## Initial Submission

Right now, anyone with a Google account can sign up and create a metadata record. While the metadata intake form is fairly self-explanatory, reducing the number of people able to create records could help with efficiency, training and quality consistency across the records, especially as the Metadata Intake Form profile is updated.

> **Recommendation:** Each program within Hakai should have 1 or 2 people dedicated to creating and maintaining the metadata records developed for the program. This should help improve accuracy across metadata records. Any updates or changes made to the Metadata Intake Form can then be communicated to this select group.

## Submission Review

Once the required fields are populated, the records can be submitted. A total of 18 people are currently listed as being able to review the quality of the metadata record prior to publication.

> **Recommendation:** when populating a metadata record, the data provider has to specify a minimum of 1 reviewer to assess the quality of the metadata record. If no reviewer is assigned, a notification should automatically be sent to the Principal Investigator (PI) listed in the record.

The reviewers should use a checklist to determine whether the quality of the metadata and the contents of the data package are sufficient and accessible prior to publication. A draft version of the Hakai Metadata Catalogue Review Checklist can be found here. A Hakai CIOOS Data Stewards should determine whether the requirements for publication to CIOOS (Pacific) Catalogue are met [link to checklist with CIOOS (meta)data requirements?]

## Reviewer/Submitter Agreement

For future records, should a CIOOS representative also be assigned to determine whether the record should/can be harvested by CIOOS? Or is this something that we’d like data providers themselves to do by selecting that option? If a CIOOS representative be involved, I think they should only be responsible for determining whether or not the record meets the quality required for CIOOS [see below]?

> **Recommendation:** Prior to publishing a submitted record, (both) reviewer(s) must have ‘signed off’ (selecting a checkbox) on the metadata quality. A checklist should be made available that can be used as reference material to ensure that the quality of the metadata record meets minimum requirements.

The final quality and accuracy of the metadata record is the responsibility of the identified Metadata Custodian(s). A traceable record of who reviewed the metadata should be made available. A DOI can be minted once the metadata record is published, and this can be added to the metadata record by the Data Owner or the Metadata Custodian(s).

## CIOOS Requirements

Requirements for dataset to be harvested to CIOOS

- Should include EOVs
- Doesn’t matter how much data there is (big or small)
- Data shouldn’t be derived or synthesis products
- Data should not be under embargo
