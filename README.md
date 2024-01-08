
# Project Title
Hosting a Full Stack Application

## URL to app

http://andihostingfullstack.s3.amazonaws.com/index.html

http://udagram-api-dev.us-east-1.elasticbeanstalk.com/api/v0/

## Infrastructure description

The infrastructure for this project is hosted on AWS. It consists of the following components:

- AWS S3 (Simple Storage Service): This service is used for web hosting and storing static files for your application. It allows you to easily distribute and deliver content to users. The front-end of your application is hosted on S3.
- AWS RDS (Relational Database Service): RDS is used for hosting your database. It provides a managed database service that makes it easy to set up, operate, and scale a relational database in the cloud. Tne database for your application is hosted on RDS.
- AWS Elastic Beanstalk: Elastic Beanstalk is used for deploying and managing your application. It provides a platform as a service (PaaS) for deploying and running applications in multiple languages. It simplifies the process of deploying and scaling your application. The back-end of your application is hosted on Elastic Beanstalk.
- CircleCI: CircleCI is a continuous integration and delivery platform that automates the building, testing, and deployment of your application. It integrates with your GitHub repository to trigger builds and run tests whenever changes are pushed to the main branch.
- GitHub: GitHub is a web-based hosting service for version control and collaboration. It allows you to store and manage your source code and collaborate with other developers.

![architecture-diagram](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/diagrams/architecture-diagram.png?raw=true)

## App dependencies

The application is built using the following technologies:

- Node.js 14.x
- NPM 6.x
- Ionic CLI 6.x
- AWS CLI 2.x
- Express 4.x
- Postgres 12.x
- Sequelize 5.x
- Typescript 4.x

## Pipeline description

The pipeline for this project is implemented using CircleCI. It consists of the following steps:
1. The pipeline is triggered whenever changes are pushed to the main branch of the GitHub repository.
2. The application backend is built and deployed to Elastic Beanstalk.
3. The application frontend is built and deployed to S3.

In the following diagram, you can see the pipeline steps in more detail:

![pipeline-diagram](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/diagrams/pipeline-diagram.png?raw=true)


## Screenshots

![screenshot1](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot1.png?raw=true)
![screenshot2](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot2.png?raw=true)
![screenshot3](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot3.png?raw=true)
![screenshot4](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot4.png?raw=true)
![screenshot5](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot5.png?raw=true)
![screenshot6](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot6.png?raw=true)
![screenshot7](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot7.png?raw=true)
![screenshot8](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/screenshots/Screenshot8.png?raw=true)

