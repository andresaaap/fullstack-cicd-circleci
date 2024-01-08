## Pipeline description

The pipeline for this project is implemented using CircleCI. It consists of the following steps:
1. The pipeline is triggered whenever changes are pushed to the main branch of the GitHub repository.
2. The application backend is built and deployed to Elastic Beanstalk.
3. The application frontend is built and deployed to S3.

In the following diagram, you can see the pipeline steps in more detail:

![pipeline-diagram](https://github.com/andresaaap/fullstack-cicd-circleci/blob/main/diagrams/pipeline-diagram.png?raw=true)