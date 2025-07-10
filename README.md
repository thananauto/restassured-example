

# RestAssured-Java Demo Project

[![Java CI with Maven](https://github.com/thananauto/restassured-example/actions/workflows/test.yml/badge.svg)](https://github.com/thananauto/restassured-example/actions/workflows/test.yml)

A beautiful and comprehensive demo repository for API testing with [RestAssured](https://rest-assured.io/) in Java. This project showcases best practices for:

- **Serialization & Deserialization**
- **RequestSpecification & ResponseSpecification**
- **QueryableRequestSpecification**
- **AssertJ for advanced assertions**
- **CI integration with GitHub Actions**
 
---

## 🚀 Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/thananauto/restassured-example.git
   cd restassured-example
   ```
2. **Get a Bearer Token:**
   - Create an account at [GoRest](https://gorest.co.in/) and obtain your API token.
3. **Run the tests:**
   ```bash
   mvn clean test
   ```
4. **View the reports:**
   - Navigate to `./target/reports/*` for the latest execution report.
   - Or see the latest published report [here](https://thananauto.github.io/restassured-example/index.html).

---

## 📦 Features

- Real-world API test scenarios
- Clean code structure with `RequestSpecification` and `ResponseSpecification`
- Serialization/Deserialization examples
- AssertJ for expressive assertions
- Docker & CI ready (see `Dockerfile` and `docker-compose.yml`)
- Automated daily test runs via GitHub Actions

---

## 🛠️ Requirements

- Java 8 or higher
- Maven 3.x
- [GoRest](https://gorest.co.in/) API token

---

## 🗂️ Project Structure

- `src/` - Test source code
- `pom.xml` - Maven dependencies
- `testNg.xml` - TestNG configuration
- `Dockerfile` & `docker-compose.yml` - Containerization support
- `.github/workflows/` - CI/CD pipeline

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is for demonstration and educational purposes.

---

## 🌐 Links

- [Project Home](https://github.com/thananauto/restassured-example)
- [Latest Report](https://thananauto.github.io/restassured-example/index.html)
- [GoRest API](https://gorest.co.in/)

---

Happy Testing! 🚦

