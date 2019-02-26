# Learning Record API

## Background

The purpose of the Learning Record API is to allow Ministry of Labour (MOL) approved training providers to submit learning records to the MOL Certificate Management System (CMS). This method of submission is meant to replace the current method, which involves the physical submission of training records via the mailing of a USB key.

The API currently supports only learning records for courses related to both MOL standards: Working at Heights and Joint Health and Safety Committee 2014. This is captured in the trainingStandardKey attribute in the reference documentation, and the complete list of support values is included in the Technical section below. Training providers must always map their learning records to one of these standard courses.

MOL-approved training providers are issued a unique identifier by MOL, which must be included with every request. Please refer to the networkKey attribute in the reference documentation.

## Supported Actions

*Add Learning Record*

Call to add a learning record to the CMS system.

- Each learning record must include detailed learner information to ensure the learning record can be associated with the correct user. Note that MOL administrators will have the ability to manually match any learners that could not be matched automatically. If the learner cannot be found, a new one will be created.
- Currently, learning records cannot be directly removed from the system. They can, however, be voided or updated by contacting the Bluedrop Customer Success team (support@bluedrop360.com).

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
- *JHSC-2014-2-E-I*
	- JHSC - Part 2 (English, In-Person) 
- *JHSC-2014-1-F-I*
	- CMSS - partie 1 (French, In-Person) 
- *JHSC-2014-2-F-I*
	- CMSS - partie 2 (French, In-Person) 
- *JHSC-2014-Refr-E-I*
	- JHSC – Refresher (English, In-Person) 
- *JHSC-1996-1-E-I*
	- JHSC 1996 - Part 1 (English, In-Person) 
- *JHSC-1996-2-E-I*
	- JHSC 1996 – Part 2 (English, In-Person)





