# Cypress Automated Test for Daft.ie

## Overview

This repository contains an automated test script using Cypress for searching out the "Garage" keyword on the Daft.ie website. The test involves opening the Daft homepage, searching for a Sale Ad in county Dublin, applying the "garage" keyword filter, and verifying the results.

## Prerequisites

Before running the test, ensure that you have the following installed:

- Node.js and npm

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/ahmadiqbal1/distilled.git

2. Navigate to the project repository

   ```bash  
   cd daft-cypress-automation

3. Install dependencies:

   ```bash  
   npm install

## Running the Test

To execute the automated test, run the following command:

   ```bash  
   npx cypress open

This will open the Cypress Test Runner. Click on the test file (Daft-keyword-search.js) to run the test.
which is located at "cypress\integration\example\Daft-keyword-search.js", SpecPattern is already there in the cypress.config.js 
file to load the test file automatically when the cypress test runner is open.Just click on the file and the execution will be started automatically.


## Github Actions Workflow CI/CD

I have setup the github workflow with Github Actions to enable the tests to run automatically on every code change or a github push
Github Actions are enabled on my github repo and the location to the .yml can be found at 
.github\workflows\cypress.yml


