## Project Infrastructure
the infrastructure of this project is based on the AWS services for static web hosting (S3 bucket), server deployment (elasticbeanstalk), and database management (rds).

# S3 Bucket
- Initialized to host the static web files that would serve as the frontend of this project.

# Elasticbeanstalk
- Initializes an environment to host the backend, provides a link that can be used by the client side as a server URL.

# RDS
- To store the data on the website (i.e user information, user post, etc..). Initialized a database management system which a postgres database is used.