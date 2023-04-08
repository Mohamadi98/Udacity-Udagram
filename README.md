# Udacity-Udagram
## Description
This project details the process of deploying a full-stack application into the AWS cloud services, along with Circleci that is used to create an automated deployment
pipeline.
## Getting Started
- Clone the repo locally to your device
- Use your code editor to open the repo
- Navigate to the root of the repo 
## Project Setup
- Make sure to crate `.env` file and populate the file with those environment variables to connect to the database (a database creation is aslo needed)
```
POSTGRES_USERNAME
POSTGRES_PASSWORD
POSTGRES_DB
POSTGRES_HOST
POSTGRES_PORT
```
- From the root directory use `npm run frontend:install` to install the frontend dependencies
- From the root directory use `npm run api:install` to install the backend dependencies
- Start the the frontend using `npm run frontend:start`
- Start the backend using `npm run api:start`

Note: you will need to provide the link which the server is running on in `udagram/udagram-api/src/environments/environment.ts`
example:
```
export const environment = {
  production: false,
  appName: "Udagram",
  apiHost: "http://localhost:8080/api/v0"
};
```
## Technologies used
- Node
- Express framework
- Angular

## Docs
- The related docs to the deployment process can be found in ./Docs/Screenshots and ./Docs/Diagrams

## Website
- The website can be accessed through this link: http://my-bucket827426616813.s3-website-us-east-1.amazonaws.com/
