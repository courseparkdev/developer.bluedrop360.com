# API documentation for SWMB-Approved Training Providers

SkillsPass currently supports the following APIs for SWMB-approved training providers:

 - [Learning Record API](./learning-record-api)
	 - Allows training providers to submit learning records to the SWMB training registry.

 - [Class Offering API](./class-offering-api)
	 - Allows training providers to publish in-person or virtual class offerings to the SWMB Marketplace.

## Common Documentation

### Authentication

Authentication is documented here: 
[BLN API - Authentication](https://bluedrop360apiv2network.docs.apiary.io/#introduction/authentication)

### Error and Status Codes

Error Codes

- general 
	- returned when it's an expected error, but it's not an invalid schema error.
- forbidden
	- returned when you are authorized, but have insufficient privileges.
- internal 
	- returned when the API encounters an unexpected internal error.
- invalid
	-	returned when the request failed because the data given did not match the required schema.
- notFound
	- returned when the requested resource was not found.
- unauthorized
	- returned when you are not authorized (not logged in).
- unknown
	- returned when an expected error occurred, but we have no message to return about it.

HTTP Status Code Summary

- 200 OK
	- Everything worked as expected.
- 204 No Content
	- Everything worked as expected, but there is no response body.
- 400 Bad Request
	- Often missing a required parameter.
- 401 Unauthorized  
	- No valid API key provided.
- 403 Forbidden  
	- Access denied.
- 404 Not Found  
	- The requested item doesn't exist.
- 500, 502, 503, 504 Server errors
	- Something went wrong on our end.

---
&copy; 2022 Bluedrop ISM

