# 🧪 Selenium Automation Framework (Page Object Model)

A test automation framework built with **Selenium WebDriver**, **Java**, **TestNG**, and **Maven**, structured using the **Page Object Model (POM)** design pattern for clean, maintainable, and scalable UI test automation.

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/TestNG-EF2D5E?style=for-the-badge&logo=testinglibrary&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" />
</p>

---

## 📖 Overview

This project demonstrates a **Page Object Model** approach to Selenium test automation — separating page interactions (locators + actions) from test logic, so tests stay readable and pages are easy to maintain as the UI changes.

## 📂 Project Structure

```
SeleniumAutomationPOM/
├── src/                # Page objects, test classes, and utilities
├── test-output/        # TestNG execution reports
├── pom.xml             # Maven dependencies and build configuration
├── testng.xml          # TestNG suite/test configuration
└── .gitignore
```

## ⚙️ Tech Stack

- **Language:** Java
- **Automation Tool:** Selenium WebDriver
- **Test Framework:** TestNG
- **Build Tool:** Maven
- **Design Pattern:** Page Object Model (POM)

## 🚀 Getting Started

### Prerequisites
- Java JDK installed
- Maven installed
- A supported browser + matching WebDriver

### Run the tests

```bash
git clone https://github.com/bunnySrinu/SeleniumAutomationPOM.git
cd SeleniumAutomationPOM
mvn clean test
```

Test execution reports are generated in the `test-output/` directory after each run.

## 🗺️ Roadmap

- [ ] Add CI pipeline (GitHub Actions/Jenkins) to run tests automatically
- [ ] Integrate reporting tool (Extent Reports / Allure)
- [ ] Add cross-browser testing support
- [ ] Add data-driven testing examples

## 🤝 Contributing

Suggestions and PRs are welcome — feel free to open an issue.
