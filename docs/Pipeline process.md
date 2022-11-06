# Pipeline Process

This application is integrated with CircleCi account which is authorized to access the project repo on Github , detects changes each time there is a pushing process happened to the main branch and start deploying code by these steps :

- Spin up environment

- Preparing environment variables

- Install Node.js

- Checkout code

- Install AWS CLI - latest

- Configure AWS Access Key ID

- Setting Up Elastic Beanstalk CLI

- Install Front-End Dependencies

- Install API Dependencies

- Front-End Build

- API Build

- Deploy App