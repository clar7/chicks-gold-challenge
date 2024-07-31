# chicks-gold-challenge
TEST PLAN




Contents


INTRODUCTION ………….…………………………………………..…… 2
PURPOSE ……………………….….………………………………………….2
OBJECTIVES ………………………………………………………….……….2
RESOURCES ……….……………………….………………………………….2
RISKS ……………….………………………………….…….………………….2
DELIVERABLES .………………………………….……………………………3

























	


1. Introduction: 
The application is a stateless RESTful API, which facilitates scalability and deployment.

2. Purpose:
Verify the functionality of the API endpoints.
Ensure correct integration with other services.
Evaluate performance under different loads.
Validate the security of the application.
    Backend:
Testing the API endpoints at http://localhost:3000/.
Verifying API responses (status codes, response bodies, headers).

    Frontend:
Manual testing of the login form.

3. Objectives:
Ensure all API endpoints function correctly.
Verify that API responses are correct and in the expected format.
Identify and correct errors in the API’s business logic.
Ensure the API handles error cases appropriately.
Verify that the login form on the frontend works correctly with valid username and password.

4. Resources:
Tools: Swagger for API testing, web browser for frontend testing.
Environments: Local environment (http://localhost:3000/).
Data Sets: Specific test data for each endpoint (can be JSON, URL parameters, etc.), valid login credentials

5.Risks:
Risk: The API might not handle error cases properly.
Mitigation: Include exhaustive tests for error cases and input validations.
Risk: Inconsistencies in API responses.
Mitigation: Clearly define and document expected response formats and validate against them.
Risk: Performance issues under load.
Mitigation: Conduct load and stress tests in later stages (though not included in this initial plan).
Risk: The login form might not authenticate the user correctly.
Mitigation: Test the login with valid credentials and verify the authentication flow.

6. Deliverables:
Test Report: Detailed documentation of executed test cases, obtained results, and any found errors.
Error Log: List of errors found during testing, with details and steps to reproduce them.


Test Cases: https://docs.google.com/spreadsheets/d/1drlRv7Y3upRXdABq5cdqBn9tx4B19X9H9OxtSbalmMc/edit?usp=sharing
Document: https://docs.google.com/document/d/1Wg-mKgi02Ihyvd5thsR60g-QinyqLeO7Z9auGd8St7I/edit?usp=sharing


