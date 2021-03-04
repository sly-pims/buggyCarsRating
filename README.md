### Testing approach
The testing approach can be found here: https://github.com/sly-pims/buggyCarsRating/wiki

### Bug Report
The bug report can be found here: https://github.com/sly-pims/buggyCarsRating/blob/main/Documents/Bug%20Report.docx

### How to run the test
For user simplicity the test is self contained and should not require any installation. 

Simply download the zip file from here: https://drive.google.com/file/d/1lthqipSyZ9aOAdkEwiCqwq42qMxNK1G2/view?usp=sharing

**Note:** the zip file could not be uploaded to Github due to the size limitation on free accounts.
**Note 2:** Goole Drive will produce a warning, due to the size of the file it cannot scan it for viruses.

Unzip the folder then double click the Cypress.exe. The first launch takes a bit of time.
Once Cypress is open, click Select manually and chose the BuggyCarsAutomation folder, path should looks  like ""../BuggyCarsRating/BuggyCarsAutomation
When the specs files are visible, simply click the Run 4 integration specs.

During the process you may see a Windows Firewall window appearr, select desired setting and close.

**Note:** all tests should be passing, however the tests were designed with a CI framework in mind. Due to this the tests can only be run once. To run them more than once, you will need to modify "Moose12" in the following files:
BuggyCarsAutomation/cypress/integration/home_form.specs.js
BuggyCarsAutomation/cypress/integration/model_form.specs.js
BuggyCarsAutomation/cypress/integration/profile_form.specs.js

A search and replace will do the trick.
