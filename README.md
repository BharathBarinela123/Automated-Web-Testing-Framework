# **Automated Web Testing Framework**

## **Project Overview**  
This project is a Selenium-based automated testing framework developed using **Java, Maven, and Cucumber**. It automates web application testing by implementing the **Page Object Model (POM)** for modular and reusable test scripts. The framework supports **data-driven testing** using Apache POI and generates structured test reports with ExtentReports.

## **Tech Stack Used**  
- **Programming Language:** Java  
- **Automation Framework:** Selenium WebDriver  
- **Testing Frameworks:** JUnit, TestNG, Cucumber (BDD)  
- **Build Tool:** Maven  
- **Reporting:** ExtentReports  
- **Dependency Management:** WebDriverManager  
- **Data Handling:** Apache POI (Excel-based testing)  

## **Project Achievements**  
- Automated login functionality and form submissions, reducing manual effort.  
- Implemented POM to enhance test maintainability and reusability.  
- Used **Cucumber BDD** to improve test readability and collaboration.  
- Integrated **Apache POI** for reading/writing test data from Excel.  
- Improved test execution with **WebDriverManager** for dynamic driver handling.  
- Generated detailed test reports using **ExtentReports**.  

## **Setup & Installation**  
1. **Clone the Repository:**  
   ```bash
   git clone <repo-url>
   cd <project-folder>
   ```

2. **Install Dependencies:**  
   Ensure you have **Java 8+**, **Maven**, and **Selenium WebDriver** installed.  
   ```bash
   mvn clean install
   ```

3. **Run Tests:**  
   To execute test cases, run:  
   ```bash
   mvn test
   ```

## **Usage**  
- The framework reads test cases from `features/` (BDD feature files).  
- Results are logged in the `reports/` directory using ExtentReports.  
- Supports running tests with different browser configurations via WebDriverManager.  

## **License**  
This project is open-source and available under the [MIT License](LICENSE).  
