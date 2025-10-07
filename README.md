# Kasir AJA API Testing

Part of MySkill’s learning project
This project demonstrates API testing using Postman for the Kasir AJA API endpoints.

---

## Project Overview
The goal of this project is to practice designing and executing API test cases, including:
- Positive and negative testing
- Data-driven testing with CSV input
- Assertion validation using Postman test scripts

---

## Endpoints Tested
| Endpoint | Method | Purpose |
|-----------|---------|----------|
| `/authentications` | POST | Login and get access token |
| `/users` | POST | Create new user |
| `/users` | GET | Retrieve list of all users |

---

##  Tests Implemented
Each request includes at least 2 assertions:
- Validate response status code (e.g., `201 OK`)
- Validate JSON body fields (e.g., message, user name)

Data-driven testing is applied on the **Create User** endpoint using a CSV file.

---

## Tools Used
- **Postman** – API testing and documentation  
- **Notepad / CSV** – data-driven test input  
- **GitHub** – version control and portfolio hosting  

---

## Files in This Repository
| File | Description |
|------|--------------|
| `KasirAJA_API.postman_collection.json` | Postman collection of all requests |
| `users.csv` | Data for data-driven testing |
| `KasirAJA_TestResult.json` | Exported run results (all tests passed) |

---

## Published Documentation
You can view the live Postman documentation here:  
[Kasir AJA API Postman Documentation]([https://documenter.getpostman.com/view/XXXXXX](https://documenter.getpostman.com/view/49033900/2sB3QJNWDv))

---

## Test Summary
All requests executed successfully.  
All assertions **PASSED** in the final test run.
