### CI / CD

## Introduction to CI/CD
CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development
The "CI" in CI/CD always refers to continuous integration, which is an automation process for developers. Successful CI means new code changes to an app are regularly built, tested, and merged to a shared repository
The "CD" in CI/CD refers to continuous delivery and/or continuous deployment, which are related concepts that sometimes get used interchangeably.

## Overview of CI/CD
In software development, multiple team members develop code and contribute to creating the software’s functionality. When multiple people contribute to a code base, it is important to maintain its integrity and ensure that any team member can retrieve the latest version and build and run it locally.
Two important aspects should be maintained to assure the code base's stability. The first aspect is to ensure that the code is compiling without errors. The second aspect is to ensure that all unit tests validating code behavior pass, including the latest code changes, at a very high percentage.

## Introduction to GitHub Actions
GitHub Actions are a set of actions in a GitHub repository workflow. 
Action: The smallest building block of a workflow is an action, which can be identified as an individual task.
Artifacts: The files generated when you build your software project or test your software project are artifacts.
Event: An event triggers a workflow in GitHub Actions. Once a code change is pushed, or a pull request is made, an event can be set up in GitHub Actions to trigger the workflow.
GitHub Actions are a set of actions in a GitHub repository workflow. 
Action: The smallest building block of a workflow is an action, which can be identified as an individual task.
Artifacts: The files generated when you build your software project or test your software project are artifacts.
Event: An event triggers a workflow in GitHub Actions. Once a code change is pushed, or a pull request is made, an event can be set up in GitHub Actions to trigger the workflow.
GitHub-Hosted Runners: Hosted runners are machines similar to hosted agents in Azure DevOps pipelines. They are supported in Windows, Linux, and macOS. 
Job: A job is a set of steps set up to run in a single runner. A job can comprise one or more actions.
Self-Hosted Runner: Self-hosted runners are useful when you have special hardware configurations or software requirements for building your applications or running your jobs. 
Step: A task that is an action or a command is identified as a step. All steps in a job run in the same runner.
Workflow: In a GitHub repo, the process set up in a YAML file defining the build, test, package, or deployment jobs is called a workflow.
Workflow File: The YAML file stored in the github/workflows/ folder in your GitHub repository is a workflow file.
Workflow Run: A workflow executes based on the preconfigured triggers/events. 

## Variable
In common CI/CD systems, we can define custom variables
Example in GitHub Actions:

env:
varname1: value1
varname2: value2

## Secrets and Token
Secrets are important in any CI/CD pipeline implementation tool. They protect sensitive information, such as connection strings and passwords, and keep passwords or other secrets applied in application configuration settings.






