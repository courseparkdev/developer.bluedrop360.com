# Learning Record API

## Background

The purpose of the Learning Record API is to allow SafeWork Manitoba (SWMB) approved training providers to submit learning records to the SafeWork Manitoba training registry. 

The API currently supports only learning records for courses related to SafeWork Manitoba endorsed courses. This is captured in the `trainingStandardKey` attribute in the reference documentation, and the complete list of support values is included in the Technical section below. Training providers must always map their learning records to one of these standard courses.

SWMB-approved training providers are issued a unique identifier, which must be included with every request. Please refer to the `networkKey` attribute in the reference documentation.

## Supported Actions

[*Add Learning Record*](https://bluedrop360apiv2network.docs.apiary.io/#reference/learning-records/add-learning-record/add-a-learning-record)

Call to add a learning record to the SWMB system.

- Each learning record must include detailed learner information to ensure the learning record can be associated with the correct user. If the learner cannot be found, a new one will be created.
- Currently, learning records cannot be directly removed from the system. They can, however, be voided or updated by contacting the SkillsPass Customer Success team (support@skillspass.com).

## Technical

Supported values for *trainingStandardKey*:

- *TBD*





