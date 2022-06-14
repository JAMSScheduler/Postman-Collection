# Postman-Collection
A Postman collection of JAMS API endpoints for testing

Load this collection into your own Postman installation to begin testing the JAMS REST API endpoints.

For a more complete list of the API endpoints, you can view the Swagger page from your own server via http://servername/jams/swagger

CHANGES TO BE MADE AFTER IMPORT:

There is a Pre-Request script configured to login and set a variable with the authorization token.  That script will need to be edited to add a valid username and password for authenticating in your environment.

There is a Variable defined for the JAMSSite, which contains the base url (servername/jams) for the API endpoints.  This may need to be adjusted.
