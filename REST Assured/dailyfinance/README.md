# 🚀 API Testing & Automation Project (Postman + Rest Assured + Gradle)

## 🌐 Live URL
[https://dailyfinance.roadtocareer.net](https://dailyfinance.roadtocareer.net)

---

## ✅ Features Tested (via Postman & Rest Assured)

The following API functionalities were tested by inspecting requests from the browser's Developer Tools (Network tab):

1. Register a new user  
2. Login by admin  
3. Get user list  
4. Search the user by user ID  
5. Edit user info (e.g., first name, phone number)  
6. Login by any user  
7. Get item list  
8. Add an item  
9. Edit item name  
10. Delete an item  

---

## 🧪 Postman Collection

- Created using the captured network requests
- Included both **positive and negative** test cases
- Validated response codes, error handling, and data accuracy

🔗 **Postman Collection Link**:  
[📂 View Collection Documentation](https://www.postman.com/your-username/workspace/your-workspace/documentation/your-doc-id)

---

## 🤖 API Automation using Rest Assured (with Gradle)

Automated the above scenarios using **Rest Assured**, following the **Page Object Model (POM)** design pattern.

### 🔧 Tech Stack

- Language: Java  
- Build Tool: Gradle  
- Testing Framework: JUnit 5 / TestNG  
- Reporting Tool: Allure Reports  
- Library: Rest Assured

---

## 🧱 Project Structure (POM)

```
src/
├── base/
│ └── BaseTest.java
├── endpoints/
│ └── UserEndpoints.java
│ └── ItemEndpoints.java
├── tests/
│ └── UserTests.java
│ └── ItemTests.java
├── utils/
│ └── ConfigReader.java
│ └── TestDataGenerator.java
```

## ⚙️ build.gradle Dependencies

```
dependencies {
    testImplementation 'io.rest-assured:rest-assured:5.3.0'
    testImplementation 'io.qameta.allure:allure-rest-assured:2.24.0'
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.10.0'
    testRuntimeOnly 'org.junit.jupiter:junit-jupiter-engine:5.10.0'
}
```

# 🧪 Running Tests and Viewing Allure Report

## Run tests:
```bash
gradle clean test
```
## Generate & view Allure Report:
```bash
allure serve build/allure-results
```
## 👨‍💻 Author
### Sanjida Akter Samanta

