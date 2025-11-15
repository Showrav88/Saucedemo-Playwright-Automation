# SaucedemoAutomation-Playwright-with-javascript-

## 1️⃣ Project Overview

This is an end-to-end automation test: the user logs in with valid credentials, adds one product to the cart, verifies the product name, and logs out of the project for SauceDemo.

###The project demonstrates:

1.UI automation use Playwright with JavaScript.

2.Allure Reporting for beautiful test reports

3.Page Object Model (POM) design pattern for test maintainability

4.Cross Browsers testing

## 2️⃣ Technologies & Tools Used

-JavaScript – main programming language

-Playwright Test – automation framework

-Allure Playwright & Allure Commandline – test reporting

-Node.js – runtime environment

## 3️⃣ Installation & Setup
1. Clone the repo
   
```bash
git clone https://github.com/Showrav88/Saucedemo-Playwright-Automation.git
cd Saucedemo-Playwright-Automation

```
2. Install dependencies
```bash
npm ci
npx playwright install --with-deps

```
##  Running Project Locally

3.Run tests

```bash
npm run test
```

## 4️⃣ 📂 Project Structure

```bash
SaucedemoV/
├─ tests/                        # All your test specs
│  └─ specs/
│      └─ userLogin.spec.js
├─ pages/                        # Page classes (POM)
│  └─ login.js
├─ objects/                      # Object repositories (locators)
│  ├─ loginObjects.js
│  └─ addToCartObjects.js
├─ resources/                    # Test data / utilities
│  └─ testData.js
├─ playwright.config.js          # Playwright configuration
├─ package.json                  # Project dependencies & scripts
├─ node_modules/
├─ allure-results/               # Generated Allure results (ignored in git)
├─ allure-report/                # Generated Allure HTML report (ignored in git)
├─ .github/
│  └─ workflows/
│      └─ playwright.yml         # GitHub Actions workflow
├─ .gitignore
├─ README.md

```

## 5️⃣ Allure Report Generate 
1. Install Allure if wanted allure report 
```bash
npm install -D allure-playwright allure-commandline

```
2.Install Utility Package
-Rimraf – clean old reports before generating new ones
```bash
npm install --save-dev rimraf

```

3. Clean previous reports:
```bash
npm run allure:clean

```
4.Run tests and generate results:
```bash
npm run test:allure

```
5.Generate HTML report:
```bash
npm run allure:generate
```
6.Open report in browser:
```bash
npm run allure:open

```
## Project result :
[Drive link](https://drive.google.com/file/d/1_9iqFCRy5gkuz2OT1BfRV4MkISSLEDYr/view?usp=sharing)

##  Contact / Author
Author: Showrav Karmakar









