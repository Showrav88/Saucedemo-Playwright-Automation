# SaucedemoAutomation-Playwright-with-javascript-

## 1️⃣ Project Overview

This is an end-to-end automation test: the user logs in with valid credentials, adds one product to the cart, verifies the product name, and logs out of the project for SauceDemo.

###The project demonstrates:

1.UI automation use Playwright with JavaScript.

2.Allure Reporting for beautiful test reports

3.Page Object Model (POM) design pattern for test maintainability

## 2️⃣ Technologies & Tools Used

-JavaScript – main programming language

-Playwright Test – automation framework

-Allure Playwright & Allure Commandline – test reporting

-Node.js – runtime environment

-Rimraf – clean old reports before generating new ones

## 3️⃣ 📂 Project Structure

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
## 4️⃣ Installation & Setup
1. Clone the repo
   
```bash
git clone https://github.com/Showrav88/SaucedemoVAutomation-Playwright-with-java-script-.git
cd SaucedemoV

```
2. Install dependencies
```bash
npm ci
npx playwright install --with-deps

```
3. Install Allure (if not installed globally)
```bash
npm install -D allure-playwright allure-commandline

```
4.Install Utility Package
```bash
npm install --save-dev rimraf

```
## 5️⃣ Running Project Locally
1. Clean previous reports:
```bash
npm run allure:clean

```
2.Run tests and generate results:
```bash
npm run test:allure

```
3.Generate HTML report:
```bash
npm run allure:generate
```
4.Open report in browser:
```bash
npm run allure:open

```
## Project result :
[Drive link](https://drive.google.com/file/d/1_9iqFCRy5gkuz2OT1BfRV4MkISSLEDYr/view?usp=sharing)

##  Contact / Author
Author: Showrav Karmakar








