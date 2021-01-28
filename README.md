# Serverless Web Application
You 'll create a simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML based user interface for indicating the location where they would like to be picked up and will interface on the backend with a RESTful web service to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.

### Requirements
+ AWS Amplify
+ DynamoDB
+ API Gateway
+ Lambda
+ Amazon Cognito

### Modules
This workshop is divided into five modules. Each module describes a scenario of what we're going to build and step-by-step directions to help you implement the architecture and verify your work.
+ Static Web Hosting
+ User Management
+ Serverless Backend
+ RESTful APIs

### Usage
+ Update config services into js/config.js
    ```
    userPoolId
    userPoolClientId
    region
    invokeUrl
    ```

### Reference
+ [Build a Serverless Web Application](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)