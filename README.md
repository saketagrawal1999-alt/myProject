# myProject
Hybrid automation framework for Facebook login page testing, combining data-driven and keyword-driven approaches for reusable, scalable, and maintainable test execution.
# 🔐 Facebook Login - Hybrid Automation Framework

## 📘 Overview

This project is a **Hybrid Test Automation Framework** built using **Java, Selenium WebDriver, and TestNG** to automate and validate the Facebook login functionality.

The framework combines **Data-Driven** and **Keyword-Driven** approaches to ensure scalability, maintainability, and reusability of test scripts.

---

## 🚀 Features

* Hybrid framework design (Data-Driven + Keyword-Driven)
* Page Object Model (POM) implementation
* Reusable and modular test components
* Test data management using Excel/CSV
* Cross-browser testing support
* Logging and reporting integration
* Easy scalability for new test cases

---

## 🛠️ Tech Stack

* **Language:** Java
* **Automation Tool:** Selenium WebDriver
* **Test Framework:** TestNG
* **Build Tool:** Maven (if used)
* **Design Pattern:** Page Object Model (POM)

---

## 🎯 Test Scenarios Covered

* ✅ Login with valid credentials
* ❌ Login with invalid credentials
* ⚠️ Empty username/password validation
* 🔔 Error message verification
* 🧩 UI elements presence and validation

---

## 📂 Project Structure

```id="x82ka9"
project-root/
│── src/test/java/
│   ├── testcases/       # TestNG test classes
│   ├── pages/           # Page Object classes
│   ├── utilities/       # WebDriver setup, helpers
│   ├── testdata/        # Excel/CSV test data
│
│── src/main/resources/
│   ├── config.properties
│
│── reports/             # TestNG reports
│── logs/                # Execution logs
│── pom.xml              # Maven dependencies
```

---

## ▶️ How to Run the Project

### Prerequisites

* Java JDK (8 or above)
* Maven installed
* Browser (Chrome/Edge)
* IDE (Eclipse / IntelliJ)

### Steps

1. Clone the repository:

   ```
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open project in IDE

3. Install dependencies:

   ```
   mvn clean install
   ```

4. Run tests:

   * Right-click `testng.xml` → Run
     OR

   ```
   mvn test
   ```

---

## 📊 Reporting

* TestNG generates default reports in the `/test-output` folder
* Logs are captured for debugging and analysis

---

## 🔧 Configuration

Update `config.properties` for:

* Browser selection
* Base URL
* Timeout settings

---

## 🤝 Contribution

Contributions are welcome!

* Fork the repository
* Create a new branch
* Commit your changes
* Submit a Pull Request

---

## 📌 Future Enhancements

* CI/CD integration (Jenkins / GitHub Actions)
* Parallel execution using TestNG
* Advanced reporting (Extent Reports / Allure)
* Docker integration

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👤 Author

**Saket Agrawal**
GitHub: https://github.com/myProject
