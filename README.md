# selenium-Protractor-cucumber-js
Basic framewok to automate angular or non-angular webapps using protractor wrapped on selenium webdriver and server.
Mock data properties can be used to dry run the feature

**Table of Contents**
* [Installation](#installation)
    * [WebDriver Setup](#webdriver)
* [Usage](#usage)
    * [Feature file](#feature-files)
    * [Step Definition](#step-definitions)
    * [Page objects](#page-objects)
    * [logs](#log4js)
    * [multiple-cucumber-Report](#multiple-cucumber-Report)
    * [Mock Setup](#mock)

## Installation
git clone <path>
npm install
npm i -g protractor (If notalready installed globally)
npm i -g webdriver-manager (If not already installed globally)

### WebDriver Setup
node webdriver-manager update (If webdriver-manager is added to path use => webdriver-manager update)
node webdriver-manager start (If webdriver-manager is added to path use => webdriver-manager start)

or, use package.json script below (if webdriver added to path)
npm run startWebDriver

## Usage
npm run mmtest (Can be run as property Mock=true, any valid URL can be used for mock, defaults to google.com)

### Feature files
features/MMExercise-I.feature

### Step definitions
features/stepDefinitions

### Page objects
features/pages

### logs
log4js console output (Default)

### multiple-cucumber-Report
tmp/report/index.html (Existing Report from last run)

### Mock Setup
Update Mock property as true in features/properties/prop.properties (Defaults to true)

