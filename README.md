# Playwright QA Automation Demo

![Playwright Tests](https://github.com/emmanuel-moreno-sdet/playwright-qa-automation-demo/actions/workflows/playwright.yml/badge.svg)

A lightweight end-to-end testing framework built with Playwright.  
This project demonstrates UI testing, API testing, cross-browser execution, and CI integration using GitHub Actions.

## Features
- UI tests with Playwright Test Runner
- API testing examples
- Cross-browser execution (Chromium, Firefox, WebKit)
- CI pipeline using GitHub Actions
- HTML reporting and test artifacts

## Getting Started

Install dependencies:
```
npm install
```
Run tests:
```
npx playwright test
```
View HTML report:
```
npx playwright show-report
```
## Project Structure
```
playwright-qa-automation-demo/
├── tests/                     # UI, API, and login test specs
│   ├── example-ui.spec.ts
│   ├── example-api.spec.ts
│   └── login.spec.ts
├── playwright.config.ts       # Playwright configuration (browsers, reporters, settings)
├── package.json               # Project dependencies and scripts
├── package-lock.json          # Locked dependency versions
├── README.md                  # Project documentation
└── .github/
    └── workflows/
        └── playwright.yml     # GitHub Actions CI pipeline

```
## Author
Emmanuel Moreno  
Quality Assurance Professional | ISTQB Certified