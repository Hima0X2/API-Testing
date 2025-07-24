# API-Testing

This repository contains multiple API testing projects focused on different platforms and technologies. Each folder is a separate module showcasing practical API testing skills using **Postman**, **Newman**, and **REST Assured** with real-world test scenarios.

---

## 📁 Project Structure

- `Postman/` – API test collections and environments using Postman and Newman  
- `REST Assured/` – API automation using Java-based REST Assured framework

---

## 🧪 How to Run Tests

### 🔸 Postman

#### Option 1: Using Postman GUI
1. Open Postman
2. Import `.json` collection files from the `Postman` folder
3. Set the appropriate environment file (if any)
4. Run the collection using the **Runner**

#### Option 2: Using Newman (CLI)
```bash
newman run collection.json -e environment.json -r cli,html
```
Replace collection.json and environment.json with actual file names.

### 🔹 REST Assured

REST Assured is used for automating REST API tests in Java.

#### 🔧 Prerequisites:
- Java (8+)
- Gradle
- IDE like IntelliJ IDEA or Eclipse

#### ▶️ Running the Tests
1. Open the `REST Assured` folder in your IDE
2. Ensure dependencies are installed (check `build.gradle` file for REST Assured dependencies)
3. Run test classes or use the following Gradle command:
```bash
gradle clean test
```
#### ⚙️ Gradle Setup
Make sure your build.gradle file includes the necessary dependencies for REST Assured:
```bash
dependencies {
    testImplementation 'io.rest-assured:rest-assured:4.4.0'
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.7.1'
    testImplementation 'org.junit.jupiter:junit-jupiter-engine:5.7.1'
    testImplementation 'org.hamcrest:hamcrest:2.2'
}
```
