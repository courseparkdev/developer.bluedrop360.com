# Class Offering API

## Background

The purpose of the Class Offering API is to allow   
Ministry of Labour, Training and Skills Development (MLTSD) approved training providers not using the SkillsPass system to list class offerings in the MLTSD Marketplace.

Note that the API provides a listing service only for the MLTSD Marketplace. Any attempts at booking training will be redirected back to the training provider’s own website, and it is up to the individual training provider to manage that booking accordingly.

The API currently supports only class offerings related to both MLTSD standards: Working at Heights and Joint Health and Safety Committee 2014. This is captured in the _trainingStandardKey_ attribute in the reference documentation, and the complete list of support values is included in the _Technical_ section below. Training providers must always map their class offerings to one of these standard courses.

MLTSD-approved training providers are issued a unique identifier by MLTSD, which must be included with every request. Please refer to the _networkKey_ attribute in the reference documentation.

## Supported Actions

[*Add Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/add-class-offering/add-a-class-offering)
Call to add a class offering to the MLTSD Marketplace.

[*Patch Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/class-offering/patch-a-class-offering)
Call to update information for an existing class offering in the MLTSD Marketplace.

[*Delete Class Offering*](https://bluedrop360apiv2network.docs.apiary.io/#reference/class-offerings/class-offering/delete-a-class-offering)
Call to remove a class offering from the MLTSD Marketplace.


## Technical

Supported values for *trainingStandardKey*:

- *WAH-E-B*
	- Working at Heights - Full course (English, Blended)  
- *WAH-E-I*  
	- Working at Heights - Full course (English, In-Person)  
- *WAH-F-I* 
	- Travail en hauteur - cours complet (French, In-Person)
- *WAH-Refr-E-I*
	- Working at Heights - Refresher course (English, In-Person)  
- *WAH-Refr-E-B*
	- Working at Heights - Refresher course (English, Blended)  
- *WAH-Refr-F-I*
	- Travail en hauteur - cours de perfectionnement (French, In-Person) 
- *JHSC-2014-1-E-B*
	- JHSC – Part 1 (English, Blended)
- *JHSC-2014-1-E-I*
	- JHSC - Part 1 (English, In-Person)
- *JHSC-2014-1-E-V*
	- JHSC - Part 1 (English, Virtual)
- *JHSC-2014-2-E-I*
	- JHSC - Part 2 (English, In-Person) 
- *JHSC-2014-2-E-V*
	- JHSC - Part 2 (English, Virtual) 
- *JHSC-2014-1-F-I*
	- CMSS - partie 1 (French, In-Person) 
- *JHSC-2014-1-F-V*
	- CMSS - partie 1 (French, Virtual) 
- *JHSC-2014-2-F-I*
	- CMSS - partie 2 (French, In-Person) 
- *JHSC-2014-2-F-V*
	- CMSS - partie 2 (French, Virtual) 
- *JHSC-2014-Refr-E-I*
	- JHSC – Refresher (English, In-Person) 
- *JHSC-2014-Refr-E-V*
	- JHSC – Refresher (English, Virtual) 
- *JHSC-2014-Refr-F-V*
	- CMSS - refresher (French, Virtual) 
- *JHSC-1996-1-E-I*
	- JHSC 1996 - Part 1 (English, In-Person) 
- *JHSC-1996-2-E-I*
	- JHSC 1996 – Part 2 (English, In-Person)
