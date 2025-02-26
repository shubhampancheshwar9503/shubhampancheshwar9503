### **Overview**  

This repository features a **comprehensive and scalable Selenium Automation Testing Framework** designed for professionals with **strong expertise in Manual, Automation, and API Testing**. Built using **Selenium WebDriver, TestNG, Maven, and Page Object Model (POM)**, the framework optimizes test execution, enhances test coverage, and improves software reliability.  

With integrated **API testing (Postman), SQL for backend validation, and manual testing capabilities**, this framework provides an end-to-end solution for validating software across UI, API, and database layers.  

---  

### **Key Features**  

1. **Selenium WebDriver**  
   - Automates complex browser interactions for **functional and regression testing**.  
   - Supports **cross-browser testing** (Chrome, Firefox, Edge, etc.).  

2. **TestNG & Maven Integration**  
   - Streamlines **test execution, parallel testing, and reporting**.  
   - Manages dependencies and simplifies project builds.  

3. **API Testing (Postman)**  
   - Automates API requests for **functional, integration, and performance validation**.  
   - Ensures seamless data flow between UI and backend services.  

4. **Page Object Model (POM)**  
   - Enhances test **modularity, reusability, and maintainability**.  
   - Reduces **code duplication** for scalable automation solutions.  

5. **Data-Driven & Regression Testing**  
   - Uses **Microsoft Excel** for parameterized test cases.  
   - Ensures stability by testing **various datasets and workflows**.  

6. **Manual Testing & Defect Tracking**  
   - Complements automation with **exploratory and edge-case testing**.  
   - Tracks bugs and test cases using **Jira, Git, and GitHub**.  

7. **Backend Testing with SQL**  
   - Validates **database consistency and data integrity**.  
   - Supports CRUD operations, query validation, and performance testing.  

8. **CI/CD & Version Control**  
   - Integrates automated tests into **Jenkins for CI/CD pipelines**.  
   - Manages test repositories with **Git and GitHub**.  

---  

### **Technologies Used**  

- **Languages**: Core Java, SQL, HTML5  
- **Automation Tools**: Selenium WebDriver, TestNG, Postman  
- **Build & Dependency Management**: Maven  
- **Testing Methodologies**: Data-Driven, Regression, API Testing, Manual Testing  
- **Collaboration & Tracking**: Jira, Git, GitHub  
- **Data Sources**: Microsoft Excel  

---  

### **Project Structure**  

1. **Configuration Files**  
   - `config.properties`: Stores environment variables, credentials, and browser configurations.  
   - `log4j.properties`: Enables logging for debugging and test monitoring.  

2. **Test Scripts**  
   - Organized into modules like **login, search, registration, and form validation**.  
   - Uses **POM classes** for structured web interactions.  

3. **Utilities**  
   - **Excel Utility** – Reads test data for parameterized testing.  
   - **Report Utility** – Generates structured reports post-execution.  
   - **Browser Factory** – Manages browser sessions efficiently.  

4. **TestNG Configuration**  
   - Uses XML files to group, prioritize, and execute test cases efficiently.  
   - Supports **parallel execution** for faster test cycles.  

---  

### **Core Test Scenarios**  

1. **Login Functionality**  
   - Validate login using **valid and invalid credentials**.  
   - Check **error handling** for incorrect inputs.  

2. **Search Functionality**  
   - Test **search results and relevance** for various queries.  
   - Verify response for invalid searches.  

3. **Registration Workflow**  
   - Validate **form fields, constraints, and error messages**.  

4. **API Testing**  
   - Verify **GET, POST, PUT, DELETE** requests.  
   - Validate response codes, schemas, and error handling.  

5. **Database Validation**  
   - Use SQL queries to check **data consistency and backend transactions**.  

---  

### **Setup Instructions**  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/shubhampancheshwar9503/selenium-automation-framework.git
   ```  

2. **Import the Project**  
   - Use **Eclipse or IntelliJ** to open the Maven project.  

3. **Configure Properties**  
   - Update `config.properties` with **base URLs, credentials, and browser settings**.  

4. **Run Test Cases**  
   - Execute tests using Maven:  
     ```bash
     mvn clean test
     ```  

5. **View Reports**  
   - Access HTML reports in the `target/surefire-reports` directory.  

---  

### **Future Enhancements**  

1. **CI/CD Integration**  
   - Automate test execution using **Jenkins pipelines**.  

2. **Advanced Reporting**  
   - Implement **Allure or Extent Reports** for interactive test results.  

3. **API Automation with RestAssured**  
   - Expand API testing beyond Postman for **automated RESTful API validation**.  

4. **Performance Testing**  
   - Integrate **JMeter** to analyze system performance under load.  

---  

### **Contributing**  

- Contributions are welcome!  
- Fork the repository, create a branch, and submit a **pull request**.  
- Report **bugs or feature requests** via GitHub issues.  

---
