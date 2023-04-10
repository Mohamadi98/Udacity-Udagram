# Pipeline Workflow

## Environment setup
- the first phase in the pipeline is to setup the environment as a node application. After that we need to setup the elasticbeanstalk and the aws-cli which will be used in the deployment process, and for that,  specific environment variables must be passed to the pipeline (aws-access-id, aws-secret-key, aws-region)

## Dependencies installation
- In this phase the dependencies of the frontend and backend are installed to be used in code.

## Project build 
- In this phase the project frontend and backend are built. The result of this phase for the frontend is a ./www/ folder which is what will be deployed to the S3 bucket. For the backend a ./www/ folder will also be created, but an archive.zip inside ./www/ is the one that is deployed to the elasticbeanstalk

## Project deployment
- In this last phase the frontend and backend are deployed to their specified aws services