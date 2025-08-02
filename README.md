# API Automation with Postman + Newman

This project tests the ReqRes user API using Postman and Newman.

## Features
- Create, Get, Update, Delete User tests
- Assertions on response code and body
- Newman CLI support with HTML reporting

## Folder Structure
```
/api-automation-postman/
├── postman_collection.json
├── environment.json
├── README.md
```

![image_alt](https://github.com/montriv/API-Automation-Postman/blob/main/api-automation.png?raw=true)

## Run the tests
```bash
newman run API Automation Project - User API.postman_collection.jsonlection.json -e Production.postman_environment.json -r cli,html
