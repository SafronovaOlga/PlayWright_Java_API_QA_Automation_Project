# QA-Automation-Playwright-Java-todomvc
Automated UI &amp; API testing with Java + Playwright. Demo app. Clean code, Page Object Model, TestNG.

## How to Run Tests
```bash
mvn clean test
```

## How to View Allure Report
```bash
allure serve allure-results

## 🏗️ Project Structure

```
project-root/
├── pom.xml
├── testng.xml
├── .gitignore
├── README.md
├── src/
│   ├── main/
│   │   └── java/
│   │       └── pages/
│   │           └── HomePage.java
│   └── test/
│       └── java/
│           ├── base/
│           │   └── BaseTest.java          # Playwright setup/teardown
│           ├── tests/
│           │   └── HomePageTests.java
│           └── utils/
│               └── TestData.java
└── allure-results/
````

