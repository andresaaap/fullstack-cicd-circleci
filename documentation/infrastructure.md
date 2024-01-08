## Infrastructure description

The infrastructure for this project is hosted on AWS. It consists of the following components:

- AWS S3 (Simple Storage Service): This service is used for web hosting and storing static files for your application. It allows you to easily distribute and deliver content to users. The front-end of your application is hosted on S3.
- AWS RDS (Relational Database Service): RDS is used for hosting your database. It provides a managed database service that makes it easy to set up, operate, and scale a relational database in the cloud. Tne database for your application is hosted on RDS.
- AWS Elastic Beanstalk: Elastic Beanstalk is used for deploying and managing your application. It provides a platform as a service (PaaS) for deploying and running applications in multiple languages. It simplifies the process of deploying and scaling your application. The back-end of your application is hosted on Elastic Beanstalk.
- CircleCI: CircleCI is a continuous integration and delivery platform that automates the building, testing, and deployment of your application. It integrates with your GitHub repository to trigger builds and run tests whenever changes are pushed to the main branch.
- GitHub: GitHub is a web-based hosting service for version control and collaboration. It allows you to store and manage your source code and collaborate with other developers.

![architecture-diagram](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/diagrams/architecture-diagram.png?raw=true)