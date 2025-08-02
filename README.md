# API Automation with Postman + Newman

This project tests the ReqRes user API using Postman and Newman.

## Features
- Create, Get, Update, Delete User tests
- Assertions on response code and body
- Newman CLI support with HTML reporting

## Run the tests
```bash
newman run colAPI Automation Project - User API.postman_collection.jsonlection.json -e Production.postman_environment.json -r cli,html

## Folder Structure
/api-automation-postman/
├── API Automation Project - User API.postman_collection.json
├── Production.postman_environment.json
├── README.md