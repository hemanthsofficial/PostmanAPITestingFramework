# PostmanAPITestingFramework
## Framework Overview

This framework is designed for testing open-source APIs of SimpleBooks.

## Technologies Used:
- **JavaScript** for programming.
- **NewMan** for CLI integration.
- **Data-Driven Testing** using CSV.
  
## Features:
- **Pre-request Script**: Set up for generating values dynamically on API requests.
- **API Response Validation**: Tests are used to validate the API responses received.
- **Query Parameters**: Set in variables for easy customization and testing.
- **HTML Reports**: Generated for test execution tracking and reporting.

# Project Structure

The framework is organized with the following files:

- **README.md**: The project's documentation. It describes the framework's purpose, features, technologies used, and how to use it.
- **SimpleBooks_InputData.csv**: A CSV (Comma Separated Values) file used for data-driven testing. It contains multiple sets of data that will be used as input for the CreateOrder API request.
- **SimpleBooks_APITesting.postman_collection.json**: The core of the framework. This JSON file contains the Postman collection. It defines all the API requests, tests, pre-request scripts, and other configurations.
- **SimpleBooks_APITesting.postman_results.json**: Contains the results of test run in json format. It shows the test results, including pass/fail counts, response times, and other details.
- **SimpleBooks_APITesting.postman_results.html**: Contains the results of test run in html format. It shows the test results, including pass/fail counts, response times, and other details.
- **Newman_Commands.txt**: Contains instructions and commands for setting up and using Newman, the command-line tool for running Postman collections.

![napkin-selection (6)](https://github.com/user-attachments/assets/dbe31e03-027a-4b84-96bc-9a312dea7252)
