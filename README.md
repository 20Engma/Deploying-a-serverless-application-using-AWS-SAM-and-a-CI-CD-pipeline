# Deploying-a-serverless-application-using-AWS-SAM-and-a-CI-CD-pipeline

Project Overview
In this project, you will leverage the AWS Serverless Application Model (AWS SAM) to create and publish a serverless application. The deployment process will be automated using AWS CodeDeploy and AWS CodePipeline, with a focus on implementing a traffic shifting deployment model. This approach allows for a controlled and gradual rollout of new application updates, minimizing disruptions and ensuring a seamless user experience.

Traffic Shifting Deployment Model
The traffic shifting deployment model is a crucial strategy for DevOps teams when maintaining applications. It enables the phased introduction of updates, allowing teams to monitor the performance and stability of new versions while still serving users with the previous version. This method also facilitates rapid rollbacks if any issues arise. By automating this process, you can significantly enhance the speed of application delivery, aligning with Continuous Integration and Continuous Deployment (CI/CD) practices.

Project Objectives
By the end of this project, you will be able to:

Build and Locally Test Your Application:
Use the AWS SAM CLI to develop your serverless application and perform local testing to ensure functionality and performance.

Package and Deploy Your Application:
Package your application and its dependencies, followed by deploying it to AWS Lambda, ensuring it is ready for production use.

Automate the CI/CD Pipeline:
Set up and automate a CI/CD pipeline using AWS CodePipeline, enabling a continuous flow of updates from development to deployment while supporting traffic shifting.

Perform a Traffic Shifting Deployment:
Execute a traffic shifting deployment strategy for your application, allowing for a gradual transition to the new version, with real-time monitoring and rollback capabilities.
