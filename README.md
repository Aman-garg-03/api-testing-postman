# Passenger Service API Testing | Postman Automation Framework

> **91.67% Test Pass Rate** | 25 Automated Tests | OAuth2 Authentication | CRUD Operations

Designed and executed comprehensive API testing strategy for a Passenger Management System, identifying critical defects before production deployment. 

**Role:** QA Test Lead | **Sprint:** 3 | **Team Size:** 4 QA Engineers | **Duration:** July 7-21, 2025
## 🛠️ Technical Skills Demonstrated

| Skill | Implementation |
|-------|----------------|
| **API Testing** | Postman Collections, REST API validation, HTTP methods (GET/POST/DELETE) |
| **Authentication** | OAuth2 client credentials flow, token management, Keycloak |
| **Scripting** | JavaScript test scripts, pre-request automation, response parsing |
| **Test Strategy** | Test planning, execution tracking, defect reporting, regression testing |
| **Tools** | Postman, Newman (CLI), Jira, JSON, Git |
| **Methodologies** | Agile/Scrum, Sprint planning, retrospectives, CI/CD-ready testing |

## 📊 Test Coverage Summary

### APIs Tested (6 endpoints)
1. **POST** `/token` - OAuth2 authentication (5 assertions)
2. **POST** `/addPassenger` - Create passenger records (5 assertions)
3. **GET** `/viewPassengerById/{id}` - Retrieve by ID (5 assertions)
4. **GET** `/viewPassengerList` - List all passengers (5 assertions)
5. **GET** `/viewPassengerByNameMobile/{name}/{mobile}` - Search functionality (5 assertions)
6. **DELETE** `/deletePassengerById/{id}` - Delete records (3 assertions)

**Total Tests:** 25 | **Passed:** 23 | **Failed:** 2 | **Execution Time:** 1.45s
