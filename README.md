# PayPal Integration with Spring Boot (Sandbox)

## Description
This is a sample Spring Boot application demonstrating how to integrate PayPal Sandbox with a Spring Boot application for payment processing.

## Prerequisites
- Java 8 or later installed
- Maven installed
- PayPal Developer Account (to get sandbox credentials)

## Setup
1. Clone this repository: 
2. Navigate to the project directory:

3. Set up PayPal Sandbox:
- Log in to your PayPal Developer Account (https://developer.paypal.com/).
- Create a sandbox business account and get the client ID and secret.
- Add sandbox accounts for testing buyer and seller transactions.

4. Configure PayPal credentials in the application:
- Open `application.properties` file located in `src/main/resources` directory.
- Replace `paypal.clientId` and `paypal.clientSecret` with your sandbox client ID and secret obtained from the PayPal Developer Dashboard.

5. Build the project:

6. Run the application:

7. Access the application:
- Open a web browser and go to `http://localhost:8080` to access the application.

## Usage
- This sample application provides endpoints to initiate PayPal transactions.
- Test the PayPal integration by accessing the provided endpoints and simulating transactions.

## Endpoints
- `/paypal/pay`: Initiates a PayPal payment.
- `/paypal/execute-payment`: Executes a PayPal payment.
- Add more endpoints as needed for specific PayPal functionality.

## Additional Resources
- [PayPal Developer Documentation](https://developer.paypal.com/docs)
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)


