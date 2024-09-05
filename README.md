## Note From @DataMinion

This template is a fork from the original AWS Amplify Angular template. I have made changes to the original template because the amplify team does not seem to be updating their version.

It has been my experience using amplify that certain a project needs to begin at a certain base state or the initial project creattion will fail. In order to include advanced concepts in the template I will make heavy use of commented out code. I will atempt to clearly note different phases of complexity when uncommenting these features will make them function cleanly in your code

Change log:
1. this is an Angular project not Angular.js
2. the current project deployment fails because the NPM builder in the amplify service is incmpatible with the Angular CLI version 18. I have modified the amplify.yml to target Angular CLI 17 to prevent this build error

## Note on Angular Version

The dataminion-main branch will attempt to target the latest stable version of Angular. At the time of this writing the latest stable is 18. I will do my best to maintain seperate branches that match the major version of Angular with all of my notes until it becomes to much. 

to find a template for a specific version of angular check the branches for dataminion-main-angular-<Major Version>

## AWS Amplify Angular Starter Template

This repository provides a starter template for creating applications using Angular and AWS Amplify, emphasizing easy setup for authentication, API, and database capabilities.

## Overview

This template equips you with a foundational Angular application integrated with AWS Amplify, streamlined for scalability and performance. It is ideal for developers looking to jumpstart their project with pre-configured AWS services like Cognito, AppSync, and DynamoDB.

## Features

- **Authentication**: Setup with Amazon Cognito for secure user authentication.
- **API**: Ready-to-use GraphQL endpoint with AWS AppSync.
- **Database**: Real-time database powered by Amazon DynamoDB.

## Deploying to AWS

For detailed instructions on deploying your application, refer to the [deployment section](https://docs.amplify.aws/angular/start/quickstart/#deploy-a-fullstack-app-to-aws) of our documentation.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.