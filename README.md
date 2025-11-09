# API Automation REST Assured

API automation framework implementing CRUD flows for Restful Booker using Rest Assured, TestNG, and Allure reporting.

`mvn test -Dsurefire.suiteXmlFiles=testng.xml`

<img width="1130" alt="Framework Overview" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/69f398b3-8798-4fba-a091-3b1e321dcc7d">


## Project Link

Base API: https://restful-booker.herokuapp.com

## Tech Stack

1. Rest Assured
2. Java
3. Apache POI, TestNG, Maven
4. Jackson and GSON
5. Log4j2
6. Allure Report
7. Hybrid folder structure framework
8. Jenkinsfile (CI)

<img width="1262" alt="Folder Structure" src="https://github.com/PramodDutta/APIAutomationRestAssured/assets/1409610/2d58bf82-0ffb-4fcb-a2d9-cf26920fa7b5">


## How to Run

### Basic suite
```
mvn clean test
```

### Integration suite (Create Booking, Create Token, Update, Delete)
```
mvn clean test -DsuiteXmlFile=testng-integration.xml
```

### Assignment 1

Create the Collections for the This Test cases : 

App - Restful Booker (with Auth)

1. Create a booking, update the booking name, get by id and verify
2. Create a booking, delete by id, verify GET returns not found
3. From list of booking ids, pick one, update and verify via GET by id
4. Create a booking, then delete it
5. Invalid creation — wrong payload / malformed JSON
6. Attempt to update a deleted id (should fail)


Test per request:
- Response body
- Status code
- Headers

———

Create collection checklist:
- [ ] Restful Booker CRUD operations
- [ ] Add tests from snippets
- [ ] Integration scenarios (hard coded)


		
Assert style guidance:
- Assert: unexpected / should not happen (rare)
- Expect: actual == expected (primary)
- Should: strong requirement (edge cases)



### Assignment 2
Full CRUD test cases for the GitHub Repo API with integration scenarios:
1. Create test cases template
2. Submit Postman collection with tests
3. Add integration scenarios
4. Write advanced Postman tests


### Assignment 3
1. Get token (2-step)
2. Upload image on Imgur with OAuth 2.0 (hash generated)
3. Retrieve image and verify link hash


### Assignment 4
Complex JSON parsing with map/filter operations

### Assignment 5
Add JSON Schema validation for POST and PUT requests (Restful Booker)

---

## 📫 Connect With Us

**Wajid Daud Tamboli**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/wajid-daud-tamboli-3217b031a)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wajidddaudtamboli123@gmail.com)

**Email**: wajidddaudtamboli123@gmail.com

---
