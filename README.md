# Emfluence Webform
Emfluence Contact Save RESTful API integration with Drupal Webforms.
Version 7.x-0.3-dev

## About
Integrates Emfluence CRM's /save RESTful endpoint with forms created with the Webforms module on Drupal 7 using curl. You must have curl installed and enabled.

## Instructions

### Installation
Place the files into the modules folder as you would for any Drupal module. Since this module is not hosted by Drupal, you will need to manually update when necessary.

### Operation
The module only captures the values listed below. To captures these values, set the Key of the form fields in the Webform to the following:

* First Name - firstName
* Last Name - lastName
* Email - email
* Phone - phone
* Address 1 - address1
* City - city
* State - state
* Zip Code - zipCode
* Group IDs - groupIDs

Note: Groups IDs should be comma delineated. It is also recommended that this field be of the hidden field type.

If the Key is not set in the webform correctly as listed above, it will not be included. First Name, Last Name, and Email are required by Emfluence.

## Note
This module should be considered minimally maintained, and is shared without guarantee or otherwise. It is hoped that sharing this here will be of some small benefit to your project.
