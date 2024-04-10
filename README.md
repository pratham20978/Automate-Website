# Automated eCommerce Website Testing

This test suite automates the testing of an eCommerce website, covering functionalities such as login, product search, and retrieving product details.

## Test Cases

### 1. Login Process
- **Test Successful Login**: Verifies successful user login to the eCommerce website.
- **Test Search Product**: Automates product search functionality on the website.
- **Test Get Product Details**: Retrieves product details including text and price.

## Usage

To use the test suite, follow these steps:

1. Ensure you have Python 3 installed on your system.
2. Clone the repository containing the test suite to your local machine.
3. Navigate to the directory containing the test suite.
4. Run the following command to execute the test suite:

    ```bash
    python3 test_ecommerce_website.py
    ```

## Test Automation Process

### 1. Login Process
- **Set Up**: Initializes the base URL for the eCommerce website.
- **Successful Login Test**: Sends a POST request with login credentials and verifies successful login.
- **Search Product Test**: Automates product search functionality by sending a GET request with a search query.
- **Get Product Details Test**: Retrieves product details including name, description, and price by sending a GET request to the product details endpoint.

## Test Report

Upon running the test suite, a test report will be generated in CSV format (`test_report.csv`) containing details of the test results. The report includes the test name and the result (Passed or Failed) for each test case.

Additionally, the test results will be printed to the console, showing the total number of tests run, the number of failures, errors, and successes.

