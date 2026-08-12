# **API Assignment - DMoney Style REST API Testing with Newman**

## **Content**
1. [Introduction]
2. [Test Cases Scenario]
3. [API Endpoint Details]
4. [How to run the project]
5. [Postman API Documentation Link]
6. [Technology Used]
7. [Project Structure]
8. [Newman Report]

## Introduction

This project is a Postman/Newman automated test suite for dMoney API, simulating financial transactions where users transfer virtual/demo money between Admin, Agent, Customer, and Merchant accounts.

## Test cases scenario

1. Admin Login.
2. Admin creates a 2 Customer, 1 Agent, 1 Merchant.
3. System logs in and deposits money to the Agent.
4. Agent logs in and deposits money to Customer 01.
5. Customer 01 logs in and sends money to Customer 02.
6. Customer 02 logs in, cashes out to Agent, and pays a Merchant bill.

## API Endpoint Details

- **User API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/user_](https://dmoney.roadtocareer.net/api-docs/user)

- **Transaction API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/transaction_](https://dmoney.roadtocareer.net/api-docs/transaction)
- **Partner Key**: X-AUTH-SECRET-KEY: `ROADTOSDET`

## How to run the project

- Clone this project
   ```console
   git clone https://github.com/diparani22/dmoney_API_Testing-B19.git
   ```
- Open with any code editor / Command Shell
- Give the following command ```npm i``` and ```node .\report.js```

## Postman API Documentation Link
  
  - API Documentation Link:**https://documenter.getpostman.com/view/28551494/2sBY4VJxBr**

## Technology Used
- Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
- Newman
- newman-reporter-htmlextra

## Project Structure

```
API-Assignment/
├── Collection/
│   └── B19-API-Assignment.postman_collection.json   # Postman collection
├── Reports/
│   └── report.html                                  # Generated Newman HTML report
├── report.js                                         # Newman runner script
└── package.json
```

## Newman Report
### REPORT SUMMERY
-  <img width="385" height="542" alt="image" src="https://github.com/user-attachments/assets/d98bd27c-811c-4ebb-8045-ade3a0440659" />
<br>
### TOTAL REQUESTS
<img width="383" height="575" alt="image" src="https://github.com/user-attachments/assets/a538ac63-964a-4177-a1d1-77c3c818b291" />




