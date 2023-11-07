# Wildrydes
This is a repository for AWS Tutorial for building a Serverless Web Application
with AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito

![architecture image](https://github.com/begalievn/wildrydes-site/blob/main/images/architechture.png)

## 1. Static Web Hosting
AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

## 2. User Management
Amazon Cognito provides user management and authentication functions to secure the backend API.

## 3. Serverless Backend
Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.

## 4. RESTful API
JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.
