# Assesment MIFX - Sauce Demo Automation

This project contains web UI automation tests for the Sauce Demo application using Katalon Studio.

## Prerequisites

- [Katalon Studio](https://www.katalon.com/download/) (version 8.3.0 or later)
- Java JDK (version 8 or later)
- Gradle (for build management, optional)

## Setup

1. Ensure Katalon Studio is installed on your machine.
2. Open Katalon Studio.
3. Click on **File > Open Project** and select the `Assesment MIFX.prj` file.

## Running Tests

1. In Katalon Studio, navigate to the **Test Suites** folder.
2. Right-click on the "Login.ts" test suite and select **Run**.

## Test Cases

- **Login - Positive**: Tests successful login scenarios.
- **Login - Negative**: Tests failed login scenarios with invalid credentials.

## Build

This project uses Gradle for build management. To build:

```
gradle build
```

## Data Files

- `LoginData.xlsx`: Contains test data for login scenarios.

## Object Repository

Contains page objects for Login and Inventory pages.
