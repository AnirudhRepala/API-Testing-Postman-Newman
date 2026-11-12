# API Testing Project – Postman & Newman

## Project Overview
This project demonstrates API testing using Postman and Newman on the Fake Store API.

It covers CRUD operations, request validation, response assertions, data-driven testing, and command-line execution using Newman.

## Tools & Technologies
- Postman
- Newman CLI
- JavaScript (Postman test scripts)
- JSON
- HTML Test Reporting
- Git & GitHub

## Testing Coverage
- GET – Retrieve products
- POST – Create a product
- PUT – Update a product
- DELETE – Delete a product
- Response status code validation
- Response body validation
- JSON schema validation
- Data-driven testing

## Newman Execution
The Postman collection was executed through Newman CLI.

**Execution results:**
- Total requests: 11
- Total assertions: 50
- Passed assertions: 50
- Failed assertions: 0
- Iterations: 1

## HTML Reporting
Generated an HTML report using Newman to view test execution results, request details, and assertion outcomes.

The report is available in the `newman` folder.

## Repository Structure
- `Collections/` – Postman collections
- `DataFiles/` – Test data and collection files
- `newman/` – HTML execution reports
- `package.json` – Project dependencies and configuration
- `.gitignore` – Ignored files and folders


## CI/CD Integration with Jenkins

- Integrated Newman with Jenkins for automated API test execution.
- Connected the Jenkins Freestyle project to the GitHub repository.
- Executed the Postman collection using Newman CLI.
- Configured HTML test report generation and publishing in Jenkins.
- Verified successful automated execution through Jenkins.

## Test Execution Results

| Metric | Result |
|---|---:|
| Total Requests | 11 |
| Total Assertions | 50 |
| Passed Assertions | 50 |
| Failed Assertions | 0 |
| Skipped Tests | 0 |
| Iterations | 1 |

**Build Status: SUCCESS**
## Author
Anirudh Repala
