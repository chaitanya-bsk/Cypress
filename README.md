# Cypress
Set up 
Prerequisites
Install node - v20.8.0
Install cypress - Cypress package version: 13.3.0

# Getting Started 1. Clone this repository to your local machine:

# .ENV FILE 
In current cypress project, I have taken user_name and password as test data. If we still feel it as sensitive data that doesn’t need to be exposed we can move into cypress.env()
(This file or environment variables are typically used for configuring and storing sensitive information or configuration settings that your tests or applications need.)
		

# How to execute test-
npx cypress run

npx cypress open --browser chrome
By default, Cypress will open its interactive test runner. You can select specific test files to run or run all tests.


# Folder Structure- 
cypress/ 
├── fixtures/ # Test data 
├── integration/ # Test scripts 
├── plugins/ # Cypress plugins 
├── support/ # Custom commands and helpers 
cypress.json # Cypress configuration


# Report generation 
We use Mochawesome for generating test reports. To generate an HTML report after running tests, use:
npm run generate-report

Once test is completed view it in html location 
/cypress/reports/html/index.html
