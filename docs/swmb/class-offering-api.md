# Class Offering API

## Background

The purpose of the Class Offering API is to allow   
SafeWork Manitoba (SWMB) approved training providers not using the SkillsPass system to list class offerings in the SWMB Marketplace.

Note that the API provides a listing service only for the SWMB Marketplace. Any attempts at booking training will be redirected back to the training provider’s own website, and it is up to the individual training provider to manage that booking accordingly.

The API currently supports only class offerings related to SWMB standards. This is captured in the _trainingStandardKey_ attribute in the reference documentation, and the complete list of support values is included in the _Technical_ section below.

SWMB-approved training providers are issued a unique identifier by SWMB, which must be included with every request. Please refer to the _networkKey_ attribute in the reference documentation.

## Supported Actions

[*Add Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/add-class-offering/add-a-class-offering)
Call to add a class offering to the SWMB Marketplace.

[*Patch Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/class-offering/patch-a-class-offering)
Call to update information for an existing class offering in the SWMB Marketplace.

[*Delete Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/class-offering/delete-a-class-offering)
Call to remove a class offering from the SWMB Marketplace.


## Technical

Supported values for *trainingStandardKey*:

- *TBD*
